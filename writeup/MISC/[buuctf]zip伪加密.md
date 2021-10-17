# [[buuctf]zip伪加密](https://buuoj.cn/challenges#zip%E4%BC%AA%E5%8A%A0%E5%AF%86)

## 解题步骤

1. 下载下来的`zip`包打开提示需要解压密码。但是题目提示的是`伪加密`，所以应该不是使用暴力破解的方法
2. 使用`010Editor`打开文件
3. 对两个加密点的数据都尝试修改一下，改为偶数后将文件保存   

![](./img/zipchange.png)         

4. 修改后的压缩包可以直接解压，打开后即可得到`flag`   

![](./img/zip伪加密flag.png)    
