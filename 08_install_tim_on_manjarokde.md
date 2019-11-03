# Install QQ or Tim on Manjaro KDE

1. 配置好添加镜像源（开箱后的常规三步走即可）
2. 安装QQ或TIM，pacman一下即可
			
		
	sudo pacman -S deepin.com.qq.office
	sudo pacman -S deepin.com.qq.im


3. 尝试一下是否可以打开（如果启动菜单没有，可以在/opt/deepinwine/apps/目录下找到），如果打不开，请参考后续步骤
4. 安装gnome-settings-daemon
		
		
	sudo pacman -S gnome-settings-daemon
		
		
5. 设置/usr/lib/gsd-xsettings为自启动
		
		
	系统设置->开机或关机->自动启动->添加脚本->输入/usr/lib/gsd-xsettings
		
		
6. 重启一下即可，不出意外就能顺利打开QQ/TIM了
