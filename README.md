<h2 align="centre">What is nanometer-message?</h2>

 
* 适用于更好的消息提示或者小组件。

<h2 align="left">Claims the melon<MessageBox有哪些功能？ ></h2>
 
* 简单易用

* 更好的消息提示，四种场景选择，可以使用自定义

* 添加到您的UI库用于完善

<h2 align="left">Install</h2>
Install with script:

```bash
<script src="index.js"></script>
<link rel="stylesheet" type="text/css" href="style.css" />
```

Install with npm:

```bash
npm i nanometer-message
```

<h2 align="left">Documentation</h2>

* Common ant es6:



```js  
var Message = require('nanometer-message')
<link rel="stylesheet" type="text/css" href="style.css" />
 Message({option})
```
* 类似于vue:

```js
import Message from 'nanometer-message';
import "nanometer-message/lib/style.css"

Vue.prototype.$meessage = Message
```

<h2 align="left">API</h2>

* The pattern of object customization has been added. The previous way of use remains the same, which requires more flexible use of option


```bash
 Message(String, messges)
```


```bash
 Message({option})
```
|Name|Description|
|:--:|:----------|
|[type]|The current state of the message. [success,warning,info,error]|
|[animationDuration]|Buffer animation duration(The default for 3 seconds)|
|[egoClass]|CSS state customization|
|[context]| Message content.Please note: this is a must|
|[destroy]| A callback after the message has disappeared |




<h2 align="left">Contact the author</h2>

* 邮件联系(2636098325@qq.com)
* 提交issues
* 请访问 github地址 <a herf="https://github.com/webvs2/Nanometer"> https://github.com/webvs2/Nanometer</a>
* 请访问 网址<a herf="https://webvs2.github.io/Nanometer/">https://webvs2.github.io/Nanometer/</a>





<h2 align="left">Grateful to members</h2>

 各位帮我完善的,我会展示这里的



