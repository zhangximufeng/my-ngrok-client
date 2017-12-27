#启动步骤
```bash
# 建立ngrok配置文件：ngrok.cfg
server_addr: “ngrok.xxxx.com:4443"
trust_host_root_certs: false

#运行客户端，暴露本地4000端口站点：
ngrok -subdomain=demo -config=./config.cfg 4000

```
