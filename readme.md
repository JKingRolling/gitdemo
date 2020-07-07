git init 将当前的仓库初始化为git仓库

git add ./1.txt 将文件从工作区添加到缓冲区

git commit -m “注释” 将文件从缓冲区提交到归档区

git add origin https://github.com/JKingRolling/gitdemo.git 添加一个远端仓库

git push -u origin master将归档区的内容提交到远端仓库上来

git add -A  提交所有变化

git add -u  提交被修改(modified)和被删除(deleted)文件，不包括新文件(new)

git add .  提交新文件(new)和被修改(modified)文件，不包括被删除(deleted)文件

工作区 缓冲区 归档区 远端仓库

Git是一个开源的分布式版本控制系统

