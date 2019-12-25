# Vimscript Notes

+ :echo命令输出的信息在脚本运行完毕后就会消失，:echom打印的信息会保存下来，可以执行:messages命令再次查看
+ :set <name>/:set no<name>或直接:set <name>! 可切换布尔选项的值
+ :set <name>?命令可获取一个布尔选项的当前值 
+ 可在一个:set命令中设置多个选项的值 
+ 键盘映射命令:map后无法使用注释
+ 可用nmap、vamp、imap分别指定三种模式下的映射
+ map系列命令存在**递归危险**
+ map系列命令对应的非递归映射：noremap、nnoremap、vnoremap、inoremap
