# BinLin
效率工具产品-短视频APP（元宇宙·无障碍版）
元宇宙·黑客松idea-beta(3.0)-短视频App

项目名称

《效率工具产品-短视频APP（元宇宙·无障碍版）》

成员介绍

个人选手：王健霖

队       名:   你说的都队

团队分工：前端、后端、开发、UI......

---本文遵循知识共享许可协议（Creative Commons license）CC4.0---

 

beta(3.0)：2022-04-22 

此版本优化了项目简介，丰富了“方案介绍，产品需求，用户痛点，设计运营模式”以及技术更新~

起草了“流程图”初步方案

对“呈现形式”进行了进一步的修改

对可使用ipfs技术和框架进行了整合

beta(2.0)：2022-04-20 

此版本确定了项目研究方向和研究课题~

beta(1.0)：2022-04-16 

此版本为第一代-初代项目建设草稿方案~



项目简介

基于ipfs协议的——>新一代短视频APP（元宇宙·无障碍版）

暨：一个互联网自媒体短视频文章资源汇集整合平台，集同步，下发，搜索于一身

后期可改进升级为一键实时同步所有内容平台，并一键下发（发布）创作内容到各个平台



为什么做此产品、痛点是什么：

很明显，视频创作目前已经三分天下，如果说做内容的话，完全达不到其他成熟平台的深度和成熟度，其次是流量的问题，视频流量已经被热门平台分走，想要另起炉灶肯定是难上加难，面对如此情况——对于已具备成熟的视频结构体系和应用场景，我们可以构造出一个全新的资源整合平台，方便创作者内容的一键导入和API接口权限的调用，完成内容整合（全平台）。

再加上ipfs点对点传输的特性，非常适合个人用户和人人都是自媒体时代，嵌入一个点对点搜索引擎，直达热点和内容，对服务器的压力大大减小，形成分布式运算力。

ipfs的属性需要用户自己上传内容，恰好可以形成一个内容支撑，达到项目需求

本项目旨在帮助个人用户和创作者方便快捷高效率同步自己的内容到web，为移动端用户赋予更多生命力和价值。



方案介绍：

最新修改：2022-04-21

新用户注册第一步——>授权账号同步内容（补充和丰富web3.0项目资源）



后期：

需要设计一个自动拉去本地网络的媒体平台账号ssl登录，提升用户体验（而不需要一个一个去绑定）



idea设计模式：提供一个视频导入接口，和一个文章导入接口~



i.视频导入接口的具体实现思路：

将自媒体视频创作者们的各大自媒体平台，例如：字节跳动抖音，快手，火山，西瓜视频，腾讯微视，好看视频，A站，B站，秒拍，百度全民小视频，美团美拍



ii.文章导入接口的具体实现思路：

将自媒体视频创作者们的各大自媒体平台，例如：微信公众号、知乎、百家号、头条号、小红书、微博、搜狐号、企鹅号



关于元宇宙：

核心：内容

more：将自己的创作内容放置于一个展示厅，类似博物馆艺术展示...



☑也可以不要这项——>前期用户入驻即赠送元宇宙虚拟形象（类似：柳夜熙）和虚拟货币用于培养用户习惯（类似于b站硬币）



流程图详细介绍（beta1.0）

 

## 公共网关资源托管网站CGI程序——>重定向到ipfs寻址——>产生ipfs协议的访问权限

Tips：(各大厂商合作，将http资源分支到ipfs并赋予独家的CID标识符) 

呈现形式

•1、类似Discord社区服务器形式（一个用户即为一个服务器，而非discord中一群爱好相同的人为一个服务器）



•2、名片全能王（主要“关于我—我的名片”界面中是把内容绑定和社交绑定以名片的形式展示出来）

but，内容-非名片，而是每个人的自媒体内容（视频和文章）和社交绑定（微信、微博、qq、Tik Tok、github、百度账号等等）



•3、Tik Tok短视频形式（第一界面左右滑动改变媒体平台，竖直滑动内容改动）



•4、类似开眼app形式：

(最终效果非此图片展示效果~)







上述临时项目地址：https://github.com/wjl110/KotlinMvp

技术要点

整合项目可使用的ipfs集群应用和开源框架：



dtube - 与 steem.it 集成的分布式视频共享，使用 ipfs 进行后端存储。

youtube2ipfs - 从 YouTube（和类似的视频平台）下载视频并将其添加到 IPFS。 来源 

Diffuse - 从您的 IPFS 节点或您使用的任何其他云/分布式存储服务播放音乐。 

Global Upload - IPFS 的文件传输服务，将文件上传到分布式网络的未来。 

ipfs-search - 自 2016 年以来搜索宇宙。 嗅探 DHT 八卦并索引文件和目录哈希。 元数据和搜索 API 可用。 来源 

ipfs.pics - 上传和分享图片。 

Orbit - IPFS 上的分布式点对点聊天应用程序。 来源 

Arbore - 建立在 IPFS 之上的朋友间文件共享应用程序。

Boards - 在浏览器中运行的分布式社交平台。 来源  

Alexandria - 去中心化的内容发布/货币化平台。 

infura.io - 基础设施：使用 API 和开发工具提供对以太坊和 IPFS 的安全、可靠和可扩展的访问，以帮助更轻松地构建去中心化应用程序。 

