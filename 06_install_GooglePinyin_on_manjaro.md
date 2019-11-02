# Install GooglePinyin on Manjaro

先安装相关软件  

	sudo pacman -S wqy-microhei

然后在用户根目录编辑.xprofile文件（没有就新建一个）

	vim ~/.xprofile

若是刚装好的Manjaro上使用vim需要安装一下，pacman即可  
内容写：

	export LC_ALL=zh_CN.UTF-8
	export GTK_IM_MODULE=fcitx
	export QT_IM_MODULE=fcitx
	export XMODIFIERS="@im=fcitx"

保存，重启（或注销再登录），在输入法里面选择 Configure Current Input Method 即可配置快捷键  
