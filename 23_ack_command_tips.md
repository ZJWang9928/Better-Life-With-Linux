# ACK Command Tips

ack是一个使用Perl语言开发的高效代码搜索工具  
默认会搜索当前目录下所有文件内容，只要包含关键字就输出  
    
### 文本搜索
    
    > ack keyword
    > ack -l keyword    # 只显示文件名
    > ack -i keyword    # 忽略大小写
    > ack -w keyword    # 强制要求PATTERN匹配整个单词

### 查找文件
可以代替find+grep的功能  
-f 选项表示打印所有将要被搜索的文件，事实上不会执行搜索，如果后面加 PATTERN ，那么就在路径中搜索文件名  
-g 选项表示搜索当前路径下的符合 PATTERN 的文件  
--python 选项可指定在Python文件中搜索  
