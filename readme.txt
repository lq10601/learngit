git init 创建版本库
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
删除文件后,如果确实要从版本库中删除该文件，那就用命令git rm删掉，并且git commit
如果删除文件,删错了,可以用git checkout -- test.txt恢复
git checkout其实是用版本库里的版本替换工作区的版本，无论工作区是修改还是删除，都可以“一键还原”。
ssh-keygen -t rsa -C "youremail@example.com" 创建key到用户目录
git remote add origin https://github.com/lq10601/learngit.git 本地仓库与远程仓库关联
git push -u origin master 把分支master推送到远程,-u与远程master分支关联
远程库的名字就是origin
查看分支：git branch
创建分支：git branch <name>
切换分支：git checkout <name>或者git switch <name>
创建+切换分支：git checkout -b <name>或者git switch -c <name>
合并某分支到当前分支：git merge <name>
删除分支：git branch -d <name>