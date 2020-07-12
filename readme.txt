这里是git学习目录
第一节：
git init
git config <--global|--local> <--list> 
git add|rm
git commit <-a> <-m> <'注释'>
git log <--graph> <--oneline>
git diff <commit1>
git reflog 
git checkout -- <filename>

---------
连接远程仓库
git remote add <origin>/<master> <url>
git push
git pull
git clone <url>
------------
建立分支
git checkout <-b> <branchName>

git checkout -b <branchName> 
= git branch <branchName> 
+ git checkout <branchName>
= git switch -c <branchName>

