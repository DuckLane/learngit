# 1.git创建版本库

初始化一个Git仓库，使用`git init`命令。

添加文件到Git仓库，分两步：

1. 使用命令`git add <file>`，注意，可反复多次使用，添加多个文件；
2. 使用命令`git commit -m <message>`，完成。

```git
git add readme.txt
git add readme2.txt
git commit -m "add 2 files"
```

# 2. 查看库中文件状态及修改

- 要随时掌握工作区的状态，使用`git status`命令。
- 如果`git status`告诉你有文件被修改过，用`git diff`可以查看修改内容。

```git
git status
git diff readme.txt
```

# 3.版本退回及恢复



