# cas-server
cas-server based on sprint boot (cas version 5.3.16)

## 说明
main方法启动，非overlay模式，无需外置tomcat 

默认用户名密码：`casuser::Mellon`

该demo中默认关闭了ssl，如需开启，可调整如下`application.properties`里配置
```
#server.ssl.key-store=file:/etc/cas/thekeystore
#server.ssl.key-store-password=changeit
#server.ssl.key-password=changeit
```