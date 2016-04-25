Git is a distributed version control system.
Git is free software distributed under the GPL.
Git 是最好的免费分布式版本控制系统。
Git 命令：
	建立Git仓库	git init
	加入Git		git add xxx
	提交修改	git commit -m '修改的简述'
	查看Git状态	git status
	查看版本差异	git diff
	还原上一版本	git reset --hard HEAD^
	还原上二版本	git reset --hard HEAD^^
        还原上N个版本	git reset --hard HEAD~n
	查看提交日志	git log xxx
	以漂亮的列表查看 git log --pretty=oneline	
	还原到指定版本	git reset commit id (git log 前的数字)
	查看历史命令日志 git reflog (用来还原到未来的版本)
	撤销工作区修改	git checkout -- filename
	撤销暂存区修改	git reset HEAD fielname
	从版本库删除	git rm;	git commit -m 'remove xxx';
	撤销版本库删除	git checkout -- filename

