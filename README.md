zip4j 1.3.2.modified
================

解决解压时进度错误的bug

增加可一次性加入文件和文件夹的功能（这样压缩多文件可观察正确的进度）

使用GBK作为检测编码失败时的缺省值，以支持Windows下由其他软件压缩出的zip文件，实践证明兼容UTF-8。

自带的编码检测只能知道是不是UTF8。

若想更精确检测编码，可使用http://code.google.com/p/juniversalchardet/
