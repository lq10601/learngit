git 123abcd
a bb
git add 
git commit
commit提交的是(add后)暂存区里的
git diff 查看文件修改后(add前)的不同
git status
git log 提交日志
git reset --hard HEAD^ 回到上次提交,HEAD~10回到网上数10次提交,指定id提交
git reflog 查看命令历史及提交id
stage 暂存区
git diff查看工作区和暂存区差异，
git diff --cached查看暂存区和仓库差异，
git diff HEAD 查看工作区和仓库的差异，
git checkout -- file，让这个文件回到最近一次git commit或git add时的状态
git reset HEAD <file>可以把暂存区的修改撤销掉,就是撤销add操作