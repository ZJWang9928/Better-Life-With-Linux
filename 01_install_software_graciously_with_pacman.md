# Install Software Graciously with Pacman

## Reason to use pacman
+ Arch下简洁高效的包管理命令
+ 享受AUR(Arch User Repository)，软件库相当庞大，无需像Debian系一样手动添加ppa源等

## Commonly Used Commands
1. 安装软件

> sudo pacman -S 软件名   

2. 获取最新软件情况，但是可能不会实际执行

> sudo pacman -Sy   

3. 强制更新软件库

> sudo pacman -Syy   

4. 更新软件

> sudo pacman -Su   
> sudo pacman -Syu   

5. 搜索软件(支持正则表达式)

> sudo pacman -Ss 软件名   

6. 删除软件(并不是很好的删除命令)

> sudo pacman -R 软件名    

7. 删除软件及依赖

> sudo pacman -Rs 软件名   

8. 删除软件、依赖及全局配置文件(最佳方式)

> sudo pacman -Rns 软件名   

9. 显示本地所有软件

> sudo pacman -Q   

10. 查看本地一共有多少个软件

> sudo pacman -Q | wc -l    

11. 查看自己安装的软件

> sudo pacman -Qe    

12. 查看自己安装的软件且不显示版本号

> sudo pacman -Qeq    

13. 查询本地安装的软件

> sudo pacman -Qs 软件名    

14. 查询不再被需要的孤儿(Orphans)软件

> sudo pacman -Qdt    

15. 查询不再被需要的孤儿(Orphans)软件且不显示版本号

> sudo pacman -Qdtq    

16. 删除不再被需要的孤儿(Orphans)软件

> sudo pacman -R $(pacman -Qdtq)    
