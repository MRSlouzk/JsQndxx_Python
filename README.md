# 江苏省青年大学习自动学习Python脚本

每周都要被团支书催着做青年大学习，虽然网上也有很多办法可以秒过，但是还是得打开微信公众号然后点击最新一期的青年大学习。我就想能不能有办法每周自动帮我完成呢？本着能copy就不自己动手的原则，我在github逛了半天，结果并没有发现江苏省青年大学习自动学习相关代码，无奈只好自己写一个了。

---

### 实现原理

对于这种功能一般都和网络请求相关了，简单来说就是带着你的信息去发送请求即可。

### 准备工作

+ 抓包

  既然要发送请求，那肯定要知道向哪发送请求，我通过Charles抓包发现每次的请求江苏省青年大学习的接口是https://service.jiangsugqt.org/youth/lesson?s=/youth/lesson&from=singlemessage&isappinstalled=0

+ 分析

+ 写代码

