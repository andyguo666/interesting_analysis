# 发现身边最近疫情监控
## 功能
- 输入自己的住址
- 发现与最近疫情的距离，如果小于某一阈值，通知给自己
- 通知方式：邮件、短信

## TODO
- 通过腾讯坐标转换
- 通过twilio发送短信
- 通过celery实现任务异步


## 参考资料
1、疫情地图，数据来源[CBNData](https://z.cbndata.com/2019-nCoV/index.html)
![image.png](https://i.loli.net/2020/02/11/SesZNrU1PfiJD5t.png)

![image.png](https://i.loli.net/2020/02/11/iY4X5GQOCnRovpu.png)

文案：
```
湖北省鄂州市鄂城区汀祖镇 距离您定位位置 52.57 公里，曾出现 3 例新型冠状病毒肺炎确诊病例。确诊病例已收入定点医院救治，只要做好自身防护，无需过分担心哦
上海市浦东新区民乐城兰丽苑 距离您定位位置 31.72 公里，曾发现新型冠状病毒肺炎确诊病例，尚未公布确诊人数。确诊病例已收入定点医院救治，只要做好自身防护，无需过分担心哦！
你所定位的 江苏省苏州市 目前已有 80 起新型冠状病毒肺炎确诊病例。离你最近的在 江苏省苏州市昆山市中航城花园，距离你 2.64 公里。1 公里内没有病例，3 公里内有 2 个病例。确诊病例已收入定点医院救治，只要做好自身防护，无需过分担心哦！
你所在的 安徽省黄山市 目前已有 9 起新型冠状病毒肺炎确诊病例。确诊病例已收入定点医院救治，只要做好自身防护，无需过分担心哦！
```
