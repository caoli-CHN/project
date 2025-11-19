

# README.md

## 首次推送

```
#创建 README 文件
echo "# README.md" >> README.md
```

```
#初始化 Git 仓库
git init
```

```
#添加文件到暂存区
git add README.md
```

```
#提交到本地仓库
git commit -m "first commit"
```

```
#设置主分支为 main
git branch -M main
```

```
#绑定远程 GitHub 仓库
git remote add origin https://github.com/caoli-CHN/project.git
```

```
#推送到 GitHub
git push -u origin main
```

## 更新推送

```
#查看修改状态
git status
```

```
#添加文件到暂存区
git add .
```

```
#提交到本地仓库
git commit -m "修改"
```

```
#推送到 GitHub
git push
```

```
#强制推送覆盖远程仓库
git push origin main --force
```

## 拉取推送

```
#克隆远程仓库到本地
git clone https://github.com/caoli-CHN/project.git
```

```
#进入项目目录，查看当前分支
cd project
git branch
```

```
#拉取远程最新内容
git pull origin main
```

```
#添加文件到暂存区
git add .
```

```
#提交到本地仓库
git commit -m "修改"
```

```
#推送到 GitHub
git push -u origin main
```