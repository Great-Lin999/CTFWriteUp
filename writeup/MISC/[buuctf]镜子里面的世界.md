# [[Buuctf]镜子里面的世界](https://buuoj.cn/challenges#%E9%95%9C%E5%AD%90%E9%87%8C%E9%9D%A2%E7%9A%84%E4%B8%96%E7%95%8C)

## 解题步骤

1. 解压压缩包后发现是一张图片，根据题目可以猜测是不是进行了隐写，有可能藏了一张图
2. 最简单的隐写算法就是`LSB`，对其进行提取
3. 比起在网上找`LSB`的加解密算法，很多关于`LSB`隐写的`writeup`里面都会提到[StegSolve](http://www.caesum.com/handbook/Stegsolve.jar)，可以使用这款工具直接进行数据提取、图片拼接。
> [StegSolve的基本安装和使用](https://github.com/linzqin/CTFWriteUp/blob/master/%E5%B7%A5%E5%85%B7%E4%BD%BF%E7%94%A8/StegSolve.md)

## 参考资料

- [github-用于lsb加密解密检测的工具](https://github.com/livz/cloacked-pixel)
- [ctf常用工具](https://github.com/zardus/ctf-tools)