## 2021/09/29 add
	git init
	git add @filename
	git commit -m "comment"

	git status
	git diff

	git log
	git log --pretty=oneline

	git reset --hard HEAD^  回退版本
	git reset --hard 65e8   回退版本
	git reflog

	git add -> stage; git commit -> master/branch
	第一次修改 -> git add -> 第二次修改 -> git add -> git commit

	git checkout -- readme.txt
	命令git checkout -- readme.txt意思就是，把readme.txt文件在工作区的修改全部撤销

	git reset HEAD readme.tx
	git reset命令既可以回退版本，也可以把暂存区的修改回退到工作区。

	git rm -- test.txt

## 2021/09/30 add
	git remote add origin git@github.com:rwdong2021/gcbaas.git
	git branch -M main
	git push -u origin main

	git remote -v
	git remote rm origin
