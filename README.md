Interactsh内网版，基于Interactsh 1.0.2版本
 通过IP地址的方式接受http请求和ldap请求，不需要用到域名
 
 
 使用方式：
 ./interactsh-server -ip 192.168.85.1
![image](https://user-images.githubusercontent.com/52018740/167871274-e35cb9fc-290d-46a5-9a26-8a3a784a55ea.png)

 ./interactsh-client -s 192.168.85.1
 ![image](https://user-images.githubusercontent.com/52018740/167871158-f50c65df-caba-40d0-ad58-afe83f16543f.png)
 
 当目标访问client生成的url时,client可以收到请求信息：
 ![image](https://user-images.githubusercontent.com/52018740/167872141-83013a6e-64b1-44f7-8f47-56eaafc7dadf.png)

