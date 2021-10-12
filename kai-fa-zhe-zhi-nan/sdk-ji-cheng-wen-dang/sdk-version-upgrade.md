# SDK 版本更新说明



{% tabs %}
{% tab title="IOS SDK" %}
|    版本   | 描述                                                                                                                                                                                                                                                                                                                                           | 大小   |
| :-----: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
|  1.26.2 | <p><strong>修复:</strong></p><p>1、修复 pushToken 接口某些情况下可能导致的闪退问题；</p><p>2、修复某些情况下推送触达上报不准的问题；</p>                                                                                                                                                                                                                                               | 2.2M |
|  1.2.5  | <p><strong>新增:</strong></p><p>1、新增推送上报设备唯一标识接口；</p><p>2、支持对接极光推送；</p><p></p><p><strong>优化:</strong></p><p>1、增加接口参数检查，增强系统稳定性；</p>                                                                                                                                                                                                            | 2.2M |
|  1.2.4  | <p><strong>新增:</strong></p><p>1、banner 信息流支持基于事件触发展示创建的活动；</p><p></p><p><strong>修复:</strong></p><p>1、修复弹窗等活动规则匹配若干bug；</p><p></p><p><strong>优化:</strong></p><p>1、优化弹窗布局渲染，支持图文自适应；</p>                                                                                                                                                       | 2.2M |
|  1.2.3  | <p><strong>新增:</strong></p><p>1、banner 信息流轮播图支持单张图片点击跳转；</p>                                                                                                                                                                                                                                                                                 | 2.1M |
|  1.2.2  | <p><strong>新增:</strong></p><p>1、banner 信息流增加轮播图模板功能；</p><p>2、banner 信息流小图标、视频没活动时支持展示默认配置；</p><p>3、个性化文本变量增加默认文案；</p><p></p><p><strong>修复:</strong></p><p>1、修复个性化文本字体颜色显示不正确的问题；</p><p>2、修复系统静音模式下 banner 信息流视频播放没有声音的问题；</p><p>3、修复某些情况下活动的 URL 链接无法跳转的问题；</p><p></p><p><strong>优化:</strong></p><p>1、优化图片磁盘缓存，修复某些情况下读写导致闪退的问题，增强系统稳定性；</p> | 2.1M |
|  1.2.1  | <p><strong>修复</strong></p><p>1.修复弹窗新规则下第一次触发后杀死进程后续不弹窗的问题；</p><p>2.修复某些情况下弹窗不弹出或闪退的问题，增强系统稳定性；</p><p></p><p><strong>优化</strong></p><p>1.openURL 处理ios 10.0接口；</p><p>2.获取 idfa 适配 ios 14.0；</p><p>3.优化弹窗体验：图片弹窗点击跳转链接为空的话点击图片不响应</p>                                                                                                          | 1.9M |
|  1.2.0  | <p><strong>新增:</strong></p><p>1、增加对 banner 信息流广告（大图）的支持及对应接口；</p><p>2、增加对弹窗活动新规则（点击、关闭后续弹出频率）的匹配；</p>                                                                                                                                                                                                                                        | 1.9M |
| 1.1.9.3 | <p><strong>新增:</strong></p><p>1、弹窗、推送新增对 URL scheme 形式跳转链接的支持；</p><p></p><p><strong>修复:</strong></p><p>1、修复若干可能造成弹窗闪退的问题，增强系统稳定性；</p><p></p><p><strong>优化:</strong></p><p>1、优化弹窗、推送点击跳转逻辑；</p>                                                                                                                                               | 1.8M |
|  1.1.9  | <p><strong>新增</strong></p><p>1.注册远程推送可配置；</p><p>2.新增与方舟 SDK 的时间校验逻辑；</p><p>3.接收事件回调接口修改，兼容旧版方舟 SDK；</p>                                                                                                                                                                                                                                      | 1.8M |
|  1.1.8  | <p><strong>修复</strong></p><p>1.修复 iPhone6 不弹窗问题；</p>                                                                                                                                                                                                                                                                                         | 1.8M |
|  1.1.7  | <p><strong>新增</strong></p><p>1.AnalyaysEaConfig 增加可配置 url 参数；</p><p></p><p><strong>修复</strong></p><p>1.修改数据存储模式，groupIdentifier 参数可为空；</p><p>2.优化弹窗内部判断逻辑，增加系统稳定性；</p>                                                                                                                                                                       | 1.8M |
|  1.1.6  | <p><strong>新增:</strong></p><p>1、文本弹窗支持一个按钮的样式；</p><p></p><p><strong>修复:</strong></p><p>1、优化推送 deviceToken 上报逻辑，去除上报为空的情况；</p><p></p><p><strong>优化:</strong></p><p>1、移除对外接口 registerForRemoteNotificationWithDelegate，集成到SDK内部；</p>                                                                                                           | 1.8M |
| 1.1.5.6 | <p><strong>新增:</strong></p><p>1、增加上报推送token的接口；</p><p></p><p><strong>修复:</strong></p><p>1、修复token不能及时更新导致推送有时收不到的问题；</p><p>2、修复上报推送token时用户信息不全的问题；</p><p></p><p><strong>优化:</strong></p><p>1、登录接口增加重试机制；</p><p>2、framework取消对模拟器32位i386架构支持；</p>                                                                                            | 1.8M |
|  1.1.4  | <p><strong>优化:</strong></p><p>1、取消对 UIWebView 支持；</p><p>2、SDK大小；</p>                                                                                                                                                                                                                                                                         | 2.7M |
|  1.1.3  | <p><strong>新增:</strong></p><p>1、添加本地缓存支持；</p><p>2、添加HTTP请求失败后重试机制；</p><p></p><p><strong>修复:</strong></p><p>1、去除文本背景色导致的弹窗边框颜色不统一的问题</p><p></p><p><strong>优化:</strong></p><p>1、push 事件上报、弹窗匹配的机制；</p>                                                                                                                                         | 2.5M |
| 1.1.1.2 | <p><strong>新增:</strong></p><p>1、日志的分级管理；接口增加日志开关功能；</p><p></p><p><strong>修复:</strong></p><p>1、打包编译项设置；</p><p>2、push到达、点击事件的上报问题；</p>                                                                                                                                                                                                         | 2.4M |
| 1.1.1.1 | <p><strong>新增:</strong></p><p>1、支持多事件触发弹窗；</p><p>2、设置页面别名的功能；</p><p></p><p><strong>修复:</strong></p><p>1、弹窗的背景色的问题；</p><p>2、弹窗跳转中URL中空格的问题；</p><p></p><p><strong>优化:</strong></p><p>1、优化立即弹窗的页面计数机制；</p><p>2、优化事件的属性过滤规则；</p>                                                                                                                 | 2.4M |
|  1.1.1  | <p><strong>新增:</strong></p><p>1、弹窗功能增强；</p><p>2、推送功能增强；</p><p></p><p><strong>修复:</strong></p><p>1、弹窗功能APP 页面内跳转问题；</p><p>2、修复打包发布时Found an unexpected Mach -O header code:0x72613c21错误；</p><p></p><p><strong>优化:</strong></p><p>1、优化SDK拉取活动列表判断；</p><p>2、接口请求超时时间设置为60秒；</p>                                                                 | 2.4M |
|  1.0.0  | <p><strong>新增:</strong></p><p>1、弹窗功能；</p><p>2、推送功能；</p>                                                                                                                                                                                                                                                                                      | 2.7M |
{% endtab %}

