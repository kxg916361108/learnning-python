# learnning-python
basis
Python注意细节：
1、字符串前面加'r'代表后面的字符串按照原样输入，转义字符等字符不起作用。
2、在用os.listdir操作文件目录时，涉及到整合文件目录有两种方法，os.path.join 和os.path.normpath，使用时最好使用后者，能够根据操作系统的不同自动匹配系统层级目录中才有'/'或是'\'对文件目录进行分隔。
