# GitTest
 Test repository for Git  

> 1. git 会忽略空文件夹，如果想要保留文件夹，可以放入 .gitkeep
> 2. .DS_Store 是 Mac 系统的文件夹的自定义属性信息
> 3. .gitignore 只能忽略未追踪过的文件

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
    
