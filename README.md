# 環境說明:

啟用服務

Nginx
MySQL
Redis
Fluentd

### 添加 hosts
``` shell
sudo vim /etc/hosts
```
將以下紀錄加入：
127.0.0.1 go.mvc.local

### 啟動
``` shell
docker-compose up -d
```
