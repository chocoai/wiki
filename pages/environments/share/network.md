共享网络
==========

宽带
------

A 百兆电信 研发
B 百兆电信 赵良
C 百兆电信 赵良
D 八兆电信 客服专用 固定IP地址

路由器
------

企业级路由器  机柜  IP:172.16.234.3, 帐号:(机密)，密码:(机密)
两个交换机    机柜  
VPN路由器     机柜  IP:172.16.234.1 物业集团配置


网络拓扑图
------

办公研发局域网络配置清单
------

###公司路由

| 路由  | 名称  |ip   | 服务电话  |
| ------------ | ------------ | ------------ | ------------ |
| 路由器1 (主出口)  | VPN路由器(鑫塔XT6000)  | 172.16.234.1  | 4008-252-696  |
| 路由器2  | 无线路由器(TP-Link WVR1750L)  | 172.16.234.253  |  ---------- |


###公司WiFi名称

| 名称  | 账号  |  密码 |
| ------------ | ------------ | ------------ |
| wifi  |  GIGAHOME / GIGAHOME_5G |  @xiaoquguanjia@1806 |


###ip功能和负责人

| ip  | 功能或负责人  |
| ------------ | ------------ |
| 172.16.234.1   - 172.16.234.100  | 服务器  |
|172.16.234.11  - 172.16.234.15   | 赵良  |
| 172.16.234.16  - 172.16.234.20  | 何猛  |
| 172.16.234.21  - 172.16.234.100  | 其它服务器  |
| 172.16.234.17  | api文档服务、SVN服务  |
| 172.16.234.101 - 172.16.234.120  |  DSL+VPN(客服专用) |
| 172.16.234.121 - 172.16.234.140  | VPN+上网(行政，财务，产品)  |
|  172.16.234.141 - 172.16.234.250 | 研发  |

###域名与ip对照及负责人

| 域名  |ip   | 负责人  |
| ------------ | ------------ | ------------ |
|共享文件服务器   | 172.16.234.21  |陈展雄   |
|app.gigahome.cc   |  172.16.234.4 | 赵良/陈展雄  |
| git.gigahome.cc  | 172.16.234.3  | 赵良/陈展雄  |
| wiki.gigahome.cc  |  172.16.234.4  | 赵良/陈展雄  |
|  zentao.gigahome.cc |  172.16.234.4 | 赵良/陈展雄  |
| sea.gigahome.cc  | 172.16.234.4  | 赵良  |
| git.xiaotu.com  | 172.16.234.11  | 赵良  |
| eip.kaisagroup.com  | 192.168.1.82  | 刘进辉/马武雄  |
| sso.kaisagroup.com  |  192.168.1.143 | 刘进辉/马武雄  |
| mail.kaisagroup.com  |  192.168.1.148 | 刘进辉/马武雄  |
| APIDOC服务器(172.16.234.17:8088/showdoc)  |  172.16.234.17 | 胡文俊  |