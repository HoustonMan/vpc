# 申请虚拟IP地址<a name="vpc_vip_0002"></a>

## 操作场景<a name="se6c62cd61b874228a8bde0cc58d45fae"></a>

当弹性云服务器需要设置虚拟IP地址或预留指定的虚拟IP地址时，可以通过给子网申请虚拟IP地址的方式分配虚拟IP地址。

>![](public_sys-resources/icon-note.gif) **说明：** 
>当前在部分区域中，子网与虚拟私有云已解耦，解耦后子网入口迁移，虚拟IP的相关操作入口也随之迁移。目前存在以下两种入口。
>-   在虚拟私有云详情页的“子网”页签，可对子网进行操作。
>-   在进入“网络 \> 虚拟私有云”后，在左侧导航栏直接选择“子网”，对子网进行操作。

## 操作步骤<a name="section56200370103127"></a>

1.  登录管理控制台。


1.  在管理控制台左上角单击![](figures/icon-region.png)，选择区域和项目。
2.  在系统首页，选择“网络 \> 虚拟私有云”。

**在子网未解耦区域，虚拟IP入口请参考[4](#li51522361618)\~[7](#li18152143611112)；在子网已解耦区域，虚拟IP入口请参考[8](#li715211361516)\~[10](#li19153536815)。**

**图 1**  入口图示<a name="fig111471723185713"></a>  
![](figures/入口图示.png "入口图示")

1.  <a name="li51522361618"></a>在左侧导航栏选择“虚拟私有云”。
2.  在虚拟私有云列表中，单击需要申请虚拟IP地址的子网所在的虚拟私有云名称。
3.  在“子网”页签中，单击需要申请虚拟IP地址的子网名称。
4.  <a name="li18152143611112"></a>选择“虚拟IP”页签，单击“申请虚拟IP地址”。
5.  <a name="li715211361516"></a>在左侧导航栏选择“子网”。
6.  在子网列表中，单击需要申请虚拟IP地址的子网名称。
7.  <a name="li19153536815"></a>在“IP地址管理”页签中，单击“申请虚拟IP地址”。
8.  选择IP类型。仅在IPv6开放区域可配置。
    -   IPv4
    -   IPv6

9.  选择虚拟IP地址的分配方式。
    -   自动分配：系统将自动分配IP地址。
    -   手动分配：系统将分配您指定的IP地址。

10. 选择手动分配方式，请填写虚拟IP地址。
11. 单击“确定”。

在IP列表中可以查看申请的虚拟IP地址。

