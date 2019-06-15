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
