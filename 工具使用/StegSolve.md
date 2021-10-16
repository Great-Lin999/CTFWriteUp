# StegSolve

## 安装

###  java环境安装

1. 下载[java](https://www.oracle.com/java/technologies/downloads/)并进行解压
```bash
# 下载java17
wget https://download.oracle.com/java/17/latest/jdk-17_linux-x64_bin.tar.gz

# 移动压缩包至opt目录
mv jdk-17_linux-x64_bin.tar.gz /etc/opt
 
#切换至opt目录进行解压
cd /etc/opt
 
#解压
tar -zxvf jdk-17_linux-x64_bin.tar.gz
 
#拷贝解压后Java文件夹至/usr/bin
cp -r jdk-17/ /usr/bin
 
#安装并注册
update-alternatives --install /usr/bin/java java /etc/opt/jdk-17/bin/java 1
update-alternatives --install /usr/bin/javac javac /etc/opt/jdk-17/bin/javac 1
update-alternatives --set java /etc/opt/jdk-17/bin/java
update-alternatives --set javac /etc/opt/jdk-17/bin/javac
 
#检查是否成功配置Java环境
java -version

# java version "17" 2021-09-14 LTS
# Java(TM) SE Runtime Environment (build 17+35-LTS-2724)
# Java HotSpot(TM) 64-Bit Server VM (build 17+35-LTS-2724, mixed mode, sharing)

```

### StegSolve安装

1. 安装和使用`StegSolve`
```bash
wget http://www.caseum.com/handbook/Stegsolve.jar
java -jar Stegsolve.jar
```   

![](./img/StegSolveinstall.png)   

## 使用

## 实验问题

1. 
## 参考资料

- [在Kali Linux中下载工具Stegsolve](https://www.bbsmax.com/A/rV57X4QWdP/)
- [Kali中安装Java环境（保你一次性安装成功）](https://blog.csdn.net/userpass_word/article/details/103838606)