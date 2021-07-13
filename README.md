# Git
Git使用方法以及相关命令
1、通过使用一下命令添加邮箱以及用户名
   git config --global user.email "****@**.com"
   git config --global user.name "***"
  
2、git status （查看当前文件的状态）

3、git add 文件名 （将文件添加到暂存区）

4、git commit -m '文件描述' （将文件提交到git本地仓库）

5、当需要将修改后的文件提交至Git本地仓库，重复上述过程

6、删除文件
	• 首先删除本地文件
	• 从git中删除文件  git rm 文件名
	• git commit -m ‘描述’ 
	
7、将远程仓库代码下载到本地仓库
   git clone 仓库地址
	
8、将本地仓库同步至远程仓库
   git push


