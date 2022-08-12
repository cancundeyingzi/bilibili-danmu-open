# bili弹幕机器人
## 建议把这个只当成一个朗读,欢迎模块,配合别的弹幕姬的显示模块吧

效果演示视频:https://www.bilibili.com/video/av771953100

使用前需先申请微软文本转语音秘钥(https://azure.microsoft.com/zh-cn/services/cognitive-services/text-to-speech/#overview)

教程请搜索"无需信用卡怎么用微软azure"(正常情况下需要visa/万事达银行卡,本人visa信用卡不行,提示不支持预付卡,但是万事达借记卡可以)

![image](https://user-images.githubusercontent.com/73635883/184405056-7f3dd22a-223d-4daa-a16f-e5d7cf65ee87.png)

需要在运行目录下创建一个'peizhi.txt'(发行版无需创建,仅需修改)

第一行是微软语音的秘钥(俩秘钥随便写一个)

第二行微软语音的地区(看你创建项目创建在哪,推荐创建在东南亚)

第三行欢迎词的时间段总数,如图,8种欢迎词就写8

后面依次是时间段判断,前缀,和后缀

![image](https://user-images.githubusercontent.com/73635883/184302083-cb02bae5-90e0-4a7e-b2eb-9081e2675ce7.png)

![image](https://user-images.githubusercontent.com/73635883/184399844-e0d9eece-07e7-4053-8702-bf1f7bb56426.png)


0-8

10800-11   
8-11点对应第一条上午好xxx谢谢你来到直播间

18000-13        
11-13点对应该吃午饭了xxx谢谢你来到直播间

32400-17                            
.......

39600-19

54000-23

72000-4

82800-7

86400-8
