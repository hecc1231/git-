# git 连接远程库
在github建立仓库，得到类似链接如下:
https://github.com/hecc1231/python-notebook.git

#在本机上进行仓库创建(如果之前没有设置过用户名和邮箱需要利用 git config --global user.name 'hecc1231')
1. mkdir newRepos
2. git init(创建git文件)
3. 若没有文件需要创建一个如 vim readMe.md
4. git add reamMe.md
5. git commit -m 'first commit'
6. git remote add origin  https://github.com/hecc1231/python-notebook.git(创建本地仓库和远程仓库的连接)
7. git push -u origin master (将本地master的文件全部上传到origin云端仓库)
8. 后续上传就可以简单用git push origin master

# 回滚版本
git reset --hard commit_id(commit_id 可以利用git log 命令查看)
