# study-k8s
study-k8s, k8s study project
k8s学习项目：

## 视频地址：https://www.bilibili.com/video/BV17THverEiq

## 01-课程内容
![img.png](src/main/resources/images/01-img.png)

# 02-k8s介绍和特性
- 更方便的去部署容、扩展、回滚器化的服务(可视化的去操作docker)
- 做到很多功能，回滚、热部署、水平扩展、自我修复等
![img.png](src/main/resources/images/02-img.png)

## 03-k8s的集群架构组件
![img.png](img.png)
- master,主控节点
API server，master内部组件负责调度node，工作节点
![img_1.png](img_1.png)

- node,工作节点
![img_2.png](img_2.png)

## 04-k8s核心概念
### pod
![img_3.png](img_3.png)
### controller
- 确保pod预期的pod数量
- 无状态部署
- 有状态部署，需要有特定条件，存储、网络等
- 确保所有node执行同一个pod
- 一次性任务和定时任务

## 05-搭建k8s集群
可以搭建多master或单master节点
![img_4.png](img_4.png)
![img_5.png](img_5.png)

### 配置要求
![img_6.png](img_6.png)

### 搭建方式
kubeadm、二进制包

## 06-虚拟机安装操作系统和初始化
