1.-----------------------------------------------------------------
tar cjf - electron-ssr-0.2.6.deb |split -b 1m - logs.tar.bz2.

完成后会产生下列文件：

logs.tar.bz2.aa, logs.tar.bz2.ab, logs.tar.bz2.ac

要解压的时候只要执行下面的命令就可以了：

cat logs.tar.bz2.a* | tar xj

可以得到分卷压缩的文件


2.-----------------------------------------------------------------
chrome访问助手：http://www.ggfwzs.com/
