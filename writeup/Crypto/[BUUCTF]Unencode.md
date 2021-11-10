# [[BUUCTF]Unencode](https://buuoj.cn/challenges#Unencode)

## 解题过程

1. 压缩包解压出来是：`89FQA9WMD<V1A<V1S83DY.#<W3$Q,2TM]`，不属于常见的`base64`等常见编码和加密，因为有`#$]`等奇怪字符出现
2. 查了一下题目，这个就是一种编码方式，有在线的编解码[工具](http://web.chacuo.net/charsetuuencode)，就能直接解出`flag`