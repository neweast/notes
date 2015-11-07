## Unicode 早期历史 
### unicode的命名，源于三个主要目标
1. universal 通用性（能够编码世界上的所有语言）
2. uniform 一致性（为了提高访问效率，采用固定宽度编码）
3. unique 唯一性（bit流到字符流只有唯一解释）

### 时间点
1987年立项 - 1988年初完成了三个主要的调查 - 1988年秋天，开始建立unicode字符的数据库 - 1991年发布了unicode 1.0 卷1

### 问题
1. 文本大小的增长是否能够被美国和西欧的用户所接受。
    
    文本大小方面，他们测试了日常使用中，字符数据占用内存或者磁盘空间的百分比，最终得出来的结论是比较小。
2. 是否能够将中文、日文、韩文统一起来。

    RLG的东亚字符书目代码EACC，表明一致性是没有问题的。
3. 16bit是否能够表示所有的现代字符。

    统计了日常使用的现代字符，得出的结论是16 bit完全能够包含所有的字符。
    
更进一步，论证了不论如何编码，混合字节字符集访问起来，相比于unicode更加低效。（这里是指相比于unicode的fix-length 16 bit而言）

(http://programmers.stackexchange.com/questions/120126/what-is-the-history-of-why-bytes-are-eight-bits)[http://programmers.stackexchange.com/questions/120126/what-is-the-history-of-why-bytes-are-eight-bits]