1.cd 路径 进入到本地目录
2.配置git
3.git init 在本地进行初始化
4.工作区提交的缓冲区
	git add 文件名 
	git add * 提交所有文件
	git commit -m "提交的信息"
5.查看工作区的状态
	git status

6.从暂存区恢复文件到工作区
	git checkout 文件名
7.查看工作区和暂存区版本的区别
	git diff
8.clear 清屏操作
9.查看已提交到缓存区的历史版本
	git log
10.恢复文件到指定的某一版本
	git reset --hard 版本号
11.生成ssh密钥
	ssh-keygen -t rsa -C "你的github邮箱"
C:\Users\admin\.ssh\id_rsa.pub
12.去GitHub配置密钥
13.暂存区推送到远程仓库
	git remote add origin https://github.com/haiyang1024/testgit.git
	git push -u origin master
14.git clone
	从远程仓库更新到本地
15.从远程仓库同步本地代码



一号程序员第一次提交
二号程序员第一次提交