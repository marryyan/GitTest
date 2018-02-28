# GitTest
 Test repository for Git  

> 1. git 会忽略空文件夹，如果想要保留文件夹，可以放入 .gitkeep
> 2. .DS_Store 是 Mac 系统的文件夹的自定义属性信息
> 3. .gitignore 只能忽略未追踪过的文件



## init

初始化 `.git` 仓库

```
git init  
```

## clone  

克隆，将云端仓库的内容下载下来  

    git clone https://github.com/marryyan/GitTest.git  

## status  
查询当前 git 状态  

    git status

## add  
添加修改/追踪到暂存区  
添加 index.js 的变化到暂存区

    git add index.js  

多文件:添加 多文件 变化到暂存区

    git add index.js src/ README.md  

简化:添加所有变化到暂存区  

    git add -A

## checkout  
检出文件  

    git checkout .gitignore 

## commit  
将 暂存区 中所有修改提交到本地分支(本地版本库)  

    git commit -m '我修改了一些文件'

## log  
查看 commit 详情  

    git log
## pull

从远程仓库拉取代码与本地同步

```
git pull
```

等同于

```
git fetch && git merge
```

## push

将本地修改提交到远程仓库

```
git push
```