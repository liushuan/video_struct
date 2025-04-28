# video_struct
视频结构化，车牌识别，车辆识别，车型识别，人形识别
联系方式：547691062@qq.com 微信:18781975483
# 安防监控、智慧交通 视频结构化（车辆+行人）实现方案
 目前视频结构化已经应用到安防监控中，主要是对视频中的人员、车辆目标进行结构化处理，能够提取出人员的年龄、性别、衣服颜色、是否戴眼镜等属性信息，车辆的车牌号码、车型、车辆颜色、挂件等属性信息。基于提取的属性信息可以进行人员、车辆的进一步比对分析，确定违法犯罪人员和违法车辆。
 ![image](https://github.com/user-attachments/assets/1bc9e3b9-e9ce-4f1c-aef8-8820d71e9146)
平安城市、智慧城市等的火热建设下，视频监控和视频应用的需求在不断增加，视频监控行业市场规模保持快速增长。
庞大的监控视频数据加大了安防运维成本。如公共安全监控中主要关注的视频信息为：人员、车辆、行为。而传统视频监控中，如需获得某区域相关信息，则需从公共监控视频中百万级的目标库中(对应上千小时的高清视频)进行查找，查找速度慢，检索效率低。
随着算法不断升级与革新，公共安全领域对视频结构化需求的越来越旺盛，视频结构化现已大规模地得到应用。结构化的视频数据可以极大提升视频查找的速度，并能解决视频传输中的痛点问题——带宽压力，还可大幅降低视频存储容量问题。
# 1.目标检测算法实现
检测视频中出现的 （车辆/行人） 包括类型 {行人、汽车、公交车、卡车、三轮车、摩托车}

![image](https://github.com/user-attachments/assets/e5714f66-8f72-4c8a-a8c7-28c3d42d4951)
# 2.车牌识别算法实现
使用OCR技术完成基本的车牌识别功能

![image](https://github.com/user-attachments/assets/dbdb72e8-f313-4310-91fa-f8bdacfd8576)
# 3.车型分析方案
分析车型，包括 粗类别 （120类） / 细类别（1500类）

![image](https://github.com/user-attachments/assets/71c8a9ce-b901-4ce8-b848-e1317b0db0eb)
# 4.行人结构化分析

![image](https://github.com/user-attachments/assets/26055cd2-718b-409e-a3b4-2a4497daf898)
基于以上4点完成算法闭环
目前我们已完成模块包括
人脸、人形属性分析：人脸识别 人脸跟踪 人脸角度、性别、年龄、人脸特征点信息、人脸清晰度、活体检测、人脸朝向，运动方向、骑自行车、骑摩托车等分析。
车辆、车牌属性分析：车型、车颜色、车头朝向、车牌识别。
# 实现效果图
目前的实现效果图


![image](https://github.com/user-attachments/assets/962f562a-5046-4b14-9f5e-aa7b0951b748)

![image](https://github.com/user-attachments/assets/11b12f8f-142c-4afb-af9d-cb2bbcc353fb)

![image](https://github.com/user-attachments/assets/b1c5dc76-e351-4616-bf86-13c4cf05afe5)

![image](https://github.com/user-attachments/assets/5e8c523d-d543-4140-a1ee-25cf0b426e41)

![image](https://github.com/user-attachments/assets/731ed83f-3865-4b88-8df9-d564681ebb88)

![image](https://github.com/user-attachments/assets/412d58c7-682d-4177-b9c8-dea209afd283)

![image](https://github.com/user-attachments/assets/7776f90b-8746-4cb7-abd9-8ecd95ee3eb0)
