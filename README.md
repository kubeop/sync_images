# Sync Image

使用Github Action将所需镜像转存至阿里云镜像仓库

- 支持docker.io、registry.k8s.io、quay.io、ghcr.io等仓库
- 支持多对多镜像仓库同步
- 同步过程只经过内存和网络，不依赖磁盘存储，同步速度快
- 自动增量同步, 自动忽略已同步且不需要修改的镜像
- 支持镜像层级别的并发同步
- 简单轻量，不依赖 docker 以及其他程序