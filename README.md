# 20春API项目

|文档名称|Sport-doctor—产品需求文档|
|--|--|
|产品名称|Sport-doctor(运动医生)|
|产品描述|一款通过收集男大学生运动损伤的信息，运用人工智能技术(图灵机器人服务、自然语言处理)进行数据分析整理，主要利用自然语言处理中的问答系统，解决男大学生运动损伤处理需求的App|
|产品版本|2.0|
|文件现状|进行中|
|文件作者|丘小峰|

## 加值宣言
   我认为目前市面上欠缺可以针对**运动损伤处理**的健康类App，虽然国内已有一些APP也开发了病患指导的功能，像是在线医生问诊等，但这些指导难以为用户设计针对性的方案，且缺乏具体的治疗价值。
   此款App能够给在校的男大学生在日常生活中的体育运动中产生的运动损伤提供一个可行的治疗方案。将图灵机器人与自然语言处理中的问答系统相结合进行机器学习，建立一个问答社区（如知乎、百度知道）不断完善数据库，可以快速地、准确地回答用户提出的需求。还可以结合自然语言处理的文本分析和情感分析，优化与用户的交互体验。

## 一、需求概述
### 1. 产品背景
   直至目前，大学生的体育运动损伤是十分常见的，并且特别是在男大学生中尤为明显，因为男大学生绝大部分会喜欢用身体对抗进行的体育运动，如：篮球、足球等。在这些运动中经常会出现不同程度的损伤。而这时候如果处理不当，一次一次的损伤，一次一次的处理不得当留下隐患，有可能这时候不明显的症状日后会越来越严重。因此这款产品可以让男大学生随时随地在遇到运动损伤的时候能得到合适恰当的建议。
   
### 2. 产品市场
运动损伤在大学校园里真的再常见不过了，但是每次都依靠常识以及临时搜索的片面资料很难真正做到很好得处理。与其选择瞎猫碰上死耗子还不如能有这样一款可以随时查询方法的App。所以这款App是符合男大学生的实际情况需要并且是简洁有效的方法。

### 3. 市场概述
##### 3.1国内外智能健康管理类应用市场概述
- 国外健康类应用市场描述
> 由于医疗体系不同，发达国家的电子病历系统已接近完成，目前正在实施建设全国医疗信息化系统。1998年，英国国家医疗服务体系（NHS）提出为每位居民建立覆盖终生的电子病历并实现所有医生能访问这些电子病历，目前已基本完成。2010年，美国政府建立了国家健康信息网络（NHIN）， 即建立跨医疗机构的全国范围的电子病历，以此来实现医疗机构之间的信息共享。
                                       ——《国外健康类ＡＰＰ评价研究综述》-仝晶晶、邓胜利（武汉大学信息资源研究中心，武汉，４３００７２）
- 国内健康管理类应用市场描述                                       
> 国内的移动医疗目前缺乏类似日本的国家健康体系支持，商业化模式亦不完善，尚处于早期快速发展、快速“烧钱”与摸索阶段，准入门槛不高，产品良莠不齐，临床专业性App匮乏。根据中国APP客户端注册中心的数据显示，截至2014年，iTunes商店中已经有16275款医疗与健康相关的应用，主要集中在运动保健、自问诊平台和挂号预约，而在患者的用药提醒、病程记录和信息反馈方面基本处于空白状态。根据艾媒咨询发布的《2015年中国“互联网＋”医疗研究报告》，挂号预约类、问诊咨询类和医疗资讯类APP，分别占比28.5%、24.9%、17.9%，但这些APP大多功能有限，有的甚至只有1项主要功能，即提供相关的数据信息。这些APP内容同质化严重，有的应用看上去似乎更像是玩具。只有不到2500款应用既能够提供数据信息，又能够追踪用户的数据，至于拥有提示或预警等功能的应用数量就更少了。在这其中，预约挂号类APP受国内医疗资源分布的影响，过于集中在三甲医院，仅仅是提供资源的平台，而缺乏资源分流的能力。问诊类和咨询类APP由于线上咨询 和线下医疗的分离，大多只停留在初步问诊阶段，难以提供有效的医疗服务。而人们真正期待的革命性移动医疗应用应是能将常用功能成功整合到一个平台之上，而此整合后的平台又能够改善人们传统的保健与医疗方式。
          ——《健康管理类应用软件国内外现状与前景分析》 张子豪、章红英-首都医科大学基础医学院，北京-100069；首都医科大学中医药学院，北京-100069 
