# ==常用命令==

````javascript
git --version  //版本
git config --list  //配置信息
yum -y install git  //安装git   但不是最新版本
git init   //初始化一个仓库
git branch  //查看本地分支
git remote  //列出已经存在的远程分支
git remote add origin https://gitee.com/onlypluto/free.git    //连接远程仓库
git add 文件名 或者 .   //将项目中的某个文件或者全部文件添加到本地仓库
git rm 文件名   //从本地仓库删除一个文件
git commit -m''  //提交
git push origin master   //推送到远程仓库
````



# ==常规步骤==

````javascript
//在gitee上新建空仓库
//在本地新建空项目文件夹
//cd到根目录
git init //初始化一个本地仓库
git remote add origin 远程仓库地址   //连接远程仓库
git pull --rebase origin master   //拉取远程仓库到本地仓库，我的理解就是将两个仓库同步
//本地写代码
git add *
git commit -m  
git push origin master   //推送到远程仓库
````





