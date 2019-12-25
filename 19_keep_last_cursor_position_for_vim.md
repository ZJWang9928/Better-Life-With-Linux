# Keep the Last Cursor Position for Vim

记录上次关闭某一文件时的光标位置，并在下一次打开该文件时将光标移动到该位置  
在.vimrc中添加
    
    au BufReadPost * if line("'\"") > 1 && line("'\"") <= line("$") | exe "normal! g'\"" | endif

保存即可