- 总结来看：
1. 国外健康管理类应用软件现状：国外健康管理类APP更多地结合了临床应用[4]，注重用药指导、临床指南、临床监测等功能的研发，为用户提供专业化、标准化的服务。
2. 国内健康管理类应用软件现状：国内健康管理类应用软件大多功能有限。
因此产品发展动态：**如何将App的功能上限不断提高是关键，利用人工智能的有机结合，可以不断进行机器学习、丰富数据库，从而使产品在迭代过程中不断改进。**
##### 3.2发展优势
- 目前健康管理里人工智能应用不多，有充足的发展空间；
- 对健康管理类移动端的需求，近年来，特别是在2020年新冠疫情期间需求增加；
- 通过人工智能的有机结合可以提高用户体验、提高准确率等来提高App的上限；

## 二、核心价值（最小可行性产品）
为男大学生日常的运动损伤提供可行的处理方案。

##### 用户痛点
1. 市面上没有针对此类运动损伤的健康类软件；
2. 处理运动损伤的时候经常没有具体的方法，只是靠猜测和常识来做判断；
3. 有时候为了得到正确的治疗，总是去医务室，占用学校资源。

## 三、用户分析
1. 目标用户群：
- 核心用户：男大学生

2. 用户画像及使用场景
- ![男大学生](https://gitee.com/EdisonQXF/API/raw/master/images/%E8%BF%90%E5%8A%A8%E5%8C%BB%E7%94%9F%E7%94%A8%E6%88%B7%E7%94%BB%E5%83%8F.png)
- 使用场景：经常做体育运动，受到运动损伤了却不知道该怎么做。于是使用这款运动医生App，能够很方便的知道自己运动损伤的可能情况，并且知道具体怎么做的建议，比如需要热敷还是冰敷，做一些什么样的拉伸运动去缓解疼痛等等。

## 四、核心价值与用户痛点
|用户痛点|API加值|
|:--:|:--:|
|无法随时得到有价值的建议|自然语言处理的问答系统快速准确地给出回答|
|对运动的损伤存在疑问|通过图灵机器人为用户解答疑惑|
|个人资料信息的安全保证|使用信息需要授权，输入身份证号码、人脸识别等方式|

## 五、人工智能概率性与用户痛点
图灵机器人技术与自然语言处理的问答系统，有以下优势：

|图灵机器人技术优势/用户痛点|自然语言处理的问答系统技术优势/用户痛点|
|:--:|:--:|
|1. 语义理解准确：开放域聊天准确率81.64%，垂域技能准确率96.34%|1. 自定义问题成本低|
|2. 知识图谱：千万级实体及关系知识，支持逻辑与关系的知识推理|2. 对于完全匹配的问题可以绝对准确|
|3. 基础知识库：问答知识库1亿条，高频知识库1000万条|3. 有足够数据的问答系统甚至不需要训练|

所以，该产品利用图灵机器人与用户进行交互，通过问答系统准确匹配出运动损伤的处理方案，图灵机器人结合问答系统，根据强大的数据库进行的分析出错率很低。

**识别、分析不准确的方法：机器自身的深度学习、丰富数据库**

## 六、需求列表（对应人工智能加值）
|序号|api技术|用户场景|优先级|
|--|--|--|--|
|1|问答系统|准确、迅速匹配正确的运动损伤处理方法|A（重要）|
|2|图灵机器人|与用户进行对话（语音、文本）满足用户提出的需求|A（重要）|
|3|Azure 认知服务（如文本分析和语言理解）|来解释客户情绪和意图|B（次重要）|
|4|Azure人脸识别|对用户个人数据进行保障的重要手段之一|B（次重要）|

## 七、产品结构图（图片可能比较大，加载不出来刷新即可）
1. 产品功能结构图
![产品功能结构图](https://gitee.com/EdisonQXF/API/raw/master/images/%E8%BF%90%E5%8A%A8%E5%8C%BB%E7%94%9F-%E4%BA%A7%E5%93%81%E5%8A%9F%E8%83%BD%E7%BB%93%E6%9E%84%E5%9B%BE.png)


2. 用户流程图
![用户流程图](https://gitee.com/EdisonQXF/API/raw/master/images/%E8%BF%90%E5%8A%A8%E5%8C%BB%E7%94%9F-%E7%94%A8%E6%88%B7%E6%B5%81%E7%A8%8B.png)


3. 产品结构图
![产品结构图](https://gitee.com/EdisonQXF/API/raw/master/images/%E8%BF%90%E5%8A%A8%E5%8C%BB%E7%94%9F-%E4%BA%A7%E5%93%81%E7%BB%93%E6%9E%84%E5%9B%BE.png)

## 七、数据推理
||页面|
|--|--|
|问题1|我们在页面上可以获得什么内容|
|回答1|运动损伤情况可能症状，选择合适的并给出处理方案|
|问题2|向用户输出的结果内容从哪里来|
|回答2|建立数据库和去开放平台调用api，进行问答系统匹配获得结果内容|
|问题3|请求从哪里来|
|回答3|用户或者智能设备对产品输入身体状况的相关信息|
|问题4|如果分析病情的过程中出现明显的识别错误，应该如何获取并处理这些数据数据|
|回答4|通过用户的反馈功能进行信息获取，通过用户的自愿反馈扩大数据库，强化机器学习，不断扩大数据库进而降低失败率|

## 八、产品原型及交互设计
##### [原型文档下载区](https://github.com/EasonQXF/nfu.API/tree/master/%E8%BF%90%E5%8A%A8%E5%8C%BB%E7%94%9F%E5%8E%9F%E5%9E%8B%E4%BA%A4%E4%BA%92%E7%95%8C%E9%9D%A2)
##### [原型文档交互展示](https://i2zbnz.axshare.com)
##### [原型文档rp文件下载区](https://github.com/EasonQXF/nfu.API/blob/master/%E8%BF%90%E5%8A%A8%E5%8C%BB%E7%94%9F.rp)

1. 启动、注册、登录、首页界面

- 启动界面
![启动界面](https://gitee.com/EdisonQXF/API/raw/master/images/%E5%90%AF%E5%8A%A8%E7%95%8C%E9%9D%A2.jpg)
- 注册界面
![注册界面](https://gitee.com/EdisonQXF/API/raw/master/images/%E6%B3%A8%E5%86%8C.png)
- 登录界面
![登陆界面](https://gitee.com/EdisonQXF/API/blob/master/images/%E7%99%BB%E5%BD%95.png)
- 首页界面
![首页界面](https://gitee.com/EdisonQXF/API/raw/master/images/%E9%A6%96%E9%A1%B5.png)
2. 核心页面——图灵机器人解答界面

![图灵机器人解答界面](https://gitee.com/EdisonQXF/API/raw/master/images/%E5%9B%BE%E7%81%B5%E6%9C%BA%E5%99%A8%E4%BA%BA.png)

3. 主要页面——问答社区

![问答社区](https://gitee.com/EdisonQXF/API/raw/master/images/%E9%97%AE%E7%AD%94%E7%A4%BE%E5%8C%BA.png)

## 九、API的运用（展示主要应用API）
**需要通过注册登录得到API Key和Secret Key获取access_token**
###### （一）问答系统
- 开源问答系统参考链接：
- [开源软件>建站系统>开源问答系统 (31)](https://www.oschina.net/project/tag/299/qa)
- [问答系统 - weiyinfu - 博客园](https://www.cnblogs.com/weiyinfu/p/10839297.html)

###### （二）图灵机器人
```python
def tuling(msg):
    api_key = "******"
    url = 'http://openapi.tuling123.com/openapi/api/v2'
    data = {
        "perception": {
            "inputText": {
                "text": msg
            },
        },
        "userInfo": {
            "apiKey": api_key,
            "userId": "1"
        }
    }
    datas = json.dumps(data)
    html = requests.post(url, datas).json()
    if html['intent']['code'] == 4003:
        print("次数用完")
        return None
    return html['results'][0]['values']['text']
msg = '我今天肚子疼'
print("原话>>", msg)
res = tuling(msg)
print("图灵>>", res)
```
输出：
原话>> 我今天肚子疼
图灵>> 

**图灵机器人API和青云客智能聊天机器人API的比较**
|      | 图灵机器人API                                                                                                                                                        | 青云客智能聊天机器人API                                                                                            |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| 功能 | 开放域聊天准确率81.64%，垂域技能准确率96.34%  知识图谱：千万级实体及关系知识，支持逻辑与关系的知识推理；多轮对话：开放域聊天与垂域技能超过5轮的上下文对话能力 | 天气、翻译、藏头诗、笑话、歌词、计算、域名信息/备案/收录查询、IP查询、手机号码归属、人工智能聊天 |
| 价格 | 需要注册账号，可以申请5个机器人，未认证账户每个机器人只能回3条/天，认证账户每个机器人能用100条/天。 | 完全免费！不用注册，不用申请key，拿来就用！|
| 体验感受 | 回答准确率高，交互体验良好 | 功能单一，体验不良|

## 十、API的使用价格
1. 图灵机器人
需要注册账号，可以申请5个机器人，未认证账户每个机器人只能回3条/天，认证账户每个机器人能用100条/天。

2. 自然语言处理-问答系统
[基于知识图谱的问答系统](https://blog.csdn.net/weixin_44023339/article/details/99965656)
[Github项目地址](https://github.com/liuhuanyong/QASystemOnMedicalKG)

####可能还会用到的次重要API估价
3. 文本分析
- ![文本分析](https://gitee.com/EdisonQXF/API/raw/master/images/%E6%96%87%E6%9C%AC%E5%88%86%E6%9E%90%E6%8A%A5%E4%BB%B7%E8%A1%A8%E5%A4%B4.png)
- ![文本分析](https://gitee.com/EdisonQXF/API/raw/master/images/%E6%96%87%E6%9C%AC%E5%88%86%E6%9E%90%E6%8A%A5%E4%BB%B7%E8%A1%A8.png)

4. 语言理解
- ![语言理解](https://gitee.com/EdisonQXF/API/raw/master/images/%E8%AF%AD%E8%A8%80%E7%90%86%E8%A7%A3%E6%8A%A5%E4%BB%B7%E8%A1%A8.png)

## 十一、API使用风险评估
本产品需要收集用户的个人信息，例如受伤部位、有无出血等，这些数据属于个人十分隐私的数据，然后再通过人工智能数据分析等操作。这些数据需要得到足够的安全保障。可以在建立数据库的时候加入区块链技术也可以通过加密用户数据，使用的时候需要得到用户的授权，比如输入用户个人身份证号、人脸识别等。

## 十二、竞品分析
1. 竞品对象——春雨医生App

2. 竞品的战略定位分析
春雨医生搭建了自诊和问诊系统，定位于用户的诊前咨询，主要解决用户在“身体不适”到“去医院”之间的需求，这被春雨医生定义为“轻问诊”。

3. 竞品的产品结构
![春雨医生](https://gitee.com/EdisonQXF/API/raw/master/images/%E6%98%A5%E9%9B%A8%E5%8C%BB%E7%94%9F.png)

4. 竞品的差异化分析
 4.1 区别
- 春意医生竞品：春雨医生主要是通过大数据的方式分析病情只分轻度的和严重的，轻度给出基本建议，严重的病情会练习在线医生，与医生进行线上沟通。这是春雨医生主打的“轻问诊”模式。

 4.2 缺点
- 问诊类和咨询类APP由于线上咨询和线下医疗的分离，大多只停留在初步问诊阶段，难以提供有效的医疗服务。

**结论：相比春雨医生，我们的Sport-doctor(运动医生)产品加入了人工智能，结合大数据的数据分析可以提供更权威的数据分析结果，并且能够为用户得到推荐治疗方案后的疑惑问答等提供良好的用户体验。春雨医生的“轻问诊”我们可以学习，加入在线医生问诊的功能，并且在此基础上不断完善。**

## 十三、该产品未来的发展路线构想
定好产品的主要发展功能、领域，然后不断完善，基础到成熟，之后再逐渐发展附属功能，最终成为一个成熟的产品。

#####  (一）产品的更新迭代过程
- **V1.0**
   1. 实现自然语言处理的，问答系统数据库；
   2. 实现人工智能机器人功能，满足基本的智能操作、交流需求；

- **V2.0**
   1. 人工智能数据库逐渐完善、丰富减少失误率；
   2. 增加在线预约门诊、医生预约等功能；
   
- **V3.0**
   1. 人工智能数据库完善趋向成熟，几乎没有失误率；
   2. 产品用户流量增多，根据用户需求完善周边附属功能；

#####  (二）产品可能涉及的功能范围
- 在线智能机器人根据用户数据分析病情，给出治疗方案
- 用户选择运动损伤处理方案并解答相关医疗健康疑惑等
- 医生在线问诊，通过审核的医生会在线解答病患病情

#####  (三）产品的盈利模式
1. 广告盈利
> 本小程序是医疗健康类小程序，后期成熟后可以招募药店、医院、医学院等相关医疗机构、医疗教育行业的广告，从中获得广告费盈利。
2. 平台入驻盈利
> 前期做好宣传，可以选择邀请友商入驻，利用大的流量ip吸引用户，初定为免费的不收费，待到成熟，有一定的流量、知名度、访问度之后可以向入住的平台收取摊位费、推广费等。
3. 发展周边
> 我们可以选择发展医疗周边，可以是友情赞助商提供的医护用品，例如口罩、棉签等等。待到资金到达一定的程度，我们可以选择发展自己的ip，并利用其流量和知名度做成周边商品，吸引用户进行购买，从而获得资金收入。
4. 增加付费的高端项目
> 我们还可以为高端人群客户定制化服务，在保障普通用户的正常使用功能外，再开发更高端的服务，吸引特定的人群进行升级服务，消费升级。

#####  (四）产品的业务模式
![业务模式]()

### 所使用的API功能链接
- [自然语言处理](https://lbs.amap.com/api/webservice/guide/api/direction)
- [图灵机器人](http://www.turingapi.com/scene)
- [Azure认知服务](https://azure.microsoft.com/zh-cn/services/cognitive-services/)

#### 一句话版本
现代大学生体育运动参与度越来越高，而且大学体育课的种类也丰富多样，发生运动损伤的情况也无可避免的时有发生。所以通过这样的一款专门为解决运动损伤需求的App
#### 1分钟版本
现在国内外都有很多的健康管理类App，特别是受2020年疫情的影响，更是掀起了热潮。但是针对男大学生运动损伤的健康类App并没有出现。此款App针对男大学生运动损伤处理这一痛点，主要运用问答系统和图灵机器人，对运动损伤提出具有可行性的处理方案。这款App实用性高，市场潜力是很大的，因为有人工智能的加入，未来的发展潜力也是巨大的。
![健康管理App](https://gitee.com/EdisonQXF/API/raw/master/images/App%E8%81%9A%E5%90%88.jpg)
所以本产品是通过API人工智能技术将产品功能有机结合。通过问答系统加上图灵机器人，构建强大的数据库能够匹配对应的运动损伤的处理方案。加入文本分析等自然语言处理，让图灵机器人与用户的交流更有交互体验，丰富情感化需求。还可以通过知识付费、广告周边等方式获得收入盈利。
