# 【原创项目】，基于Springboot+Vue的在线课程学习网站
基于Springboot+Vue的【在线课程学习网站】，系统代码全部原创，并提供带敲视频和笔记  

大家好，我是武哥，最近给大家手撸了一个基于Springboot+Vue的在线课程学习网站，在线课程网站，课程资源，视频播放，可用于实习项目、毕业设计、课程设计等，系统全部原创，如有遇到网上抄袭站长的，欢迎联系博主~  

#### 项目在线体验地址
体验地址：**（请电脑端浏览器访问）**：[http://101.35.218.50:82/](http://101.35.218.50:82/)  
管理员账号：**admin 123456**    
用户账号：**zhangsan 123456**    
线上环境，为了不影响其他小伙伴的体验，部分基础数据不允许修改。  


#### 项目技术栈  
> 前后端分离  
> 后端：Springboot2 + Mybatis  
> 前端：Vue2 + ElementUI  
> 数据库： MySQL  

#### 项目功能描述  

>**系统管理员**  
>登录、个人信息、修改密码、管理后台管理系统所有数据  
>####   
>01、**课程信息管理**：管理平台的所有课程信息，其中课程分为图文课和视频课两种，支持课程封面图片上传，视频课需要上传视频，并且可以在富文本编辑器里编辑课程详细介绍；两种类型的课程均**支持付费和公开，公开课可以免费在线观看，付费课需要用户支付后才可以看到课程内容。会员用户在购买课程的时候，享受课程的折扣价。**  
>02、**课程信息推荐**：管理员可以将某一个课程手动推荐到首页大图那里，重点展示  
>03、**积分专区管理**：宠物领养管理  
>04、**宠物寄养管理**：管理积分专区的课程，其中课程分为图文课和视频课两种，支持课程封面图片上传，视频课需要上传视频，并且可以在富文本编辑器里编辑课程详细介绍；两种类型的课程均**需要用户使用积分兑换才可以看。**  
>05、**积分专区推荐**：管理员可以将积分专区的某一个课程手动推荐到首页大图那里，重点展示  
>06、**在线资源管理**：用户可以在平台上传自己的资料，设置积分，其他用户下载后可以获取对应的积分，管理员在后台审核用户上传的资料信息，审核通过后，才可以展示在前台。  
>08、**课程订单**：管理用户在平台购买的课程订单信息  
>09、**资料下载**：管理用户在平台通过积分下载的资料信息  
>10、**积分兑课**：管理用户在平台通过积分兑换的课程信息  
>11、**首页统计**：查看平台不同类型课程的收益对比；平台会员占比；平台所有课程数量、积分专区课程数量、所有资料总数占比（echarts）  
>12、**管理员信息**：管理管理员的信息  
>13、**用户信息**：管理平台用户信息  
>14、**系统公告**：管理平台系统公告  
>####   
>**用户**  
>注册、登录、个人信息、修改密码、查看系统公告  
>####   
>1、**首页签到**：支持用户在首页签到，签到可以领取积分，积分可用于兑换积分专区的课程，或者用来下载资源。  
2、**首页查看课程信息**：用户在前台可以通过切换标签查看平台所有课程，分为：**视频课程、图文课程和积分专区**，支持点击进入对应课程的详情页。  
>3、**首页查看在线资源**：用户在前台首页可以查看目前平台里的一些可下载的资源，支持点击进入对应资源的详情页。  
>4、**全部课程**：用户可以进入全部课程板块，分页查看平台所有的课程（包括图文课和视频课），支持搜索  
>5、**积分专区**：用户可以进入积分专区板块，分页查看平台所有的可用积分兑换的课程（包括图文课和视频课），支持搜索  
>6、**海量资源**：用户可以进入资源专区，分页查看平台用户上传的所有资源，如果有自己需要的，可以使用积分进行下载。支持搜索  
>7、**我的资料**：用户可以在前台发布自己的资料，自己设置所需要的积分，管理员审核通过后，即可展示出来，其他用户下载你的资料，你会获取相应的积分，积分可以用于下载其他资料或者兑换积分专区的课程。  
>8、**已购课程**：可以查看自己购买过的课程信息，可以在这里统一查看，方便进入  
>9、**我的兑换**：可以查看自己使用积分兑换的所有课程信息，可以在这里统一查看，方便进入  
>10、**历史下载**：可以查看自己使用积分获取的所有资源信息，可以在这里统一查看，方便进入  
>11、**模拟充值**：用户可以在个人中心模拟充值，一次性充值满500，会自动成为会员用户，会员用户在购买课程的时候，会享受课程的折扣  
>12、**课程详情查看**：用户可以查看课程详情信息，未付费的课程或者未兑换的课程、或者未兑换的资源，只能看到它的介绍，当购买或者使用积分兑换后，方可看到资源的核心内容  
>13、**课程评论**：用户可以在课程详情页下面对课程发表自己的看法和评论  

#### 创新点  
> 1、富文本编辑器的使用，支持格式的调整，富文本内部图片上传  
> 2、用户签到功能，很多小伙伴不会做签到功能，这次教一下  
> 3、前台首页仿网易云课堂，页面精致，不担心什么重复，因为是仿首页  
> 4、课程内容的访问限制，根据用户是否付费或者积分兑换来展示部分信息内容  
> 5、echarts统计不同模块数据，方便管理员对平台资源进行分析  
> 6、复杂的多维度分类设计，例如：课程分为图文课和视频课，且又分为付费课和公开课，且又根据用户的身份不同（会员和非会员）享受不同的价格。用户端还支持不同维度的切换查看  
> 7、二级身份的设计：管理员和用户两个角色，其中用户又分为普通用户和会员用户两种身份，享受不同的优惠  
> 8、支持视频在线播放、下载  
#### 页面关键截图  
登陆页面:![请添加图片描述](https://img-blog.csdnimg.cn/direct/3c66393cd9364dac8e4642033d30d399.png)
#### 前台页面![请添加图片描述](https://img-blog.csdnimg.cn/direct/caf5a938ed2348b2ae99e81b69813716.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/6798dbce26d04d8383aac7c56b4b3750.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/3aca95d98bf04f58ac2c8c9fb0ec29f6.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/93c129c90e8847fabb4f18f758ff031f.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/d7739d6b53c844cc82914acffaa78f92.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/0681ca52368046f99dc00b95f8b67c30.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/2e640db634a64e219aed6badc0b48a83.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/027ef7f395fb494a9d2f45d573e01e94.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/360d646eaa324c9cb6e3823da576250c.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/5ba5cb64dd0f4d318eaf5484514d8286.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/f5d2e6b33d2f46df815fa12d71afd075.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/231d7d449edd4b6ba0617077eb35e9f0.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/cea2809f4ef74cb485ce90ff3a428aaf.png)
#### 管理后台![请添加图片描述](https://img-blog.csdnimg.cn/direct/9636b917bb934e71a97eeac67f946608.png)![请添加图片描述](https://img-blog.csdnimg.cn/direct/d4f931a48835495589cd23698e8dd343.png)
![请添加图片描述](https://img-blog.csdnimg.cn/direct/5b126e3a00264d06898d33ca0e5cd83a.png)
![请添加图片描述](https://img-blog.csdnimg.cn/direct/17ac64d1f162439c888b3a75feed4df8.png)
![请添加图片描述](https://img-blog.csdnimg.cn/direct/502424a3565b4fea8b9dbca8d294e2df.png)
![请添加图片描述](https://img-blog.csdnimg.cn/direct/5c6a70d0554a436fb0957a062789a519.png)
![请添加图片描述](https://img-blog.csdnimg.cn/direct/97b01da5b04c4e8688c1b33e801c3013.png)

资料获取方式：加入知识星球：【项目训练营】即可  
<img src="https://img-blog.csdnimg.cn/direct/44f688415c0c47cc81ad08a1f275e6a4.png" width="300px" />

**星球提供**：

1. （**价值**）星球内部的所有实战项目均提供脚手架、详细的笔记和完整的带敲视频，可以跟着完整学习视频敲出来，学习过程中提供一对一答疑。  
2. 星球内部的实战项目会一直更新，星球成员可以学习所有项目，具体项目列表如下（长期更新）：[https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf](https://www.yuque.com/xiaqing-en2ii/skflxg/cayqu7tvpxrwt9tf)  
3. 星球内部会提供不同的专栏，其中除了上述实战项目外，还有学习资料，比如经典学习笔记、超全面试题等  
4. 星球内部会不定期分享学习经验，开发经验，工作经验，如果你有需要，也可以提供相应文档    
