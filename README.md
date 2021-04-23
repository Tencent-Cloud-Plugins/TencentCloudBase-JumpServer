<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [JumpServer](https://github.com/jumpserver/jumpserver)

JumpServer 开源堡垒机部署广泛，遵循GNU GPL v2.0开源协议，是符合 4A 标准的专业运维安全审计系统。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-JumpServer&branch=master)
### 配置

- DB_HOST: 数据库地址
- DB_PORT: 数据库端口
- DB_USERNAME: 数据库用户
- DB_NAME: 数据库名
- DB_PASSWORD: 数据库密码


### 依赖

- CFS：需要使用 CFS 持久化配置数据
- CynosDB: 需要使用 CynosDB 做为数据库

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
2. JumpServer 默认使用 mysql 做存储数据库
