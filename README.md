# latex
a simple records for latex
比如插入了三个参考文献，显示的是[1,?,?]

这个和使用的模板有关，如果使用\bibliographystyle{IEEEtran}的模板的话，参考文献中间有空格是不会出错的，也就是说cite{ref1, ref2, ref3}不会报错。但是如果使用\bibliographystyle{splncs04}的话，cite{ref1, ref2, ref3}就回出现上述错误，添加参考文献的时候必须去掉多个参考文献中间的空格，也就是cite{ref1,ref2,ref3}就没有问题了，一个小错误，特此记录
--------------------- 
作者：binqiang2wang 
来源：CSDN 
原文：https://blog.csdn.net/m0_37052320/article/details/80346236 
版权声明：本文为博主原创文章，转载请附上博文链接！
