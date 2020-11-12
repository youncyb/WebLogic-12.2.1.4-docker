## 1. 初始化

1.  运行`build.sh`会生成weblogic12.2.1.4的镜像

2. 运行`run.sh`会启动镜像，并开启7001的http端口和8453的调试端口

## 2. 之后使用容器

**启动容器**： `docker start flamboyant_kare`

**停止容器**： `docker stop flamboyant_kare`

## 3. properties目录是挂载到域的domain.properties

