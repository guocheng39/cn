## 短信模板 <br>

![短信样例](../../../../image/Text-Message/dx-014.png)<br><br>

最终用户收到的短信样式如下: <br>
[京东云] 您已成功注册成为京东云会员<br><br>

在短信模板TAB页, 点选 ‘创建模板’, 如下图<br>
![创建模板](../../../../image/Text-Message/dx-015.png)<br><br>

根据提示内容填写模板内容, 点击提交后等待运营人员进行签名审核<br><br>

国内文本短信分为三个类型:<br>
* 验证码短信<br>
* 通知短信<br>
* 推广短信<br><br>

**验证码短信**<br>
![验证码](../../../../image/Text-Message/dx-016a.png)<br>
验证码短信示例:<br>
```【京东云】欢迎您注册成为京东云用户，验证码为：${1}，5分钟内有效！```<br>
其中:<br>
```【京东云】``` 为短信签名<br>
```欢迎您注册成为京东云用户，验证码为：${1}，5分钟内有效！``` 为短信模板<br>
```${1} ``` 为模板变量<br><br>

验证码短信只支持一个变量<br>
模板内容必须含验证码，注册码，校验码，动态码这 4 个词其中之一<br>
必须包含使用平台，失效时间，用途其中之一<br><br>

**通知短信:**<br>
![通知](../../../../image/Text-Message/dx-016b.png)<br>
通知短信示例:<br>
```【京东云】我是京东小哥${1}, 您的生鲜订单${2}即将送达, 请您准备收货!```<br>
其中:<br>
```【京东云】``` 为短信签名<br>
```我是京东小哥${1}, 您的生鲜订单${2}即将送达, 请您准备收货! ``` 为短信模板<br>
```${1} ${2} ${3} ```为模板变量<br><br>

不允许出现相同的变量名称<br>
不支持变量与变量、短链接与变量直接组合的格式<br><br>

**推广短信:**<br>
![推广](../../../../image/Text-Message/dx-016c.png)<br>
推广短信不支持加变量<br>
不能发送贷款/借款/中奖/抽奖类短信，不支持金融理财/房产通知类短信（验证码除外）<br><br>

提交审核后您可以在短信模板列表页查看审核状态, 审核通过的短信模板可用于短信发送<br>
![查看状态](../../../../image/Text-Message/dx-017.png)<br><br>

注: 验证码短信和通知短信需要通过API或SDK调用. <br>
详细请参考 https://docs.jdcloud.com/cn/?act=3 <br>
API和SDK所需要的相关信息在概览页获取 <br>
![ak](../../../../image/Text-Message/dx-017a.png)<br><br>
