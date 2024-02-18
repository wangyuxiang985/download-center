# download-center
实现下载中心功能demo


### 功能
利用客户端和服务端实现下载中心的功能，需要下载/导出文件需求的系统集成客户端sdk，进行配置即可实现下载/导出任务的自动调度

### 项目依赖需依赖三方组件
oss: 存储第三方文件
nacos: 用作配置中心和注册用心

### 模块划分
download-center-sdk  下载中心客户端，第三方系统集成用

download-center-server 下载中心服务端，单独部署即可

### 系统部署要求
1. 集成注册中心nacos,实现spring-cloud调用