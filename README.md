# docker for gh-oauth-server
+ 拉取镜像

```shell
docker pull registry.cn-hangzhou.aliyuncs.com/lefer/gh-oauth-server:1.0.0
```

+ 运行容器

```shell
docker run  \
--name oauth \
-d -p 3000:3000 \
registry.cn-hangzhou.aliyuncs.com/lefer/gh-oauth-server:1.0.0
```