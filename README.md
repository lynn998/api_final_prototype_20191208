

<div align="center">
  <h1>:whale2: 项目名称：安防放大镜 :whale2:</h1>
  <p>基于meitu_API的 安防放大镜 APP</p>

</div>

## ✨Product Requirement（产品说明文档）

\*

| Title | Content |
| --- | --- |
| Target release(发布日期) | 2019/12 |
| Epic(史诗名称) | 安防放大镜 |
| Document status(文档状态) | 进行中 |
| Document owner(文件主人) | 刘炜豪 |
| Designer(领头的设计师) | 刘炜豪 |
| Developer(领头的开发者) | 刘炜豪 |
| QA(领头的测试者) | 刘炜豪 |

## ✨Catalogue（目录）
|产品的PRD设计|原型设计|机器学习之API的输出入展示
|---------- | --- |---------- 
|[PRD1-加值宣言](#chapter1) |[产品功能架构](#chapter14)|[API输入与输出](#chapter18)
|[PRE2-核心价值](#chapter2) |[流程图](#chapter15)|[API1.使用水平](#chapter19) 
|[PRD3-用户痛点宣言](#chapter3) |[全局说明](#chapter16)|[API2.使用比较分析](#chapter20)
|[产品简介](#chapter4) |[原型1.交互及界面设计](#chapter17) |[API3.使用后风险报告](#chapter21) 
|[产品背景](#chapter5) |[原型2.信息设计](#chapter17)|[API4.加分项](#chapter22)
|[产品目标](#chapter6) |[原型3.原型文档](#chapter17)|---------- 
|[用户画像](#chapter7) |[Axure交互及设计低保真原型](#chapter17) |---------- 
|[用户需求](#chapter8) |[原型4.口头操作说明 ](#chapter17)|---------- 
|[情景假设](#chapter9) | --- |---------- 
|[问题与解决](#chapter10) | --- |---------- 
|[考虑后不完成之项](#chapter11) | --- |---------- 
|[PRD4-人工智能概率性与用户痛点](#chapter12)| --- |---------- 
|[PRD5-需求列表与人工智能API加值](#chapter13)| --- |---------- 


⭐️加值宣言

&quot;安防放大镜&quot;帮助警察、安保人员等进行嫌疑犯的追踪，皆在为提高安防原始照片放大后的人像清晰度，以提高对嫌疑犯的身份识别能力。

⭐️核心价值

- .对象为警察、安保人员等，拥有清晰度不足的照片并需要放大图片、进行人像抠图、图片清晰化，从而实现身份识别的需求的人员。

- .使用的方式简单，前后对比，一键完成。

⭐️核心价值与用户痛点

视频监控最为明显的&quot;痛点&quot;是——看不清嫌疑犯的样子。看清，就是核心价值。

⭐️人工智能概率性与用户痛点

自主测试——看图说话

![嫌疑犯1](https://images.gitee.com/uploads/images/2019/1208/181448_e1291168_1648161.png)
![嫌疑犯2](https://upload-images.jianshu.io/upload_images/9746829-9cb60b9381ee1ad2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![嫌疑犯3](https://upload-images.jianshu.io/upload_images/9746829-b68ebdd6b6e90ba3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

其中，监控中的图像质量修复，使得图像像素增加；切割背景，有效降低复杂环境对图片的后期使用影响；使用人脸特征识别，获取年龄、情绪、眼睛、人种、单双眼皮信息；使用人脸关键点识别，获取脸部轮廓信息，从而整体上获取到嫌疑犯的基本信息特征，对嫌疑犯身份识别起到一定作用。

⭐️需求列表与人工智能API加值

\*

| # | User Story（用户案例） | Importance（重要性） | Notes（笔记） | 技术 |
| --- | --- | --- | --- | --- |
| 1 | 嫌疑犯2，原始图像画质低、光线不足、黑白、有反光，需要形成嫌疑犯画像  | 极其重要 | 核心功能 | 图像修复、人脸提取、人脸属性判断、人脸关键点提取 |
| 2 | 嫌疑犯3，原始图像为抠图，画质低、光线稍足、有反光，需要形成嫌疑犯画像  | 极其重要  | 核心功能 | 图像修复、人脸提取、人脸属性判断、人脸关键点提取 |
| 3  | 嫌疑犯1，原始图像较为清晰，国际作案、识别年龄和人种 | 极其重要 | 核心功能 | 图像修复、人脸提取、人脸属性判断、人脸关键点提取 |
| 4 | 嫌疑犯2，原始图像画质低、光线不足、黑白、有反光，需要描述嫌疑犯当时姿态动作 | 重要 | 非核心功能 | 肢体关键点检测 |

⭐️产品架构图
![产品架构图](https://images.gitee.com/uploads/images/2019/1208/181448_e2eabd64_1648161.png)

## ✨PART2 原型

点击进入交互体验：http://lynn998.gitee.io/api\_final\_prototype\_20191208

点击进入仓库下载源文件：https://gitee.com/lynn998/api\_final\_prototype\_20191208

——————————————————————————————————————

其中

⭐️原型1.交互及界面设计

交互及界面设计：在PRD文件中是否有说明且原型是否有做到：交互及界面设计的某个核心交互环节使用了人工智能的加值 **（已实现）**

⭐️原型2.信息设计5%

信息设计：在PRD文件中是否有说明且原型是否有做到：信息设计的某个核心信息或设计使用了人工智能的加值 **（已实现）**

⭐️原型3.原型文档5%

原型文档：多少程度上有提供MVP可交互的原型文档，供它人在Github上下载使用 **（已实现）**

![image.png](https://images.gitee.com/uploads/images/2019/1208/181448_2a0230a2_1648161.png)
![image.png](https://images.gitee.com/uploads/images/2019/1208/181449_c9ce603a_1648161.png)
![image.png](https://images.gitee.com/uploads/images/2019/1208/181449_e2e71536_1648161.png)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-68f66f17e86003d7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-170e90a5cedf0f45.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-cfa1ad0c980899d2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-ce0ce50df8db108b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



⭐️API 产品使用关键AI或机器学习之API的输出入展示

⭐️API1.使用水平

完整代码请点击：https://gitee.com/lynn998/api\_final\_prototype\_20191208/blob/master/AI\_API\_demo.ipynb
实例代码
# 人脸属性检测
```
import requests
import base64
import json

def Face_attribute_detection():
    image = open('/Users/lynn998/Desktop/嫌疑犯DEMO/嫌疑犯1证件照后.jpg', 'rb')
    image_read = image.read()
    image_64_encode = base64.encodestring(image_read).decode('utf-8')
    ss = json.dumps(
    {
        "parameter": {
            "rsp_media_type": "jpg",
        },
        "extra": {},
        "media_info_list": [{
            "media_data": image_64_encode,
            "media_profiles": {
                "media_data_type":"jpg"
            },
            "media_extra": {
            }
        }]

    }
    )

    AIBeauty_url = "https://openapi.mtlab.meitu.com/v1/facedetect?api_key=0_FKVGvWYLNUaPMOlkhlzJExz15NI4i5&api_secret=P1MKgX3GsRkY8EBd3abkEXUutdPh9HYB"
    print(ss)
    response2 = requests.post(AIBeauty_url, data=ss)
    ss2 = json.dumps(response2.json())
    print(ss2)
    print(response2.status_code)
```
if __name__ == "__main__":
    Face_attribute_detection()

![image.png](https://upload-images.jianshu.io/upload_images/9746829-6921e439d314564f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-8572c7c29b480117.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-1eea0e22f3cf2888.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-46fd329edb45637a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-28d36758f5f76b99.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/9746829-f681712bc59a2135.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


⭐️API2.使用比较分析

美图AI开放平台：https://ai.meitu.com/index

美图AI使用文档：https://ai.meitu.com/doc?id=145&amp;lang=zh&amp;domain=OUT

\*

| 适用性评估 | API | 美图 | 腾讯 | 旷世 |
| --- | --- | --- | --- | --- |
| 成熟度 | 图片质量分析 | ✨✨✨ | 无产品 | 无产品 |
| 图像画质修复 | ✨✨ | 无产品 | 无产品 |
| 图像背景去除 | ✨✨ | 无产品 | 无产品 |
| 人脸属性检测 | ✨✨ | ✨✨ | ✨✨✨ |
| 人脸关键点检测 | ✨✨ | ✨✨ | ✨✨✨ |
| 肢体关键点检测 | ✨✨✨ | 无产品 | ✨✨✨ |
| 性价比 | 总体 | 综合解决方案，性价比高 | 产品欠缺 | 产品欠缺 |
| 准确度 | 人脸属性检测 | ✔️✔️✔️ | ✔️✔️ | ✔️✔️✔️ |
| 人脸关键点检测 | ✔️✔️✔️ | ✔️✔️✔️ | ✔️✔️✔️ |
| 价格 | 人脸属性检测 | ✔️✔️ | ✔️✔️ | ✔️✔️ |
| 人脸关键点检测 | ✔️✔️ | ✔️✔️ | ✔️✔️✔️ |
| 优点 | 总体 | 拥有整体解决方案 | 部署方便 | 准确度高 |
| 缺点 | 总体 | 价格相较贵 | 产品欠缺 | 产品欠缺 |

⭐️API3.使用后风险报告5%

使用后风险报告：在PRD文件中是否有说明且提供连结证据，所使用的API类别的现在及未来发展性，如API市场竞争程度丶输入输出限制丶定价丶及可替代的程序库（改用自己开发的代码及数据库而不用API）等等

\*

| 使用后风险报告 | 说明 | 连结证据 |
| --- | --- | --- |
| API市场竞争程度 | 与人脸识别API的竞争程度高  | 新闻稿https://baijiahao.baidu.com/s?id=1611368355899522622&amp;wfr=spider&amp;for=pc |
| 输入输出限制 | 美图AI试用限制为5000/次正式购买提供三种选择方案，可选择按月无限量付费 | 详细请浏览其官方网站注册登录查看https://ai.meitu.com/index  |
| 定价 | 目前查询到美图AI为2000/月，针对少量高QPS用户 | 详细请浏览其官方网站注册登录查看https://ai.meitu.com/open-platform-admin |
| 可替代的程序库  | 图片质量分析 | 未查询到可替代的程序库 |
| 图像画质修复 | 未查询到可替代的程序库 |
| 图像背景去除 | 第一替代程序库：https://github.com/AKSHAYUBHAT/ImageSegmentation第二替代程序库：https://github.com/susheelsk/image-background-removal第三替代程序库：https://github.com/rorodata/background-removal |
| 人脸属性检测 | 第一替代程序库：https://github.com/unicodeveloper/face-detection第二替代程序库：https://github.com/binLearning/face\_det\_attr第三替代程序库：https://github.com/ZHUXUHAN/Keras\_Face |
| 人脸关键点检测 | 第一替代程序库：https://github.com/CMU-Perceptual-Computing-Lab/openpose第二替代程序库：https://github.com/qiexing/caffe-regression第三替代程序库：https://github.com/sksq96/cnn-face-recognition第四替代程序库：https://github.com/soheillll/Facial-Keypoint-Detection |
| 肢体关键点检测 | 第一替代程序库：https://github.com/SpikeKing/Human-Pose-Estimation第二替代程序库：https://github.com/renjingc/PosematchAndRecognition |

⭐️API4.加分项

**完整代码请点击：https://gitee.com/lynn998/api\_final\_prototype\_20191208/blob/master/AI\_API\_demo.ipynb**

 

 

 

 
