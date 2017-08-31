# docker-alpine-postgres

### 构建
`docker build -t pgsql .`
### 使用
`docker run --name pg -e POSTGRES_PASSWORD=postgres -d -p 5555:5432 pgsql`  
上面的命令映射到主机的`5555`端口, 用户名和密码都是`postgres`

### 参考
- https://github.com/docker-library/docs/tree/master/postgre
- http://iliwei.me/2016/12/13/alpine-time-zone/
