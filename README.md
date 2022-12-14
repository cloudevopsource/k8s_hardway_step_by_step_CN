<img alt="kubeasz-logo"  src="pics/ukraine.jpg">

##                   声援乌克兰，反对战争，守护世界和平! 

***<u>战争没有赢家，受伤的永远是平民！俄罗斯的侵略旨在摧毁一个作为主权独立国家的乌克兰，将导致可怕的人道主义灾难！</u>***

***<u>There is no winner in the war, and civilians are always injured! Russia's aggression aims at destroying Ukraine as a sovereign and independent country, which will lead to a terrible humanitarian disaster!</u>***

## Kubernetes The Hard Way(中文版)
<img alt="kubeasz-logo" width="220" height="230" src="pics/k8shardway.jpg">

​     本教程将引导您以Kubernetes The Hard Way(困难模式)以二进制方式部署设置 Kubernetes。本指南不适用于寻求全自动命令来启动 Kubernetes 集群的人。本教程针对学习进行了优化，这意味着要确保您了解引导 Kubernetes 集群所需的每项任务; 同时注重通过对kubernetes原理及工作 流阐述，努力成为`kubernetes`基于生产环境的最佳实践。

- **集群特性** `TLS`双向认证、`RBAC`授权、[Master高可用](docs/setup/00-planning_and_overall_intro.md#ha-architecture)、支持`Network Policy`
- **集群版本** kubernetes v1.24.x
- **操作系统** CentOS/RedHat/Rocky Linux 8,
- **运行时** [containerd](docs/setup/03-container_runtime.md) 
- **网络** [calico](docs/setup/network-plugin/calico.md)



## kubernetes安装指南(00序号开头)

<table border="0">
    <tr>
        <td><a href="docs/setup/00-planning_and_overall_intro.md">00.k8s部署整体规划准备</a></td>
        <td><a href="docs/setup/02-install_etcd.md">01.操作系统初始化配置</a></td>
        <td><a href="docs/setup/04-install_kube_master.md">02.内核参数优化</a></td>
        <td><a href="docs/setup/06-install_network_plugin.md">03.分发脚本及配置工具准备</a></td>
    </tr>
    <tr>
        <td><a href="docs/setup/01-CA_and_prerequisite.md">04.为TLS双向认证准备证书</a></td>
        <td><a href="docs/setup/03-container_runtime.md">05.为身份认证准备配置文件</a></td>
        <td><a href="docs/setup/05-install_kube_node.md">06.安装配置nginx实现HA</a></td>
        <td><a href="docs/setup/07-install_cluster_addon.md">07.安装配置etcd集群</a></td>
    </tr>
    <tr>
        <td><a href="docs/setup/01-CA_and_prerequisite.md">08.分发k8s软件包</a></td>
        <td><a href="docs/setup/03-container_runtime.md">09.安装配置containerd</a></td>
        <td><a href="docs/setup/05-install_kube_node.md">10.安装配置kube-apiserver集群</a></td>
        <td><a href="docs/setup/07-install_cluster_addon.md">11.安装配置kube-controller-manager集群</a></td>
    </tr>    
    <tr>
        <td><a href="docs/setup/01-CA_and_prerequisite.md">12.安装配置kube-scheduler集群</a></td>
        <td><a href="docs/setup/03-container_runtime.md">13.安装配置kubelet</a></td>
        <td><a href="docs/setup/05-install_kube_node.md">14.安装配置kube-proxy</a></td>
        <td><a href="docs/setup/07-install_cluster_addon.md">15.安装配置calico</a></td>
    </tr>  
    <tr>
        <td><a href="docs/setup/01-CA_and_prerequisite.md">16.安装配置coredns</a></td>
        <td><a href="docs/setup/03-container_runtime.md">17.验证集群功能.md</a></td>
        <td><a href="docs/setup/05-install_kube_node.md"></a></td>
        <td><a href="docs/setup/07-install_cluster_addon.md"></a></td>
    </tr>  
</table>


## kubernetes生态安装指南(000序号开头)

<table border="0">
    <tr>
        <td><a href="docs/setup/00-planning_and_overall_intro.md">001.安装配置helm</a></td>
        <td><a href="docs/setup/02-install_etcd.md">002.安装配置ingress-nginx.md</a></td>
        <td><a href="docs/setup/04-install_kube_master.md">003.安装longhorn分布式存储</a></td>
        <td><a href="docs/setup/06-install_network_plugin.md">004.安装配置PLG日志架构</a></td>
    </tr>
</table>

## kubernetes配置管理指南(序号0000开头)

<table border="0">
    <tr>
        <td><a href="docs/setup/00-planning_and_overall_intro.md">0001.kubectl常用命令汇总</a></td>
        <td><a href="docs/setup/02-install_etcd.md">0002.容器操作及构建工具集</a></td>
        <td><a href="docs/setup/04-install_kube_master.md">0003.手动拉取国外镜像</a></td>
        <td><a href="docs/setup/06-install_network_plugin.md">0004.containerd配置私有仓库</a></td>
    </tr>
    <tr>
        <td><a href="docs/setup/01-CA_and_prerequisite.md">0005.新增worker节点手动加入k8s集群</a></td>
        <td><a href="docs/setup/03-container_runtime.md">0006.基于calico配置NetworkPolicy</a></td>
        <td><a href="docs/setup/05-install_kube_node.md">0007.基于velero集群备份恢复</a></td>
        <td><a href="docs/setup/07-install_cluster_addon.md">0008.升级k8s集群</a></td>
    </tr>
</table>


- 

## 沟通交流

- 微信：solaris10

- 邮件: orasun@vip.qq.com

- 捐赠：如果觉得本项目对您有帮助，请小小鼓励下项目作者，谢谢！

     ​      支付宝码(左)            微信钱包码(右)

  <img src="pics/alipay.jpg" alt="支付宝" width="150" height="150" /> `<img src="pics/wxpay.jpg" alt="微信钱包" width="145" height="145" />

## 贡献&致谢

请阅读[项目分支说明](docs/mixes/branch.md), 欢迎提[Issues](https://github.com/easzlab/kubeasz/issues)和[PRs](docs/mixes/HowToContribute.md)参与维护项目！感谢您的关注与支持！

参考资料

- [kubernetes-the-hard-way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
- [opsnull 安装教程](https://github.com/opsnull/follow-me-install-kubernetes-cluster)



Copyright 2021 orasun (orasun@vip.qq.com) Apache License 2.0, 详情见 [LICENSE](docs/mixes/LICENSE) 文件。
