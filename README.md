## 目前实现了以下功能

 + 机器人群聊@回复
 + 机器人私聊回复
 + 好友添加自动通过
![image](https://user-images.githubusercontent.com/68322685/206850729-901ae567-08e3-4221-8acb-bf32bfaa53c2.png)

## 注册openai

chatGPT注册可以参考[这里](https://juejin.cn/post/7173447848292253704)
注册完之后登录`https://chat.openai.com`获取token

![image](https://user-images.githubusercontent.com/68322685/206850650-dc93c18b-b11a-4c55-8f77-a71da9559fbf.png)

## 使用

修改`config.json`把里面的`你的token`替换成前面获取的`Bearer `后面的`token`字符串复制进来

````bash
# 启动项目
$ ./chatgptWechatbot-macos-arm64

# 出现下面信息如果没弹浏览器二维码就复制链接到浏览器打开，使用你要自动回复的微信xxxx
访问下面网址扫描二维码登录
https://login.weixin.qq.com/qrcode/QdXGWxxxx==

# 登录成功之后，用户私聊你那个机器人微信或者群里艾特你机器人微信都能请求chatgpt获取回复。
````
