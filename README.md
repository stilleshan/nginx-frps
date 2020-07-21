# nginx-frps
## 简介
适用于服务器部署了 frps 并占用了 80/443 端口,配置 docker 版 frpc 和 nginx 进行端口转发提供 Web 服务.  

- clone 到本地
- 修改 frpc/frpc.ini 配置
- 上传证书文件到 nginx/ssl 目录下
- docker compose 启动