##### linux 常用命令
#### 解压缩命令
* tar -zcvf 压缩后的文件(后缀名.tar.gz,.tar等) 被压缩文件 压缩
* tar -zxvf 被解压文件(后缀名.tar.gz,.tar等) 解压
 
#### 软连接
* ln -s sourcefile targetfile 软连接，类似win下快捷方式

#### ssh
* ssh-agent
* ssh-add
* ssh key的生成：ssh-keygen -t rsa
* ssh root@jimscx.top -p xxxx
* ssh rsync -avzP 当前目录 目的目录  

### nginx
* 启动 nginx `service nginx start`
* 重启 nginx `service nginx restart`
* 停止 nginx `service nginx stop`
