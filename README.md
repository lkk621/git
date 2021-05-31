# git
撤销此次add，且未commit[常用]
git reset HEAD
git reset HEAD filename // 撤销某个文件

撤销此次commit ，保留add[常用]
git reset --soft HEAD~

撤销此次commit 和 add【常用】（不删除工作空间改动代码）
git reset HEAD~
or
git reset --mixed HEAD~

撤销commit 和 add【慎用】（删除工作空间改动代码），代码会回滚到最新的一次git pull的代码
git reset --hard HEAD~
