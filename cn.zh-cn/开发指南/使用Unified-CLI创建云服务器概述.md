# 使用Unified CLI创建云服务器概述<a name="ZH-CN_TOPIC_0070863629"></a>

Unified CLI不支持通过磁盘创建云服务器，要采用通过镜像创建云服务器的方式。

## 创建流程<a name="section16493259"></a>

1.  使用openstack port create命令创建Port。
2.  使用openstack server create命令创建云服务器。

## 约束和限制<a name="section389497111506"></a>

1.  在创建云服务器之前，需要先申请port，并且需要创建一个主网卡资源（并且只能有一个），以便进行云服务器发放。
2.  创建云服务器时，请不要删除对应的镜像（Image）、网络（Network）、子网（subnet）、安全组（security\_group）等信息。
3.  不支持批量创建云服务器。
4.  如未按以上原则创建云服务器，造成云服务器创建失败以及云服务器不可用，需要删除云服务器后重新按照上述流程创建。