点对点网站 - 点对点网站托管在您的指尖！ 从您的浏览器发送功能齐全的 HTML（包括 CSS、JS）站点并附加文件，例如。 视频、图像等 来源 

Terrive - 使用 HIVE 区块链作为数据库和不可变图像/视频托管的照片和视频共享平台。 来源 











（未完善）

For普通用户：

一个内容生态丰富的短视频APP，向上兼容视频普通浏览，上下滑动指向小程序，衍生出更多的小程序，例：小说，视频，音乐，支付，等等

For视障人士：（智能播报）

可以与其进行无障碍交互服务，以及配套交互方式同步出更多的小程序，例：小说，视频，音乐，支付，等等

例：残障人士打开APP后，将听到，你关注住的某某up🐷更新了xxx，你关注的某微博博主，更新了xxx，你关注的抖音创作者xxx，更新了xxxx，多内容平台的推送~

 





特    点：

每一个人（包括残障人士）都能被赋予短视频浏览的特殊属性（在APP上浏览属于自己的推荐内容，具有短视频流行的生命力、拓展小程序指向为视障碍人士的特殊内容呈现）



后期~

浏览器中：

以小程序，插件的形式在App Store火狐/chrome上架衍生视频,音乐,云盘,会议,等应用,既可以使用原始的http协议浏览器,也可使用基于ipfs的点对点网络协议

小程序，插件 ——自动弹出优化访问选项卡，使用ipfs以访问提升访问速度。        

为web3.0的独家内容（自媒体）生态提供链路连接 ——>将自媒体用户的内容提供: 一键导入的功能，并提供个人认证的数字媒体版权©



项目互助论坛：（补充和丰富web3.0项目资源）并且创建属于自己的公网资源



拓展：

基于ipfs特性，具有内容直接查找的特点，可以将视频中的所有字幕和视频内容等比例划分成若干cid，储存于数据库中，用特定的链路标记，当用户搜索某个特定专业词语或者字幕or内容，可以直达视频内容点，超级链路标记法。



协议为：点对点超级链路传输协议（机器学习+算法自动识别）





项目简述：

本项目采用 Kotlin 语言编写，结合 MVP+RxJava2+Retrofit2+Glide等的架构设计，学习 Kotlin 利用空余时间开发的一款小项目，代码结构清晰有详细注释。

tips：

本项目借鉴了大量github资源=0.0=

《KotlinMvp》 是仿着“开眼Eyepetizer”之前版本并加上自己的想法，开发的一款的短视频小应用，每日为你推荐精选视频，让你大开眼界。



优点：

学习了 Kotlin 的一些语法相比 Java 而言源代码行数有所减少、方法数也有所减少。

Kotlin 团队为 Android 开发提供了一套超越标准语言功能的工具：

易拓展性：

- [Kotlin Android 扩展](https://www.kotlincn.net/docs/tutorials/android-plugin.html)是一个编译器扩展， 可以让你摆脱代码中的 `findViewById()` 调用，并将其替换为合成的编译器生成的属性。

- [Anko](http://github.com/kotlin/anko) 是一个提供围绕 Android API 的 Kotlin 友好的包装器的库 ，以及一个可以用 Kotlin 代码替换布局 .xml 文件的 DSL。













模块说明：

每日精选：首页采用下拉刷新+RecyclerView 实现，Banner展示每日精选推荐的视频，监听 RecyclerView 的滑动事件，实现 TitleBar 的隐藏显示功能，底部菜单采用高斯模糊的半透明效果，使整个 APP 风格更加清爽。

 发现： 包括关注和分类模块，关注是推荐的作者上传的视频集，分类包括时尚、运动、创意、广告、音乐、旅行、生活、记录、开胃、游戏、萌宠、动画、综艺、搞笑等可自由选择想查看的类型视频。

 热门： 热门排行榜包括周排行、月排行、总排行的视频列表。

 搜索： 根据关键字搜索榜你找到感兴趣的视频。

 我的： 个人主页的相关介绍。

观看记录： 查看之前看过的视频，按时间进行排序。



特别说明：

根据残障人士特别优化的API和模块支持拓展



灵感来源：

https://github.com/git-xuhao/KotlinMvp/releases



开眼APP：

https://github.com/kaikaixue/Eyepetizer

最初是看了这个项目才开始做的，学了不少东西，写出了我自己的代码风格



licenses：

http://www.apache.org/licenses/LICENSE-2.0

More

个人github地址:https://github.com/wjl110

Python 中的非官方 TikTok API 包装器https://github.com/davidteather/TikTok-ApiFlutter 

开源浏览器：https://github.com/scoute-dich/browser/releases

开源chrome：https://github.com/chromium/chromium

无障碍用于自动化 Web UI 测试的辅助功能引擎：https://github.com/dequelabs/axe-core

Google and Udacity course on Accessibility：https://github.com/udacity/ud891

可访问性（a11y）可视化工具包：https://github.com/Khan/tota11y https://khan.github.io/tota11y/

安卓kotlin项目:https://github.com/search?q=kotlin

 基于Kotlin+MVP+Retrofit+RxJava+Glide 等架构实现短视频类小项目：https://github.com/git-xuhao/KotlinMvp

Tiktok 抖音实战https://github.com/DingMouRen/flutter_tiktok

高仿抖音APPhttps://github.com/running-libo/Tiktok





TODO-list（3）

☑项目文档和计划

□程序框架开发

□前端UI


