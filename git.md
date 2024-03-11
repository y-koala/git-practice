#操作
先pull（解决冲突）再push
git status //查看当前分支工作状态
git add . //将本地修改的文件放入暂存区
git commit -m '' //提交文件并说明提交内容
git pull origin 远程分支名字：本地分支名字 //从远程分支拉取文件到本地仓库
git push origin 本地分支名字：远程分支名字//将本地仓库分支的内容提交到远程分支

git log //查看提交记录及内容

git branch 分支名//创建新的分支
git checkout 分支名//切换到心的分支

创建完新的分支，在修改文件后并执行git add和git commit后，新的分支才算是真正的建立好

git merge 分支名字 //首先将分支切换到master，然后执行git merge dev，这样才能将dev分支的内容合并到master分支；



