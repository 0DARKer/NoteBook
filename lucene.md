lucene

# 1. jdk环境,eclipse和lucene安装.

[lucene3.6.2](http://archive.apache.org/dist/lucene/java/3.6.2/)
下载.tgz(Windows下载.zip)解压出来四个.jar文件为库文件,
[yiibai/lucene
](https://www.yiibai.com/lucene/lucene_first_application.html)根据以上网址跟着做帮助配置eclipse开发环境.跟着复制粘贴即可.

完成后我的eclipse有出错提示,暂时没找到解决办法:ERROR: index path not specified

我选择用命令行来对程序进行编译:
命令行编译java项目
`javac -cp /path/*.jar -d /compile/path/ project1.java ...`
-cp后面接的是引用的.jar包的路径/path/lucene-core-3.6.2.jar ;
-d后面接的是编译目标程序(.class)文件的存放地址;
最后接各种.java源程序文件.

运行程序需要在/compile/path 运行
`java com.yiibai.lucene.LuceneTester`
其中com.yiibai.lucene对应编译后对应文件夹`./com/yiibai/lucene/`    LuceneTester为.class 编译文件．

# 2. lucene基本知识.

## indexing process

## 包介绍

1. Package:org.apache.lucene.document
2. Package:org.apache.analysis
3. Package:org.apache.lucene.index
4. Package:org.apache.lucene.search

## 应用实例
