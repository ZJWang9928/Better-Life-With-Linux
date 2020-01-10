# Git Commit Withdrawal

    撤销上一次提交  
    git reset --soft HEAD^
    撤销前n次提交  
    git reset --soft HEAD~n
    仅修改commit注释
    git commit --amend


### 参数：
+ --soft 不删除工作空间改动代码，撤销commit，不撤销git add . 
+ --hard 删除工作空间改动代码，撤销commit，撤销git add . 
+ --mixed 不删除工作空间改动代码，撤销commit，并且撤销git add . 操作，默认参数，与git reset --mixed HEAD^ 和 git reset HEAD^ 效果一样