{% tab title="android SDK" %}
| 版本      | 描述                                                                                                                                                                         | 大小   |
| ------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| 2.2.1   | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、token失效逻辑优化；</p>                                                     |      |
| 2.2.0   | <p><strong>新增:</strong></p><p>1、添加上报微信id接口；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化对话框显示；</p>                                             |      |
| 1.29.2  | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、信息流逻辑的优化；</p>                                                        |      |
| 1.29.0  | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化方舟UBA的版本依赖；</p><p>2、弹窗逻辑的优化；</p>                                   | 340K |
| 1.26.0  | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化网络请求方式；</p>                                                        | 340K |
| 1.2.4   | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、弹窗的展示样式优化；</p><p>2、banner信息流的展示样式优化；</p>                             | 340K |
| 1.2.3   | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、在没有初始化的情况下优化事件上报；</p><p>2、banner轮播支持一图一点击事件；</p>                     | 340K |
| 1.2.2   | <p><strong>新增:</strong></p><p>1、新增banner位的功能；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化个性化文本替换功能；</p>                                       | 340K |
| 1.2.1   | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化第三方数据库的使用；</p><p>2、优化弹窗的展示效果；</p>                                  | 334K |
| 1.2.0.1 | <p><strong>新增:</strong></p><p>1、添加信息流功能；</p><p>2、支持新弹窗规则；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                                        | 287K |
| 1.1.7   | <p><strong>新增:</strong></p><p>1、服务器时间的校准；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化弹窗规则的逻辑；</p>                                             | 284K |
| 1.1.6.1 | <p><strong>新增:</strong></p><p>1、添加设置EA服务的URL的功能；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                                                 | 283K |
| 1.1.6   | <p><strong>新增:</strong></p><p>1、文本弹窗支持一个按钮的样式；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                                                   | 283K |
| 1.1.5   | <p><strong>新增:</strong></p><p>1、设置主页的功能；</p><p>2、增加上报厂商推送token的接口；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化重试机制；</p>                       | 282K |
| 1.1.4.2 | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、减少对开源框架的依赖；</p>                                                      | 274K |
| 1.1.3   | <p><strong>新增:</strong></p><p>1、添加本地缓存支持；</p><p>2、添加HTTP请求失败后重试机制；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                               | 217K |
| 1.1.1.3 | <p><strong>新增:</strong></p><p>1、支持日志关闭；</p><p>2、支持页面添加别名的功能；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                                     | 217K |
| 1.1.1   | <p><strong>新增:</strong></p><p>1、弹窗功能支持多种规则匹配；</p><p>2、支持多事件触发一次弹窗；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化日志输出的格式；</p>                    | 217K |
| 1.1.0   | <p><strong>新增:</strong></p><p>无</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化日志输出的格式；</p>                                                       | 217K |
| 1.0.9.1 | <p><strong>新增:</strong></p><p>1、弹窗功能-支持在同一个事件顺序弹窗；</p><p>2、弹窗的文本中支持动态的事件属性替换；</p><p><strong>修复:</strong></p><p>1、立即弹窗功能没有显示在第一个页面上；</p><p><strong>优化:</strong></p><p>无</p> | 217K |
| 1.0.9   | <p><strong>新增:</strong></p><p>1、弹窗功能；</p><p>2、项目和活动配置；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                                           | 215K |
{% endtab %}

