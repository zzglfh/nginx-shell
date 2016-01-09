# nginx-shell
简单的nginx配置命令，方便配置反向代理等  
初学 shell 编程，后期再改成命令格式吧，先凑合用。  

有兴趣的给指导下，万分感谢

#添加一个反向代理
例如，添加反向代理 test.zzg.me  到 127.0.0.1:8080/test   （根据域名跳转）  
```
./forward_add test.zzg.me http://127.0.0.1:8080/test  
```

#添加一个前端项目(html,php之类的，目录)  
例如，添加反向代理 test.zzg.me  到 /var/www/test   （根据域名跳转）  

```
./path_add test.zzg.me /var/www/test  
```
