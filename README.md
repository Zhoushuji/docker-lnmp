# docker-lnmp
用Docker构建更高可控性的LNMP运行环境

### 使用方法：

`$ git clone https://github.com/getnas/docker-lnmp.git .`

`$ mkdir www mariadb mariadb/datadir`

`$ docker-compose up -d`

浏览器访问 http://ip-address:808

可以根据需求修改 docker-compose.yml 配置文件，比如调整端口映射（默认为 808:80）。