{% tab title="android pushSDK" %}
| 版本    | 描述                                                                                                                                  | 大小   |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------- | ---- |
| 0.3.0 | <p><strong>新增:</strong></p><p>1、集成小米、华为、OPPO、VIVO、魅族推送SDK</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p> | 825K |
{% endtab %}

{% tab title="JS SDK" %}
| 版本    | 描述                                                                                                                                                                                                                                        | 大小  |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| 2.0.7 | <p><strong>新增：</strong><br>1、事件属性触发支持多值过滤；<br><strong>修复：</strong><br>无</p>                                                                                                                                                               | 22  |
| 1.1.7 | <p><strong>新增：</strong><br>1、增加用户体验控制项；<br><strong>修复：</strong><br>无<br><strong>优化：</strong></p><p>1、多事件触发一次弹窗；</p>                                                                                                                       | 22K |
| 1.1.6 | <p><strong>新增：</strong><br>1、支持多事件触发一次弹窗；<br>2、支持发送测试设备活动不受弹窗次数控制；<br><strong>修复：</strong><br>无<br><strong>优化：</strong></p><p>无</p>                                                                                                       | 21K |
| 1.1.5 | <p><strong>新增：</strong></p><p>1、支持所有用户和新访问用户弹窗；<br>2、支持基于浏览页面增加过滤条件；</p><p><strong>修复：</strong></p><p>1、IE11不兼容assign方法bug。</p><p><strong>优化：</strong><br><strong></strong>无</p>                                                          | 20K |
| 1.1.4 | <p><strong>新增:</strong></p><p>1、支持神策数据平台的弹窗；</p><p>2、支持新模板、字体颜色、按钮大小、等配置；</p><p>3、支持浏览页面 * 通配符匹配；</p><p>4、支持按钮不链接跳转，只关闭弹窗；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>1、优化日志输出格式；</p><p>2、单个事件一次触发多个弹窗，依次弹出；</p> | 19K |
| 1.1.2 | <p><strong>新增:</strong></p><p>1、对 $url_domain 进行不含参匹配；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                                                                                                          | 18K |
| 1.1.0 | <p><strong>新增:</strong></p><p>1、web 弹窗功能；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                                                                                                                       | 18K |


{% endtab %}

{% tab title="wechat SDK" %}
|   版本  | 描述                                                                                                                                                                          | 大小  |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --- |
| 2.07  | <p><strong>新增：</strong><br>1、事件属性触发支持多值过滤；<br><strong>修复：</strong><br>无</p>                                                                                                 | 85K |
| 1.2.6 | <p><strong>新增：</strong><br><strong></strong>无<br><strong>修复：</strong><br><strong></strong>无</p><p><strong>优化：</strong><br><strong></strong>1、将上报用户信息的字段appid修改成wx_appid</p> | 85  |
| 1.2.0 | <p><strong>新增：</strong></p><p>1、增加用户体验控制项；</p><p><strong>修复：</strong></p><p>无</p><p><strong>优化：</strong></p><p>无</p>                                                        | 84K |
| 1.1.8 | <p><strong>新增：</strong></p><p>1、支持跳转公众号文章和其他小程序；<br>2、支持虚拟事件；<br>3、新增日志输出参数；</p><p><strong>修复：</strong></p><p>无</p><p><strong>优化：</strong></p><p>无</p>                      | 80K |
| 1.1.7 | <p><strong>新增：</strong></p><p>1、新增小程序用户信息上报</p><p><strong>修复：</strong></p><p>无</p><p><strong>优化：</strong></p><p>1、多事件触发一次弹窗；</p><p></p>                                     | 33K |
| 1.1.6 | <p><strong>新增：</strong></p><p>1、支持多事件触发一次弹窗；</p><p><strong>修复：</strong></p><p>无</p><p><strong>优化：</strong></p><p>无</p>                                                      | 22K |
| 1.1.5 | <p><strong>新增:</strong></p><p>1、支持所有用户和新访问用户弹窗；</p><p><strong>修复:</strong></p><p>1、修复弹窗活动IOS低版本图片展示bug；</p><p><strong>优化:</strong></p><p>无</p>                              | 15K |
| 1.1.3 | <p><strong>新增:</strong></p><p>1、小程序弹窗功能；</p><p><strong>修复:</strong></p><p>无</p><p><strong>优化:</strong></p><p>无</p>                                                          | 15K |


{% endtab %}
{% endtabs %}











