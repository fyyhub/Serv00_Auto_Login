# Serv00 - 控制面板自动登录、ssh自动连接脚本

> 基于 [Serv00_Auto_Login](https://github.com/bg8ixz/Serv00_Auto_Login) 修改的项目，增加了bark推送和ssh自动连接脚本

## 使用方法
　　在 GitHub 仓库中，进入右上角`Settings`，在侧边栏找到`Secrets and variables`，点击展开选择`Actions`，点击`New repository secret`，然后创建一个名为`ACCOUNTS_JSON`的`Secret`，将 JSON 格式的账号密码字符串作为它的值。在bark中填入bark软件的推送apiKey，可留空。在host填入ssh的连接地址。如下格式：  
```
[  
  { "username": "fyy5210", "password": "", "panelnum": "6", "bark": "apikey", "host": "s6.serv00.com" },  
  { "username": "566521a", "password": "", "panelnum": "8", "bark": "apikey", "host": "s8.serv00.com" },  
  { "username": "1637045610a", "password": "", "panelnum": "8", "bark": "apikey", "host": "s8.serv00.com" },  
  { "username": "178621833abc", "password": "", "panelnum": "10", "bark": "apikey", "host": "s10.serv00.com" }
]
```
> 其中`panelnum`参数为面板编号，即为你所收到注册邮件的`panel*.serv00.com`中的`*`数值。

## 贡献
|姓名|主页|内容|
| :------------: | :------------: | :------------: |
|linzjian666|https://github.com/linzjian666|增加多面板支持|

## 参考信息
|  名称 |来源|地址|
| :------------: | :------------: | :------------: |
|Limkon|Github|https://github.com/Limkon|
