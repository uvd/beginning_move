# docker介绍
docker的方式可以解决一些遇到复杂环境没发解决的一种安装方式

## 安装docker 
要想用docker方式安装Move编译器也就是`sui` cli ，首先需要安装 docker 运行环境，如何安装docker环境可以参考 [docker](https://www.docker.com/get-started/) 

检查docker 是否安装成功
```shell
docker --version
```

## docker 方式安装


Pull Sui official docker image
```shell
docker pull mysten/sui-tools:devnet
```


Start and shell into the Docker container:

docker run --name suidevcontainer -itd mysten/sui-tools:devnet

docker exec -it suidevcontainer bash