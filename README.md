
## 目录
- [目录](#目录)
  - [简述](#简述)
  - [重要配置文件](#重要配置文件)
  - [部署](#部署)
  - [参考](#参考)
  

### 简述

该demo主要展示如何使用SAP BTP CF - Nginx_buildpacks 来部署我们的的应用

### 重要配置文件

**buildpack.yml**

主要用来配置nginx的允许版本

**nginx.conf**

配置nginx的常用配置， 如反向代理， IP限制， 路由配置等

**manifest.yml**

配置用于部署使用的常用指标， 如内存， 硬盘， 路由URL等

**public**

用于存储通过npm 或者yarn类似的打包工具打包出来的静态资源文件


### 部署


部署命令行为  

```

cf api <apiEndpoint>
cf push 

```

### 参考

[cloud_foundry_nginx_buildpacks](https://docs.cloudfoundry.org/buildpacks/nginx/index.html)
[nginx](https://nginx.org/en/)




