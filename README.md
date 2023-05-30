# 安卓餐饮收银
项目采用uniapp开发，屏幕自适应，支持快餐和桌台。支持线上会员、实体卡、充值、商品建档、交班、订单、退款、改价、小票打印等

Gitee地址：https://gitee.com/linxixiaogege/cashier
>小技巧：如果您看不到下面的图片，这是因为DNS污染了，即无法访问存放了github图片素材的raw.githubusercontent.com站点，Windows系统你可以修改“C:\Windows\System32\drivers\etc”路径下的hosts文件，在文件末尾添加上如下代码：
    //hosts文件

    185.199.108.133   raw.githubusercontent.com
    185.199.109.133   raw.githubusercontent.com
    185.199.110.133   raw.githubusercontent.com
    185.199.111.133   raw.githubusercontent.com
    2606：50c0:8000::154 raw.githubusercontent.com
    2606：50c0:8001::154 raw.githubusercontent.com
    2606：50c0:8002::154 raw.githubusercontent.com
    2606：50c0:8003::154 raw.githubusercontent.com

##  一、项目说明

1.点餐分为“快餐”和“桌台点餐”。“快餐”无需选择桌台，“桌台点餐”需要选择桌台和用餐人数

2.点餐页面中，商品的数量、单品改价等操作放置在中央操作区，商品列表区域会以气泡徽标形式显示该商品、分类的数量

3.结账页面中，新增“打印预结单”功能。勾选“组合支付”后，除优惠券支付默认需要手动输入支付金额外，选择其他支付需要手动输入支付金额。“打印结账单”复选框勾选，则会在订单结束后自动打印“结账单”，您也可以在设置页面中的“打印设置”进行提前配置。

4.“桌台”页面中，会显示各个桌台的状态（桌台状态、订单金额、用餐时长、用餐人数），

点击“空闲”桌台可以进行开台操作，点击其他状态桌台后再点击右上角“桌台操作”可以进行更多操作

5.在“订单”页面中，新增了“打印预结单”、“打印结账单”、“继续点菜”、“直接结账”功能

6.在“设置”页面中的功能说明如下：

 ①.“是否每天重置取餐号”：开启后第二日生效，将会从“取餐号起始值”开始

 ②.“称重商品单位”：只对称重商品生效，默认单位“斤”

 ③.“打印端口”：根据打印机与收银机之间的连接方式（网线、USB数据线）决定，默认使用USB端口

 ④.“订单完成是否打印结账单”：对应结账页面的“打印结账单”复选框

 ⑤.“操作日志存储天数”：默认存储最近7天的日志，可以手动修改

⑥.“操作日志存储路径”:收银机从Android文件夹开始，可以在收银机的“文件”程序中查看

## 二、系统截图

![image-20230530102555036](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530102555036.png)

![image-20230530102718572](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530102718572.png)

![image-20230530102830838](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530102830838.png)

![image-20230530102853452](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530102853452.png)

![image-20230530103011613](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530103011613.png)

![image-20230530103030085](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530103030085.png)

![image-20230530150701523](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530150701523.png)

![image-20230530103149980](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530103149980.png)

![image-20230530103206491](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530103206491.png)

![image-20230530103237186](https://github.com/linxi-001/Cashier/blob/main/data/image-20230530103237186.png)
