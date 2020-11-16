



#Git 使用


工作区--暂存区--本地仓库

1.在电脑上创建一个文件加作为工作区
2.打开文件夹右键git base here 进入当前目录
3.工作区持有项目实践文件


##readme  文档
1.readme文件可以txt文件，也可以md文档
2.一般和项目一起，作为项目说明文档

##全局配置
1.配置用户名： git config --global user.name '用户名'
2.配置用户邮箱  git config --global user.email '邮箱'
3.一台电脑配置一次就可以了
4.查看你的配置信息：git config --list

##初始化
1.git init  初始化版本库
2.当前目录路径后面有（master）代表初始化成功
3.在当前目录下会生成一个隐藏文件  .git 代表这是一个版本库
4.千万别操作 .git文件，让他隐藏不管他



##工作区内容提交到本地仓库
1.执行命令 git add 文件名   将工作区内容提交到暂存区
2.命令 git add . 将所有变动（新增 修改 删除 ）提交到暂存区
3.从暂存区提交到本地仓库  git commit -m '提交注释'



##辅助命令
1.命令git status 查看当前目录下操作状态
2.git log 查看日志
3.git reflog 查看简版日志
4.
