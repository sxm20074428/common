### 一、概述    
    io流大体分为BIO,AIO,NIO，常用的基本就是BIO，也就是之前文章所介绍的那些，接下来我们来大概了解一下NIO。
    
    传统io是靠字节或字符来传输，nio是靠块传输，也就是一个一个的buffer速度相对于较快。传统io是阻塞型io，nio是非阻塞型io。多适用于进行流畅的网络读写操作。

### 二、基本使用