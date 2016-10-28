##### linux 常用命令

* df -hl 查看磁盘信息
#### 解压缩命令
* tar -zcvf 压缩后的文件(后缀名.tar.gz,.tar等) 被压缩文件 压缩
* tar -zxvf 被解压文件(后缀名.tar.gz,.tar等) 解压
 
#### 软连接
* ln -s sourcefile targetfile 软连接，类似win下快捷方式

#### ssh
* ssh-agent
* ssh-add
* ssh key的生成：ssh-keygen -t rsa
* 免密登录 

```
cd /root/.ssh
vi authorized_keys2
把类似ssh-rsa … local 这样的公钥(也就是利用ssh key 生成的key)加入到authorized_keys2的最后一行
```

* 远程登录 ：ssh root@jimscx.top -p xxxx
* 从远程拷贝 ：ssh rsync -avzP 当前目录 目的目录  

### nginx
* 启动 nginx `service nginx start`
* 重启 nginx `service nginx restart`
* 停止 nginx `service nginx stop`
