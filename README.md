# bili弹幕姬朗读模块
## 建议把这个只当成一个朗读,欢迎模块,配合别的弹幕姬的显示模块吧

效果演示视频:https://www.bilibili.com/video/av771953100

(免费版测试中)使用前需先申请微软文本转语音秘钥(https://azure.microsoft.com/zh-cn/services/cognitive-services/text-to-speech/#overview)

教程请搜索"无需信用卡怎么用微软azure"(正常情况下需要visa/万事达银行卡,本人visa信用卡不行,提示不支持预付卡,但是万事达借记卡可以)

![image](https://user-images.githubusercontent.com/73635883/184405056-7f3dd22a-223d-4daa-a16f-e5d7cf65ee87.png)

需要在运行目录下修改'peizhi.xml'

具体修改方法配置里有,
打开自己看注释就行

下一个版本已完成:1修复部分表述错误.2检测到房间号错误时不再闪退

等待实现:[已发布测试版,有道api,缺点语音质量稍差]无需秘钥使用(预计稳定性较差,可能有时候念不出)

目前问题:1.浏览器大声朗读方案:占据前台窗口,需要双机(或者虚拟机)直播

--------2.第三方软件方案:成功率更低,三分之一概率合成失败

--------3爬虫方案:严重bug,各种error
