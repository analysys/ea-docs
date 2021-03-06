# 分销裂变

## 一、创建分销裂变活动

在增长模块中，找到分销裂变菜单，进入分销活动列表页，点击创建分销裂变活动开始从0到1策划一场分销裂变活动。

![](<../../../.gitbook/assets/image (60).png>)

### 1.1 配置活动信息

首先开始配置活动的基本信息，包括活动的标题、副标题、活动起始时间、头图、内容页以及活动商品的划线价、活动价等信息。

![](<../../../.gitbook/assets/image (61).png>)

同时，系统支持配置客服信息，目前支持配置客服的电话及微信两种方式，方便用户在购买遇到问题时及时联系客服。

可通过右侧的预览图实时预览配置的活动页样式与内容。

![](<../../../.gitbook/assets/image (66).png>)

* 活动价

        活动价是分销活动用户购买时实际支付的商品价格，在实际配置时，活动价不允许高于划线价。

* 划线价

         划线价为展示价格，通过活动价与划线价的对比，形成冲击引导用户购买。

* 库存

        库存代表当前活动的总库存数，如设置库存为100，当售空后，可编辑活动，将库存调整为200，即新增100的库存用于销售。

* 虚拟销量

        虚拟销量用于活动冷启动阶段，通过配置虚拟销量，让用户减少顾忌进行下单。当实际销量超过虚拟销量后，页面将展示实际的销量。

![](<../../../.gitbook/assets/image (67).png>)

* 排行榜

        支持配置是否展示排行榜，排行榜信息通过展示用户通过分销获取的现金奖励排行，引导更多用户进行分享。

![](<../../../.gitbook/assets/image (68).png>)

### 1.2 购买凭证配置

配置用户购买后，留存的路径以及购买凭证，将用户留存到微信群、公众号等。

![](<../../../.gitbook/assets/image (69).png>)

可自定义留存的文案以及留存目标，目前支持固定二维码、活码、活链三种类型：

* 固定二维码

        固定二维码主要用于导流到公众号等不限制用户数的场景，上传一张二维码图片，用户购买后引流对应的公众号或其他位置。

* 活码

        对于微信群等有人数限制的场景，系统支持配置多个二维码，可指定切换人数，当人数达到指定人数后自动切换到下一张二维码。

* 活链

       活链则是通过配置多个链接，当达到访问人数后自动切换下一个链接进行跳转。

### 1.3 分销配置

  完成活动信息和购买凭证后，点击下一步进行分销策略的配置。

![](<../../../.gitbook/assets/image (70).png>)

分销支持最多两级的分佣，可指定每级分佣的具体金额或订单金额比例。原则上一级分销返佣不超过订单金额的50%，二级分佣不超过订单金额的30%。

到账周期则为返佣多久可以到账到用户账户，可根据实际需要进行设置，到账后用户可在小程序发起提现。

{% hint style="warning" %}
用户提现需满足微信支付要求的实名认证，否则会提现失败。
{% endhint %}

最后则支持配置用户分享时的海报，支持自定义上传海报。配置完成后点击发布，将活动发布上线。

## 二、推广活动

活动发布后，可进入活动列表，生成活动小程序码或链接，进行活动推广。

![](<../../../.gitbook/assets/image (71).png>)

点击推广按钮，可新增推广渠道，主要负责跟踪不同渠道下的活动效果。

![](<../../../.gitbook/assets/image (72).png>)

输入自定义渠道名称即可保存为活动渠道。

![](<../../../.gitbook/assets/image (73).png>)

点击已创建的渠道，可以获取到推广链接及活动小程序码，利用已有的微信群及其他ea触达通道可将活动推广给用户进行裂变分销。

## 三、效果分析

活动开始推广后，可在活动列表点击指定活动的活动统计入口，查看效果统计分析，系统支持从3个维度查看效果分析

### 3.1 活动分析

![](<../../../.gitbook/assets/image (74).png>)

活动分析可用基础的指标及趋势，分享指标及趋势去评估活动带来的用户量、分享能力以及转化能力等数据。

支持按照不同的渠道、时间段进行统计。

### 3.2 用户分析

![](<../../../.gitbook/assets/image (75).png>)

用户分析主要从参与活动的用户角度进行活动分析，主要分析用户的基本属性如性别、地域、分享渠道来源以及场景值。

![](<../../../.gitbook/assets/image (76).png>)

支持查询、下载所有参与分销用户的邀请人数、订单数、一级二级的分佣金额等信息。

### 3.3 订单分析

![](<../../../.gitbook/assets/image (77).png>)

订单分析主要分析活动带来的订单数、销售额、返现金额和待返现金额，以及活动产生的订单明细，支持下载订单明细数据。

## 四、小程序端功能

活动发布到小程序后，用户可以按照如下路径进行购买、分享、提现等操作。

![](<../../../.gitbook/assets/image (78).png>)

用户通过推广链接可直接访问到小程序的活动详情页。

![](<../../../.gitbook/assets/image (79).png>)

点击立即购买可进入订单支付页，可直接调用用户在微信的收货地址，调用微信支付完成购买。

![](<../../../.gitbook/assets/image (80).png>)

购买完成后跳转至购买凭证页，用户可以直接扫码进入微信群。同时引导用户点击分享，赚取奖励。

![](<../../../.gitbook/assets/image (81).png>)

点击分享可生成分享海报，用户可以选择海报保存到手机分享好友，同时也可以直接转发小程序卡片给好友或微信群。点击小程序卡片这进入活动详情页，开始裂变。

![](<../../../.gitbook/assets/image (83).png>)

用户可点击我的页面，查看分销的收益、返现情况，以及查看分销订单的详细。

![](<../../../.gitbook/assets/image (84).png>)

用户可点击提现按钮提取已经到账的分佣奖励。

![](<../../../.gitbook/assets/image (85).png>)
