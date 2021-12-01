# [[RCTF 2019]nextphp](https://buuoj.cn/challenges#[RCTF%202019]Nextphp)

## 解题步骤

1. 访问题目，页面上直接只显示一段`php`
```php
<?php
if (isset($_GET['a'])) { # isset() 函数用于检测变量是否已设置并且非 NULL
    eval($_GET['a']);  # eval() 函数把字符串按照 PHP 代码来计算。
} else {
    show_source(__FILE__); # 函数对文件进行语法高亮显
}
```
2. 
## 参考资料

- [[RCTF 2019]nextphp对应镜像](https://github.com/CTFTraining/rctf_2019_nextphp/tree/4e4879607a25122e3d4ebe905c8a70cd8a25db89)