# Git 使用


工作区--暂存区--本地仓库

1.在电脑上创建一个文件加作为工作区
2.打开文件夹右键git base here 进入当前目录
3.工作区持有项目实践文件


## readme  文档
1.readme文件可以txt文件，也可以md文档
2.一般和项目一起，作为项目说明文档

## 全局配置
1.配置用户名： git config --global user.name '用户名'
2.配置用户邮箱  git config --global user.email '邮箱'
3.一台电脑配置一次就可以了
4.查看你的配置信息：git config --list

## 初始化
1.git init  初始化版本库
2.当前目录路径后面有（master）代表初始化成功
3.在当前目录下会生成一个隐藏文件  .git 代表这是一个版本库
4.千万别操作 .git文件，让他隐藏不管他


S
## 工作区内容提交到本地仓库
1.执行命令 git add 文件名   将工作区内容提交到暂存区
2.命令 git add . 将所有变动（新增 修改 删除 ）提交到暂存区
3.从暂存区提交到本地仓库  git commit -m '提交注释'


## 版本回退
1.命令：git reset --hard HEAD^   回退到上一个版本（一个……代表上一个版本）
2.命令：git reset --hard 版本号 回到指定版本


## 辅助命令
1.命令git status 查看当前目录下操作状态
2.git log 查看日志
3.git reflog 查看简版日志


## 将本地仓库提交到远程仓库
1.在github创建一个远程仓库 git2010
2.本地工作区先提交到本地仓库
3.git remote add origin 远程仓库地址    本地仓库和远程仓库关联
4.git remote -v 查看本地仓库所关联的远程仓库地址
5.git push -u origin master   第一次执行
 git push 把本地仓库推送到远程仓库
 -u origin master 摄制默认提交master分支到origin


## 下载项目到本地
1.克隆项目:git clone 项目远程仓库系统  整个版本库克隆下来
2.git clone 适用于本地没有该项目，直接从远程下载到本地
3.如果本地有该项目，应该直接更新本地  git pull
4.养成先工作区的提交到本地仓库再更新远程到本地
5.git fetch  将远程更新到本地



## 分支操作
1.查看当前仓库所有分支：git branch
2.当前分支前面带有星号*
3.创建分支：git branch 分支名
4.切换分支：git checkout   分支名
5.合并分    git merge 分支名
6.删除分支   git branch -d 分支名
7.git pull origin dev 更新代码到本地，自g合并到当前分支

## 添加协作者

## git忽略列表
1.创建文件：.getignore
2.忽略文件列表
3.再忽略列表中列出不需要提交到把版本库的文件及目录













