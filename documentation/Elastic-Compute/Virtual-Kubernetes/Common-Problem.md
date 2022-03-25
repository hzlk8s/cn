
# 常见问题


Q：什么是Kubernetes？

A：Kubernetes是一个开源的容器集群管理系统，可以实现大规模部署和管理容器化应用程序。

Q：Kubernetes集群在哪些区域可用？

A：目前已经在华北-北京、华南-广州、华东-上海上线，未来会在更多区域上线。

Q：Kubernetes集群支持哪些Kubernetes 版本？

A：目前支持Kubernetes 版本1.16，1.18，并且今后将支持更多Kubernetes版本。

Q：工作节点中预置的docker客户端版本？


A：docker-ce-17.06.2.ce-3.el7.centos.x86_64。

Q：Kubernetes集群是否可以使用v1版本的镜像？


A：不支持。

Q：Kubernetes集群中service定义与关联创建的应用负载均衡器的关系？


A：一个service关联创建一个应用负载均衡器；一个serice port对应一组负载均衡监听器和后端服务器；

Q：Kubernetes集群中service名称与service port名称命名规范？


A：service名称和service port名称最大不超过14字符，且规则符合应用负载均衡器[后端服务器](https://docs.jdcloud.com/cn/application-load-balancer/backend-management)及[监听器](https://docs.jdcloud.com/cn/application-load-balancer/listener-management)命名规范。名称长度超过14字符时，前14个字符被自动截取并被引用到对应的应用负载均衡器后端服务器和监听器中。命名符合k8s规范但与应用负载均衡命名规范不一致，将导致监听器或负载均衡器创建失败。

