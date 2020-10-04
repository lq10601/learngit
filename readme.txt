git 123abcd
a bb
git add 
git commit
git diff 查看文件修改后(add前)的不同
git status
git log 提交日志
git reset --hard HEAD^ 回到上次提交,HEAD~10回到网上数10次提交,指定id提交
git reflog 查看命令历史及提交id
stage 暂存区
git diff查看工作区和暂存区差异，
git diff --cached查看暂存区和仓库差异，
git diff HEAD 查看工作区和仓库的差异，
git add的反向命令git checkout -- file，撤销工作区修改，即把暂存区最新版本转移到工作区，
如果不add就不能把修改的内容提交,commit提交的是(add后)暂存区里的
git reset HEAD <file>可以把暂存区的修改撤销掉,就是撤销add操作