#jincdream.github.io    
## 简历   
      
- 姓名：岑锦超    
- 出生：1991
- 毕业：2014
- 性别：男    
- 籍贯：广州   
- 职业：前端开发工程师
- 电话：16605812577
- 教育：广东工业大学华立学院（本科）   
    
## 简介   
    
- 2013年（大三）开始接触前端开发。    
- 2014年9月-2015年5月，太平洋网络有限公司，前端开发工程师，负责专题页面开发
- 2015年5月-2016年5月，太平洋网络有限公司，前端开发架构 ，负责六网通用的能力、前端性能优化、前端工程化
- 2016年6月-2018年7月，淘宝（中国）软件有限公司，前端开发工程师，负责淘宝内容社区业务，涉及H5、weex、nodejs、B端
- 2018年8月-2022年5月，淘宝（中国）软件有限公司高级前端开发工程师，负责淘系客服线，带四个外包，全权负责淘宝客服的C端、B端跟千牛辅助接待插件，包括客户基础能力后台、客服工具、客服能力开放、专属客服（主动与建立了BC关系的店铺人群下发消息），涉及H5、weex、faas、B端、PC小程序


## 个人荣誉
- 阿里巴巴红草莓奖（2020）
- 淘系前端团队协作奖（2020）
    
## 主要前端项目

### 专属客服

业务介绍：

基于手淘消费者与商家建立的专属客服关系，在大促和日常期间给商家提供主动发送消息给消费者的能力。

技术难点：

- 推动产品、服务端、运营同学完成整体产品链路设计，完成开发对于的一套小二后台（基于faas），提升了至少10倍的运营效率与开发效率。

### PC千牛客户端-智能客服

业务介绍：

为商家客服提供的一款接待插件，包括了客户基本信息、客户订单信息和店铺商品信息三个模块。总结了小程序技术与开放商业生态的密切关系：[小程序为何能持续发展？](https://github.com/jincdream/jincdream.github.io/issues/16)。并在2019年双十一在商家客服现场驻场，帮助其现场定位、解决使用问题，同时对产品需求进行了访谈和调研。熟悉客服线的整体业务逻辑。

技术难点：

- 独自一人通过PC小程序完成了重构，同时依赖小程序-小程序插件体系，打造智能客服的新开放体系，已经接入20+二方、三方业务。
- 熟悉小程序技术架构体系和性能优化。

### 智能客服Web版本

业务介绍：

完成智能客服的UI视觉大改版

技术难点：

- 分离了大部分的逻辑与UI，梳理近50个接口，定义和区分开放模块，通过协议驱动Action，为后续改造成小程序版本提供了基础。
- 利用React和Hooks进行重构，拆分业务模块和Context，直接通过Context完成跨组件通信；利用Effect管理数据请求。另外，还尝试了通过webpack拆分异步JS Bundle，通过web-worker进行页面渲染，提升用户体验，通过 Shodow DOM 渲染React组件，探索web技术的开放模式。

### 中后台体系-动态表单、动态表格

业务介绍：

负责开发多个中后台应用，包括了淘宝话题管理小二后台、千牛客户服务平台和专属客服平台等等。

技术难点：

- 熟悉表单开发：[【中后台应用】从表单抽象到表单中台](https://github.com/jincdream/jincdream.github.io/issues/15) 设计和实现了一套从编辑器到表单的渲染的技术方案；是阿里开源的表单解决方案[Formily](https://formilyjs.org/#/bdCRC5/BlUJUaiw)的参与者，并基于该表单内核实现了小程序动态表单 https://github.com/jincdream/sorm
- 熟悉中后台开发，沉淀了一些TS模块（有单测）和react组件：
	- action-core： 注入处理器，后续通过配置化进行调用
	- [selector-core](https://github.com/jincdream/selector-core)：人生到处都是选择题，剥离了UI的纯JS的选择API。
	- obs-parser：前端组件化协议解析器，通过配置解析出组件和组件数据，可以直接扔给对应的小程序组件或者react进行渲染
	- **react-jpage：基于schema动态渲染页面，并支持联动、动态数据写入的描述** https://github.com/jincdream/react-jpage
	- **foow：支持结构化描述的函数式运行框架，串行一个个函数来实现具体的业务逻辑**
	- **jinter：可通用的前端通信方案**,https://github.com/jincdream/Jinter/blob/master/docs/modules/_index_.md
- 基于这些可以组成一套配置化生产页面的方案，再基于配置化到可视化开发。

### 淘宝社区-移动开发

业务介绍：

负责手淘社区、内容业务的前端开发，包括了淘宝的话题页、圈子、问大家和评价等产品。

技术难点：

- 利用weex进行跨端应用开发
- 通过node.js和内部node框架搭建服务器进行一些简单数据读写与处理

------

简历存档2016.6

### 专题项目组   
    
（六网特指太平洋电脑网、时尚网、汽车网、家居网、游戏网、亲子网）   
    
- 六网的专题页面制作，兼容IE6+，基本上2~4天一个中小型专题，根本停不下来    
- CMS专题模板制作,列如:电脑网[海淘馆](http://best.pconline.com.cn/haitao/jp)    
- 六网的项目页面制作，主要参与了时尚网[医疗美容项目](http://plastic.pclady.com.cn/)部分页面、汽车网[车友会](http://club.pcauto.com.cn/)部分页面    
- 电脑网改版[无人机CMS项目](http://drone.pconline.com.cn/)    
- 等等
- 
### 太平洋网络-网速架构组   
    
主要是JS的维护    
    
- 六网文章页评论``JS``,例如:[电脑网文章终端页](http://mobile.pconline.com.cn/669/6693098.html)的[评论JS](http://js.3conline.com/pconline/common/js/cmt.js)    
- 上线的又一个[评论JS](http://js.3conline.com/js/common/modules/cmt.js) [聚乐淘](http://buy.pconline.com.cn/discount/549/)。    
- 独立编写`pc-sub` ，基于`FIS3`的自动化工具编写。   
- `pcat`工具的编写，基于`FIS-MINI`（我自己抽离的FIS3的核心）实现前端组件化、自动部署、性能优化等功能。    
- [不追尾的不同速度的评论弹幕](http://live.pconline.com.cn/661.html) 
- 主要参与太平洋六网PC端网速与性能的监测    
- 六网PC端框架维护、公共组件维护    
- 研究和开发前端工程工具（基于FIS3开发前端工具）
    
## 社交   
- [微博](http://weibo.com/275727449)    
- [知乎](http://www.zhihu.com/people/cen-jin-chao)    
- [同性交友](https://github.com/jincdream/)   
- [Blog](https://github.com/jincdream/jincdream.github.io/issues)


