# Terminals Database Inaccessible Problem When Clear
   
问题：  
当使用clear命令时出现如下报错  
   
        ~$ clear   
        terminals database is inaccessible   

临时解决方法：
    
    ~$ export TERMINFO=/usr/share/terminfo   
    
最好将上面这条 export 命令添加到 .bashrc 中。
