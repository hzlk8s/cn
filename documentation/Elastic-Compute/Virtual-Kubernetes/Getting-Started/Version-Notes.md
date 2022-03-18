# 版本说明  
  
## Kubernetes 社区版本  
- Kubernetes 社区版本以x.y.z标识，其中x表示Major版本，y表示Minor版本，z表示Patch版本，版本说明如下：Major版本一般表示不具有兼容性的API变更；Minor版本表示功能变更，一般向后兼容；Patch版本表示向后兼容的Bug修复
- 京东云基于Kubernetes社区版本提供京东云的Kubernetes集群版本，版本以x.y.z-jcs.N标识 ，每一个Minor版本提供2-3个稳定的Patch版本，京东云将根据确定上线支持的Patch版本，但不保证Patch版本的连续性。-jcs.N后缀标识京东云基于某一Patch版本提供的特殊分支，包含安全更新、Bug修复或功能升级等，由京东云保证版本可用性。
  
## 京东云支持的Kubernetes版本  
  
### 1.18  
#### 版本说明:  
- 1.18社区版于2020年3月25日正式发布。京东云Kubernetes集群支持该版本
#### 社区版支持的新特性说明：  
- 聚焦安全性：基于角色的访问控制（RBAC）成为stable支持。RBAC允许集群管理员动态定义角色对于Kubernetes API的访问策略。通过网络策略筛选出站流量的Beta支持，增强了对入站流量进行过滤的现有支持。 RBAC和网络策略是强化Kubernetes内组织和监管安全要求的两个强大工具。Kubelet的传输层安全性（TLS）证书轮换成为beta版。自动证书轮换减轻了集群安全性运维的负担。  
- 聚焦工作负载支持：Kubernetes 1.8通过apps/v1beta2组和版本推动核心工作负载API的beta版本。Beta版本包含当前版本的Deployment、DaemonSet、ReplicaSet和StatefulSet。 工作负载API是将现有工作负载迁移到Kubernetes以及开发基于Kubernetes的云原生应用程序提供了基石。

### 1.16  
#### 版本说明:  
- 1.16社区版于2019年9月18日正式发布。京东云Kubernetes集群支持该版本
#### 社区版支持的新特性说明：  
