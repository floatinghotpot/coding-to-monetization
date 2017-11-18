### 从编码到变现：程序员财务自由之路

From Coding to Monetization：Programmer's Financial Freedom Approach

[英文版本 / English Version](./README.md)

从屌丝程序猿 | 到财务自由
---|---
![屌丝程序猿](demo/poor-programmer.jpg) | ![大富豪](demo/richman.jpg)

### 目录

* [前言](#前言)
* [定位](#定位)
* [基础篇](#基础篇)
  * [语言与工具选择](#语言与工具选择)
  * [Hello, World!](#hello-world)
  * [单机版APP](#单机版APP)
  * [加个广告条](#加个广告条)
  * [注册广告账号](#注册广告账号)
  * [验证地址和设置收款信息](#验证地址和设置收款信息)
  * [发布APP](#发布APP)
  * [广告收益的计算](#广告收益的计算)
* [进阶篇](#进阶篇)
  * [需求是根本](#需求是根本)
  * [用户体验](#用户体验)
  * [哪种广告最适合](#哪种广告最适合)
  * [哪家广告商最靠谱](#哪家广告商最靠谱)
  * [营销你的产品](#营销你的产品)
  * [联网版APP](#联网版APP)
  * [云服务](#云服务)
* [高级篇](#高级篇)
  * [数据分析](#数据分析)
  * [广告优化](#广告优化)
  * [支付与内购](#支付与内购)
  * [社交营销](#社交营销)
  * [广告投放](#广告投放)
* [附录](#附录)
  * [互联网营销常用术语](#互联网营销常用术语)
  * [如何发布 APP 到 Apple AppStore](#如何发布-app-到-apple-appstore)
  * [如何发布 APP 到 Google Play Store](#如何发布-app-到-google-play-store)
  * [如何发布 APP 到 360 应用商店](#如何发布-app-到-360-应用商店)
  * [如何用 Google Analytics 做用户数据分析](#如何用-google-analytics-做用户数据分析)

### 前言

这本书，是写给程序员看的。

这并不是关于一门编程语言，也不是关于一种设计模式，更不是关于如何评估工程量、如何做项目管理。

这本书是关于：变现（monetization），通俗的说，就是赚钱。

作为程序员，你一定花了大量的时间去学习，掌握了若干种编程语言、用过数十种开发工具。为了设计稳定灵活的架构，你也认真学习和掌握了各种设计模式；为了提高工作效率，你也用了各种成熟的框架以及自动化测试的工具；总之，通过学习，你成为了一个牛B的程序员。

甚至，你也积累了管理的经验，主动学习了项目管理的理论知识、各种研发组织模式，也许会进阶到管理岗位，成为研发团队的负责人或者经理人。

在大部分的情况下，作为程序员或者研发团队，你按照项目经理 或者 产品经理给的需求，进行需求分析、架构设计、模块划分、接口设计、编码实现、测试、提交版本。这些环节，毫无疑问，是做研发的程序员最为熟悉的流程。

不幸的是，你日常所关注的，仅仅只是研发环节。接受需求，交付版本，这就是产品经理或者甲方让你干的事情。很多在研发领域侵淫多年的研发大牛，也往往并不熟悉软件怎样能够直接带来经济回报。绝大多数的开发者，仅仅关注研发这个环节，甚至仅仅关注在编码这个环节，这是非常局限的。

事实上，研发环节，再加上销售、收款、推广、用户支持、维护，这才是软件产生经济回报的完整闭环。

然而，软件怎样直接带来经济回报，这方面的技术文章或者书籍并不多见。这也是我为什么会选择这个角度，作为本书下笔的核心内容。

这本书是关于，如何从编码、到如何接受付款，以及如何获取用户。手把手，教你每一个步骤。

一旦你掌握软件如何变现的能力，你会更加关心用户反馈、关心市场需求、关心产品质量，因为这些都会为你带来更好的经济收益。实现财务自由，也就并不遥远了。

如果你觉得本书的内容有所帮助，请点赞支持。

### 定位

既然是谈赚钱，类似于外包这种把有限的生命折算成man hour来卖钱的苦逼方式，我们暂不讨论。

考虑到人力、时间、成本等因素，我们也暂时不讨论运营级、或者企业级的大型系统。研发周期长、投入大、需求复杂，也超过个人和小团队的掌控。

在移动互联网时代，以个人或者小团队，实现赚钱、甚至创造奇迹的故事，屡见不鲜。

真实案例 1: 
[Flappy Bird](https://zh.wikipedia.org/wiki/Flappy_Bird) 传奇，一个花2-3天开发出来的小游戏，在短短几周时间席卷全球，并获得了每天 5 万美金的广告收益。这无疑有偶然、运气的成分，但至少这是有概率发生的事情。

真实案例 2:
我认识一个波兰的老外，用做网页的技术，做了个并不复杂的计算器，大概也就是按照百分比计算下小费之类的。在欧洲好几个国家的应用商店上财务类APP，排名前几，通过广告条变现，赚了不少钱。

真实案例 3:
我几年前在一家开发保险软件的公司工作。 公司发展得相当好，管理层试图上市。 然而，直到今天，它们还没有能够起飞和上市，因为商业模式与外包模式太接近了，而不是产品模型或平台模式。 我以前的两位同事离开了这家公司，成立了一家初创公司，在手机上开发一个短视频APP，成为一个短视频社区平台。 前几天，在经过三年的创新和努力之后，他们以10亿美元的估值被今日头条收购了。他们的名字叫Musical.ly，你可以在应用程序商店的顶部列表中找到它。

你可以找到其他类似的成功故事，从移动应用程序或游戏中成功的赚到钱。 稍微留意一下，你很可能从朋友圈听说过一些，或者可以从互联网搜索一下，这样的故事不胜枚举。

在这本书里，我们要探讨的是，集中非常有限的时间、精力，聚焦到非常狭窄的需求领域，开发移动应用 APP、小游戏，发布到全球应用商店、获取用户、并实现盈利。

也许你是技术的大牛，掌握了数十种编程语言、设计模式、前端到后端的全栈开发能力。然而，并不是每项技术，都能够实现快速赚钱的。最艰深、最有趣的技术，未必是最容易赚到钱的技术。有时候，我们要做最容易扩展的架构。有时候，我们要选择最快速开发的技术手段。

也许你是刚入门的菜鸟，只会做做网页什么的。那也没有关系，赚钱真正需要的编程技术，其实也可以非常简单。只是有一点，需要什么知识，我们就恶补什么知识。由于技术日新月异，程序员必须是最善于学习的群体。

### 基础篇

### 语言与工具选择

开发 APP 的语言与工具，通常与平台密切相关。
* 如果是 iOS，那通常是 Objective C，开发工具是苹果推出的 [Xcode](https://developer.apple.com/xcode/) （开发工具仅运行于 Mac）。
* 如果是 Android，那通常是 Java，开发工具是 谷歌推出的 [Android Studio](http://developer.android.com/tools/studio/index.html)（开发工具有跨平台版本）。
* 如果是 Windows Phone，那就是 C#，开发工具是 微软推出的 [Visual Studio](https://www.visualstudio.com/en-us/visual-studio-homepage-vs.aspx)（开发工具仅运行于 Windows）。

除此之外，还有一些跨平台语言与工具，对于开发者更加友善，可以开发一次，多平台打包发布：
* 可以开发游戏与APP的 HTML5，以 javascript 作为主要的开发语言。
* 用于开发游戏的 [Cocos2d-X](http://www.cocos2d-x.org/)，用的是 C++ 作为主要的开发语言。
* 用于开发游戏的 [Unity3D](http://unity3d.com/) IDE 以及集成的 MonoDevelop，用的是 C# 作为主要的开发语言。
* 微软收购的 [Xamarin](https://www.xamarin.com/) 以及赞助的开源项目 [Mono](http://www.mono-project.com/)，用来开发 APP，以 C# 作为主要的开发语言。

在下文的教程中，我们选择最简单的 javascript 作为后续介绍的主要开发语言。实际上，它也是 github 上最为活跃的语言。它可以用来开发：
* 运行于浏览器内的 Web网页；
* 运行与内嵌浏览器的 单页WebApp；
* 基于 [nodejs](https://nodejs.org/) 的命令行工具；
* 基于 nodejs 的网络云服务；
* 基于 [cordova](http://cordova.apache.org/) 技术的，混合(hybrid) APP。
* 基于 [react-native](http://www.reactnative.com/) 开发 native UI体验的 APP。
* 甚至，也能够开发出桌面应用，例如 Adobe Brackets 代码编辑器。

因为它可以同时用来开发前端和后台，代码逻辑也可以用来前后端复用，从而降低技能门槛和开发成本。开发环境也要求非常低，只要有个友好的代码编辑器，有个浏览器可以用来运行和调试，就可以了。

以下是用 javascript 来做开发的所需要的环境和工具：
* Chrome浏览器，自带开发者工具 和 javascript 控制台，用来运行和调试。
* [Adobe Brackets](http://brackets.io/) 文本编辑器（如果你习惯 [Sublime Text](http://www.sublimetext.com/) 或者 [Atom](https://atom.io/) 或者 [Visual Studio Code](http://code.visualstudio.com/)，也没问题）
* iMac台式机，巨大的27寸屏幕，视野不受限制；Mac OS X命令行非常强大方便，通过 [MacPorts](https://www.macports.org/) 或者 [Homebrew](http://brew.sh/)，Linux 上有的命令行工具或者 library 都基本支持。
* Xcode（只有 Mac 版本），要调试 iOS APP，有台 iMac电脑或者 MacBook笔记本电脑，这也是必备的。
* Android Studio，用来调试 Android APP。

如果你习惯了 Windows 也没有一台 Mac，会稍微麻烦一点。不过也是有方法的，有一些专门提供编译、打包的云服务，例如 Adobe PhoneGap Build，或者 Intel XDK，我们后面会介绍如何使用。

### Hello, World!

用 javascript 开发前端，其实需要的是 3 项相关的语言：HTML / javascript / CSS。
* HTML 负责内容
* javascript 负责逻辑
* CSS 负责渲染表现

以下是一个简单的例子：
```html
<!-- index.html -->
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<title>Hello</title>
<script type="text/javascript" src="main.js"></script>
<link rel="stylesheet" href="main.css"/>
</head>
<body>
<h1>Hello, World!</h1>
</body>
</html>
```
```javascript
// main.js
console.log('hello, world!');
```
```css
/* main.css */
body {
  width: 100%;
  height: 100%;
  padding: 0px;
  margin: 0px;
}
h1 {
  color: blue;
  padding: 40px;
  margin: 10px;
  border: 1px solid gray;
  display: inline-block;
}
```

用 Chrome 浏览器打开它，于是我们看到如下的展示：
* 上面的浏览器主窗口，显示了 HTML 的内容，并且用 CSS 指定的格式和效果进行了渲染。
* 下面打开 Chrome 的 console 窗口，则显示了 javascript 调用 console.log() 输出的调试信息。

![HelloWorld](demo/helloworld.png)

用 HTML5 / javascript 做开发，入门就是这么简单。

如果需要开发出高质量的 APP，需要熟练掌握 HTML/CSS 和 javascript，尤其是 HTML5 / CSS3，掌握 HTML DOM 以及 javascript 的一些常见库，例如 [jQuery](https://jquery.com/)，等等。这里有一些免费的入门教程：
* [HTML 系列教程](http://www.w3school.com.cn/h.asp)
* [JavaScript 入门教程](http://www.w3school.com.cn/js/index.asp)
* [JavaScript 高级教程](http://www.w3school.com.cn/js/index_pro.asp)

通过这些教程的学习，你能够做到：
* 一个简单的 index.html 页面；
* 一个统一的 main.css 文件，能够对界面元素的表现加以控制和调整；
* 一组 javascript 文件，能够通过对 HTML DOM 的访问，实现内容的动态展示和切换。

对于作为程序员的你，这根本不是什么难的事情。

### 单机版APP

下一步，我们要把这样一个简单的网页程序 (web app)，变成一个手机上的 APP。准确的说，它应该是叫 Hybrid APP，即混合程序。因为它的外面是 native app 封装了一个 webview，里面运行的是 我们写的 web app。

我们需要用到 cordova 技术框架。它原本是 Adobe 公司收购的一个小团队开发的产品，被重新命名为 [PhoneGap](http://phonegap.com/)。后来 Adobe 将其开源，并捐赠给 Apache 基金会，然后被称为 [Apache Cordova](https://cordova.apache.org/)，现在已经成为一个非常流行的技术框架，也得到很多商业公司的追捧，除了 Adobe 之外，Intel、微软、IBM 等公司也都推出了支持 Cordova 的产品。

Cordova 技术框架提供了一个命令行的工具，是用 nodejs 开发的。

我们首先要装 [nodejs](https://nodejs.org/en/)，安装之后，会提供 2 个基本的命令：
```bash
$ which node
/usr/local/bin/node
$ node -v
v4.2.1
$ npm -v
2.14.7
```
* node --- 负责 javascript 程序的编译／解释／执行。它是基于谷歌开源的 Chrome V8 引擎的，基于事件驱动、不阻塞 IO模式运行，轻量而高效。
* npm --- NodeJs Package Manager, 安装包管理器。所有的 nodejs 包都是用 npm 来下载和安装（你也可以用它来发布你自己的包到 npm 库）。

接下来，用 npm 安装 [cordova](https://cordova.apache.org/)：
```bash
$ npm install -g cordova
$ which cordova
/usr/local/bin/cordova
$ cordova -v
5.4.1
```

用 cordova 创建一个项目：
```bash
# 格式为：cordova create <目录名> <APP ID> <APP名字>
$ cordova create temp com.rjfun.demo Demo
```

然后编译，并在 iOS 模拟器中运行这个项目：
```bash
$ cd temp
$ cordova platform add ios
$ cordova build ios
$ cordova emulate ios
```

于是可以看到 iOS 模拟器被启动，然后 APP 运行：

![Cordova iOS](demo/cordovaios.png)

或者你也可以把 iPhone 用 USB 线连接到 Mac，然后用这个命令安装、启动刚刚编译的 APP：
```bash
$ cordova run ios --device
```

现在运行的是 Cordova 自带的 Demo 工程。打开 Cordova 项目，可以看到这样的目录结构：

![Cordova Proj](demo/cordovaproj.png)

接下来，删去 www 目录下的内容，用我们前面写的 index.html, main.js, main.css 替换，并略作修改：
```html
<!-- index.html -->
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />

  <!-- 下面的部分，是为了兼容移动设备的屏幕 -->
  <meta http-equiv="Content-Security-Policy" content="default-src 'self' data: gap: https://ssl.gstatic.com 'unsafe-eval'; style-src 'self' 'unsafe-inline'; media-src *">
  <meta name="format-detection" content="telephone=no">
  <meta name="msapplication-tap-highlight" content="no">
  <meta name="viewport" content="user-scalable=no, initial-scale=1, maximum-scale=1, minimum-scale=1, width=device-width">

  <!-- cordova 在 APP 编译打包时自动生成，用来初始化 cordova 框架代码 -->
  <script type="text/javascript" src="cordova.js"></script>

  <title>Hello</title>
  <script type="text/javascript" src="main.js"></script>
  <link rel="stylesheet" href="main.css"/>
</head>
<body>
<h1>Hello, World!</h1>
</body>
</html>
```

```javascript
// main.js
console.log('hello, world!');

// 当 APP 初始化完成，会触发 'deviceready' 事件，我们可以调用 cordova 框架以及插件提供的 API 和功能
document.addEventListener('deviceready', function(){
  console.log('deviceready');
  
  // TODO: 开始我们 web app 的业务逻辑
});
```

```css
/* main.css */
body {
  width: 100%;
  height: 100%;
  padding: 0px;
  margin: 0px;
  background-color: silver;
}
h1 {
  padding: 40px;
  margin: 30px;
  background-color: yellow;
  color: blue;
  border: 1px solid gray;
  display: inline-block;
}
```

重新运行 cordova 项目（会自动编译、安装、运行）：
```bash
$ cordova emulate ios
```

于是，可以看到 Web App 在 iOS 模拟器中运行了：

![Hello World Cordova](demo/helloworldcordova.png)

做个最简单的APP，其实也很简单，是不是？！

### 加个广告条

作为程序员，我们毫不怀疑，你可以通过掌握的 HTML/CSS 以及 javascript 编程能力，提供一些有趣、有用的功能。

接下来，我们要给这个 APP 加上变现（monetization）的功能，即实现赚到真金白银。

变现最简单的方法，就是加上广告条，例如谷歌的AdMob。
* 通过展示广告，用户对有兴趣的广告点击，浏览产品、或者安装其他的 APP。
* 投放广告的个人／公司（简称广告主，Advertizer）会支付广告费给谷歌。
* 而谷歌则会将其中的一部分，支付给发布广告的个人／公司（简称发布商, Publisher）。
* 谷歌在其中扮演的角色，则称之为广告平台（Ad Platform）、或者广告中介（Ad Network）。

Cordova 框架的技术架构，是 Web APP 加上一些通用的插件，提供手机特定功能的访问、与第三方系统的集成。

我们通过插件 cordova-plugin-admobpro 来实现与谷歌 AdMob 的集成。这是基于谷歌 AdMob SDK 开发的一个插件，也是目前变现插件中最流行、最容易使用的。通过它，只需一行 javascript 代码就可以完成对 SDK API 的调用。

现在让我们往 cordova 项目工程中加入插件。

```bash
$ cordova plugin add cordova-plugin-admobpro
```

然后修改 main.js，在 APP 初始化完毕时，我们加几行代码。

```javascript
// main.js
console.log('hello, world!');

// 当 APP 初始化完成，会触发 'deviceready' 事件，我们可以调用 cordova 框架以及插件提供的 API 和功能
document.addEventListener('deviceready', function(){
  console.log('deviceready');
  
  // 在 APP 初始化完毕时，在屏幕下方创建一个广告条
  if(AdMob) AdMob.createBanner({
    adId: 'ca-app-pub-6869992474017983/4806197152', // 需要到 AdMob 官方网站注册用户，并创建广告单元 Ad Unit Id
    position: AdMob.AD_POSITION.BOTTOM_CENTER, // 展示在屏幕下方中央
    overlap: false, // 不要覆盖 Web APP 的内容
    isTesting: true, // 展示测试广告，在正式发布时，去掉这行
    autoShow: true // 广告资源就绪时，自动开始展示
  });
});
```

重新运行 cordova 项目（会自动编译、安装、运行）：
```bash
$ cordova emulate ios
```

于是，可以看到 Web App 在 iOS 模拟器中运行了：

![AdMob Banner](demo/admobbanner.png)

看，屏幕下方的广告条展示出来了。

这里只是仅供调试用的测试广告。我们需要到 [AdMob官方网站](https://apps.admob.com/)注册用户，并创建广告单元（Ad Unit Id），并用来替换掉 代码中 adId 后面的这串数字。并在发布的正式版本中，去掉 `isTesting:true` 这行代码。

### 注册广告账号

下面我们就介绍，如何注册账号，如何创建广告单元，如何设置银行收款信息。

由于价值观方面的原因，谷歌的网站基本上都是被隔离在中国大陆局域网之外，通常是无法访问的。需要通过 VPN 等科学上网的方式才能够访问。如果你不知道如何科学上网，可以写邮件给我，单独讨论这个问题，这里暂不展开。

访问谷歌AdMob官网（ https://www.google.com/admob/ ），注册新账号。

![AdMob Site](demo/admobsite.png)

注册完成之后，登陆 AdMob 网站（ https://apps.admob.com/ ），点击菜单“获利”，点击左上角的红色按钮“＋通过新应用获利” 添加新APP：

![AdMob New App](demo/admobnewapp.png)

然后创建横幅广告：

![AdMob New Banner](demo/admobnewbanner.png)

即可获得广告单元 ID，将其 copy 到源代码中：

![AdMob Ad Unit ID](demo/admobadunitid.png)

### 验证地址和设置收款信息

注册账号之后，广告单元进入APP投放实际使用，即可积累广告收益。

要收到谷歌支付的广告分成，还有 2 个步骤要完成：
* 验证地址。谷歌会生成一个 PIN 码，打印在卡片上，邮寄到你的通信地址。
* 设置收款信息。可以是 西联汇款 或者 银行账号。

不过，刚注册的账号还不允许设置这个信息。只有你的累计广告收入达到基本的门槛（目前是 10美金），谷歌才会允许进入设置支付信息的环节。谷歌通过这个方法，可以过滤掉大量的无效账号。

#### 验证 PIN 码：

![Verify PIN](demo/verifypin.png)

点击“立即改正此问题”，进入 PIN 码输入界面。

![Verify PIN](demo/verifypin2.png)

验证 PIN 码这个过程比较缓慢，通常需要 2-4 周的时间。所以如果显示了最近生成 PIN 码的日期，就耐心等待吧。收到 PIN 码之后，就将其输入上面这个框，提交验证。

#### 设置收款信息：

![AdMob Payment](demo/admobpay1.png)

![AdMob Payment](demo/admobpay2.png)

![AdMob Payment](demo/admobpay3.png)

等这 2 个步骤设置完成，当产生广告收益的时候，谷歌就会在每个月的月末，计算当月的广告收益，然后在下个月的 20日左右支付给你。

### 发布APP

我们完成的 APP，要被用户安装使用并产生收益，还缺少一个重要的环节：发布 到应用商店。
* 如果是 Android APP，通常是 Google Play Store。中国大陆用户通常访问不到，则可以选择发布到大陆的一些应用商店，例如 360、豌豆荚 等等。
* 如果是 iOS APP，则是发布到苹果 AppStore。

这里我们以苹果 AppStore 为例，来说明如何注册开发者账号，并发布 APP。

访问苹果开发者网站（ https://developer.apple.com/ ），并注册登录。要在 苹果AppStore发布应用，需要支付每年 99 美金的年费，对于个人开发者、公司开发者，这个费用都是一样的。

![Apple Developer](demo/appledev.png)

注册成功的开发者，需要下面几个步骤，才能将 APP 发布到 AppStore：
* 生成开发者数字证书，用于安装包的签名。
* 为你的 APP 创建 APP ID，如果不涉及内购，也可以用 “*” 或者 “com.rjfun.*” 作为一个通用的 APP ID，在多个 APP 中使用。
* 为你的 APP 生成 Provisioning Profiles，并下载到 本地用 Xcode 打开、管理。

然后用 Xcode 打开 Cordova 项目里的 XXX.xcodeproj 工程文件，编译并存档（Archive）。成功存档的 APP 包，才能提交到 AppStore 进行审核。

APP 提交前，需要到 iTunesConnect （ https://itunesconnect.apple.com/ )，准备、发布和管理你的 APP。

![iTunes Connect](demo/itunesconnect.png)

创建新的 APP，加上名字、介绍、图标、定价等信息，并将其设置为准备提交的状态，然后就可以通过 Xcode 中的 Organizer 将成功存档（Archive）的安装包提交到 AppStore 进行审核了。

![Xcode Organizer](demo/xcodeorganizer.png)

苹果审核 APP 的流程大约 1 周左右的时间。如果审核通过，就可以在 AppStore 里面看到你发布的 APP 了。

### 广告收益的计算

当用户在设备中下载、安装APP并运行的时候，就会从谷歌的广告服务器请求正式的广告内容，并用于展示了。

你可以登陆谷歌 AdMob 网站，查看每天的广告展示量、点击率、以及产生的收益。这个网站也提供了非常强大的报表功能，可以根据国家、广告单元、时间段，显示非常详细的报告。谷歌在 AppStore 上发布有一个 AdSense 的 APP，你可以安装这个 APP，每天查看你的 AdMob 收益。

每次用户对感兴趣的广告进行点击，就会产生广告收益。大部分的广告投放，是按照点击次数计算费用的，即所谓的 CPC 广告。

在计算广告收益的时候，有几个常见的基本术语：
* CPC（Cost Per Click，每次点击费用），大约是 US$ 0.06 ~ 1.0;
* CTR（Click Through Rate，展示点击率），大量统计的结果大约是 1%;
* CPM (Cost Per Mile, 每千次展示费用），通过 CPC 和 CPR 也能够推算出 CPM，大致范围是 US$ 0.5 ~ 5。

每次点击的价格，根据广告投放的价格不同而不同。全球不同国家由于经济水平不同，也存在很大的差异。例如，
* 在美国，一次广告点击可能产生 0.2 美元的收益;
* 在巴西，也许只有 2 美分，相差 10 倍。
* 而日本，广告点击的收益是相当高的。

下面是一组数据的对比：

美国 | 巴西
---|---
![USA](demo/datausa.jpg) | ![Brazil](demo/databrazil.jpg)
日本 | 德国
![Japan](demo/datajapan.jpg) | ![Germany](demo/datagermany.jpg)

如果我们按照 CPM （每千次展示费用）1美元 来估算，每天 10万次广告展示，大约可以产生 $100美元现金收益。按照 6.45 的汇率计算，一个月30天（包括周末和节假日！），大约可以产生的收益是 ¥19,350。

而在上海，5年经验的、技术能力还不错的程序员，薪资大约也就 15,000 左右。如果你做的 APP，每天能够有 1万个用户使用，基本上产生的广告收益和现金流，就可以达到一个程序员的工资水平。

我认识一个巴西人，他用 HTML5 技术实现的小游戏，简单，但是非常有趣。每天的活跃用户大约是 10万，广告收益已经超过每个月 15万，从而实现了财务自由。

### 进阶篇

### 需求是根本

前面我们介绍了如何为 APP 增加了变现（monetization）的能力。但要真正获得可观的收益，还必须得有足够多的用户。也就是说，你必须开发出足够好的 APP，能够真正解决用户的问题，才会有更多的用户使用、更高频度的使用。

如何能够开发出更受用户欢迎的 APP 呢？其实这不是一个编程问题。

也许你是一个技术的大牛，但是最艰深、最牛X的技术，开发出来的软件产品未必是受到用户欢迎的产品。有时候，你用了一种其实比较简单的技术，但是真正关注了用户的痛点，解决了用户关心的问题，很可能你的产品就会受到用户的欢迎，创造出口口相传的良好口碑，在社交网络得到自然传播。

我推荐一本书，《需求-缔造伟大商业传奇的根本力量》，作者是亚德里安•斯莱沃斯基。

以下是某些创业成功者的推荐：

> 这是一本好书，每个创业者和每个公司管理者都值得一看，甚至公司中的每个人都应该了解和体会其中的概念。书中给出了一些创造需求的模式，这对读者是非常有价值的，我们需要好的理念，但我们更需要可以践行理念的方法。这两点本书都做到了，非常值得一读，特荐之。
——孙陶然 ，拉卡拉支付有限公司创始人、董事长兼总裁，《创业36条军规》作者

> 每一个抱怨的背后都隐藏着一个未被满足的需求，而每一个需求的背后必然隐藏着一个不可忽视的市场。其实任何产品，在一开始满足了用户的功能性需求以后，就应该着手升级到精神层面，用户拒绝麻烦，用户需要安慰，这看起来跟利润无关，但是对不起，它跟你的市场有关。你不去满足，创业者就会自己去进行开拓性满足。那么等待你的，或将是个生死存亡的巨大危机。因此，请一定重视麻烦所带来的希望，而不是去抵触他们的抱怨。这正是《需求》给我们带来的最有价值的东西。
——杜子建，华艺传媒创始人，社会化媒体营销研究者，畅销书《微力无边》作者

### 用户体验

为什么苹果手机卖得贵，依然热卖？无疑它是以优秀的用户体验取胜的。如果你看过《乔布斯传》，你可以知道，苹果手机的诞生，其实是解决了传统手机难于使用的痛点。

自然我们在手机上开发的 APP 或者 游戏，也必须要高度关注用户体验，并且把它放到战略重点的位置上来。手机 APP，不追求功能的强大、齐全，可以只做一个小小的功能，但是要切实关注用户的需求点、并提供优秀的用户体验。

一个相当典型的例子是这款《手电筒》APP，就是打开手机的 LED灯泡，用来临时照亮黑暗。

![Torch APP](demo/torchapp.png)

这款 APP 的用户已经超过好几亿，自然收益也是极其可观。

评价的数量超过600万人次，它的用户是这样写的：
* Jennifer Baylis: 易于使用。#1 最棒的手电筒APP！非常容易使用，打开很快！
* Kitty Davis: 我正是需要这样一个手电筒 APP。
* Dennis Castello: 它正是做到了需要它做的事，而且做的真的很好。
* Joseph Low: 易于使用。轻松地让它干活！强烈推荐！

### 哪种广告最适合

在移动广告领域，存在多种形式的广告，并且也在不断的发展。
* banner Ad，横幅广告
* interstitial Ad，插屏广告
* native Ad，原生广告
* reward video Ad，奖励视频广告
* IAP (in-app purchase) Ad，内购广告

哪种广告适合你的 APP，需要很好的权衡用户体验和收益之间的关系。如果广告展示不当，或者展示过于频繁，影响了用户体验甚至招致用户反感，就本末倒置了。

横幅广告 | 插屏广告
---|---
![iPhone Banner](demo/iphonebanner.jpg) | ![iPhone Interstitial](demo/iphoneinterstitial.jpg)

这两种广告是最为基本和经典的，各有千秋。相对来说，横幅广告只占用屏幕下方的一小片空间，可以一直滚动展示，默认的是每 60 秒更换一次广告内容。优点是不太会影响用户界面和体验，缺点则是因为不太起眼，不容易引起用户的注意和点击。

插屏广告则是全屏的，在特定的时间弹出，更能够吸引用户的眼球和点击。也正是因为这个原因，插屏广告的点击收益比横幅广告要高 5 倍以上，比较推荐使用。

使用插屏广告的时候，要特别注意弹出的时间，千万不要打断用户的连续操作和游戏体验，否则不仅不会引起用户的点击，还会引起用户的反感。最佳做法是将其放在 2个阶段之间的过渡时机，例如游戏的一关刚刚结束，弹出插屏广告，然后再继续下一关。

通过插件 cordova-plugin-admobpro，要展示插屏广告也是非常简单的，只需要 2 行 javascript 代码就可以完成了。其中一行代码负责准备广告资源，另一行代码负责展示。示范代码如下：
```javascript
// 在游戏启动时或者进行中，开始准备插屏广告，通过后台线程下载广告资源
if(AdMob) AdMob.prepareInterstitial({
  adId: "__ad_unit_id_here__", 
  autoShow: false
});

// 在游戏关卡结束时，调用 API 进行插屏广告的展示
if(AdMob) AdMob.showInterstitial();
```

以上这 2 种广告，是最容易使用的广告形式，集成到 APP 中的工作也最为容易。

原生广告（native Ad），就是将广告内容以较为和谐的方式，展示在APP自身的内容之间，不会显得过于突兀和突然，这是对用户体验影响最小的一种广告形式。 Facebook AudienceNetwork 和 Flurry 比较早就推出了原生广告，不过谷歌 AdMob 对此持谨慎态度，仅仅在部分开发者中进行 beta 试用。

奖励视频广告(reward video Ad)，是谷歌新推出的一种广告。就是鼓励用户看完广告视频，然后开发者在游戏中或者 APP 中给予某种虚拟物品的奖励。在以前的广告推广中，谷歌并不支持在用户接受广告方面给予鼓励的行为，甚至将对点击广告给予奖励的做法定为违规的行为。因为这很可能违背用户本身的兴趣、造成虚假无效点击。新的奖励视频广告方面，谷歌采取了相对灵活和务实的态度。不过这方面的广告视频来源，基本上都是通过广告中介的方式来自于其他的广告网络。

内购广告（IAP House Ad）是一种新颖、创新的广告形式，应用内购买广告可让用户直接在应用内购物。因为需要和支付系统、或者谷歌Play Store结合起来，所以仅在 Android 系统支持。通过内购广告，应用开发商可在以下方面获益：
* 通过在同一款应用中实施广告投放和应用内购，可以最大程度地增加您的收入和用户的生命周期价值。
* Google 会自动帮助您确定哪些用户有可能购买应用内购商品，并向其余用户展示普通的付费广告。
* 不需要开发自己的应用内购支持系统，也不需要在应用中加入应用内购支持代码。
* 利用不同的自家内购广告，可以轻松定位用户群体中的各种细分受众群。通过将应用内购广告与 AdMob 受众群体构建工具结合使用，可以向高消费群体投放价格高的应用内购商品，而向其他用户展示价格低的商品。

如果要尝试原生广告、奖励视频广告、内购广告，请移步 Google [AdMob 官方文档网站](https://developers.google.com/mobile-ads-sdk/)，进行深入研究，学习如何使用。

### 哪家广告商最靠谱

因为移动广告领域的利润可观，移动广告平台的发展也是非常快的。过去的这些年，也发生了不少并购案。例如 Google先后收购了 DoubleClick 和 AdMob，Flurry 被 Yahoo! 收购，MobFox 被 Matomy 收购，Millennial Media 被 AOL 收购。

![Top Ad Networks](demo/topadnetworks.jpg)

通常广告平台会提供：
* 接入广告系统的 SDK；
* 注册、登录和管理广告的系统；
* 接入指南、例程、FAQ；

各种移动广告平台的相关介绍，可以通过搜索活着其他不同的渠道去了解（例如 StackOverflow.com），并可以有选择性的进行尝试。

以下是我试用过的一些广告平台：
* Google AdMob
* Facebook AudienceNetwork
* Yahoo! Flurry
* MobFox
* Apple iAd
* MoPub
* Millennial Media
* InMobi
* OpenX
* Smart AdServer
* ... ...

使用下来比较满意的有 AdMob, Facebook AudienceNetwork, Yahoo! Flurry, MobFox。尤其是 AdMob，非常值得推荐。

AdMob之所以最值得强烈推荐，主要有这样一些突出的优点：
* 广告填充率高（基本上在 98% 以上，有个别国家略低于90%），因此可以充分利用用户流量。毕竟广告是谷歌公司的主要业务和利润来源，其广告客户遍及全球，这也不足为怪了；
* 付款及时，每个月的月底结算，次月 20日支付；
* SDK 非常稳定，接入文档以及参考代码易于使用，并且有不同语言的文档和系统界面；
* 报表系统功能强大、易于使用，可以通过不同的维度进行数据分析；
* 有专门的 APP 可以用来跟踪收益；
* 有专门的技术支持人员，有官方支持的技术论坛，专门解答 SDK 接入方面的技术问题；
* 定期会组织一些宣讲、培训活动，也定期有线上视频讲座；
* 客户服务非常到位，非常的耐心和友善，我和他们也基本上一直保持联系。

由于谷歌在各个领域的卓越创新、一贯的优质服务，在开发者中有良好的口碑。

而基于 AdMob SDK 开发的 cordova-plugin-admobpro 这款插件，不仅把 Objective-C / Java / C# 的原生 API 封装为统一的 javascript API，而且更加简单易用，只需 1－2 行代码即可完成广告展示。这款插件在 Cordova 全球社区也广受欢迎，是使用率最高的变现插件。以下是插件的下载趋势曲线图：

![AdMob Download Trend](demo/admobprodltrend.png)

Facebook 的 AudienceNetwork 也挺不错。Facebook 不仅仅是最大、最活跃的社交媒体，也提供各种相关 SDK，包括广告用的 AudienceNetwork。其开发者网站为：https://developers.facebook.com/docs/audience-network 。
* Facebook 的 广告填充率(Fill Rate)没有 AdMOb 那么高，大约在45～75% 之间。
* Facebook 付款也很及时，也是在每个月的 21日左右支付上个月的广告收益；
* Facebook 的 SDK 更新非常频繁，大约 2 周左右就会发布一个新的版本，因此如果有什么 bug 修复也很快。不过更新的频度实在有点高，有时候有点跟不上的感觉。相对来说，谷歌 AdMob 的 SDK 更加稳定一些；
* 管理界面和报表系统也比较清楚易用，一目了然。报表系统没有 AdMob 的那么强大和灵活，貌似仅有英文界面，看上去是下面这样的。

![Facebook AudienceNetwork](demo/fbaudnet.png)

Flurry 是一家被 Yahoo！收购的移动广告公司，其官方网站是 http://www.flurry.com/ 。其主要的产品有 2 个，一个是数据分析(Flurry Anlytics)，一个是广告系统（Flurry Ads）。
* Flurry SDK 接入也还算比较容易，报表系统中规中矩。就是网站访问稍微有点慢，比较花时间。
* 付款略慢，在广告收益产生的 60天之后才付款。
* 值得一提的是，Flurry 是比较早支持原生广告的（Native Ad）的。

MobFox 是一家欧洲的移动广告公司，总部位于奥地利。曾经它的 CEO 联系过我，希望能够就某项产品达成合作。后来因为收购事宜暂停，再后来，再后来就知道 MobFox 被 Matomy 收购，项目合作的事情就没有下文了。这家公司还是不错，付款也比较及时。虽然号称是欧洲最大的移动广告公司，并且全球位于 Top 10，但和 Google、Facebook 这样的巨头比起来，在全球范围内的影响力实在有点弱。

Apple 的 iAd，只是在 iOS 系统上进行投放。由于 iPhone 的市场定位和定价明显要高于 Android 系统，也就决定了 iOS 用户有较强的购买力，所以 iAd 广告的点击回报比较高，也就不言而喻了。不过如果你开发的 APP 需要同时投放 iOS 和 Android 系统，用 AdMob 管理起来相对容易一点。也可以通过 AdMob 的广告中介（mediation）功能，把部分流量通过 iAd 进行展示，从而使得广告收益的利益最大化。

像 OpenX 和 Smart AdServer 仅对欧美的签约客户开放，并不针对全球用户和开发者。只是曾经有美国和欧洲的客户在 GitHub 上看到我的开源项目，特意找到我要求我定制产品，通过项目合作的方式，我才得以了解和熟悉。不过因为不对全球开发者，所以也无法推荐使用。

至于 MoPub，它的 SDK 的是在 GitHub 上开源的，这是它与众不同的地方。不过也正是因为这一点，其文档和 SDK 接入就要稍微麻烦一些。必须要把这些 SDK 从源代码编译成 jar 和 framework，然后才能在自己的项目中使用。

Millennial Media（简写为 mMeida)，其 SDK Demo 的美观度做得不错，不过客服和技术支持的响应实在不敢恭维。曾经碰到过技术问题，通过 Web Form 提交了问题，一直没有得到过答复，所以我后来也就懒得用它了。

另外像 Charboost、TapJoy 等等广告平台，也或多或少的接触过。不过精力有限，没有逐一进行具体的试用。Charboost 是 2011 年才创业的广告公司，只专注在移动游戏领域，2014年被 VentureBeat 指数报告定为 Top 10 的移动广告公司。通过 Chartboost 发布的广告，点击收益比较不错，不过反过来说，也就是广告投放、获取用户的成本是比较高的。我所认识的专门做重度游戏、专门投放海外市场的朋友，通过 Facebook 和 Chartboost 投放广告用得比较多。

上面介绍了不少移动广告平台，完全是个人经验和主观体会，有兴趣的可以自行尝试。

### 营销你的产品

（待续）

### 联网版APP

### 云服务

### 高级篇

### 用户数据分析

### 广告优化

### 支付与内购

### 社交营销

### 广告投放

### 附录

#### 互联网营销常用术语

Part1 最基本的名词

ROI：Return On Investment的简称。一般而言on这个词是应该小写的，所以ROI似乎应该是RoI，不过大家都约定俗成了，不必较真。ROI是典型的追求效果类的营销的关键指标。在中国的互联网营销，这个值一般指的是，我花了多少钱推广费，直接产生了多少的销售。比如花了1万元做SEM推广，直接卖了3万元的货。ROI会被认为做到了3（即3:1）。这一点与财务计算上的ROI是不同的，后者是利润和投入的比值，但在互联网营销上，大家没有把利润作为R，而是用GMV。关于GMV是什么，本文的下篇有。:)

Impression：意思是“曝光”，也被称为“展示”或“显示”，是衡量广告被显示的次数，一个广告被显示了多少次，它就计数多少。比如，你打开新浪的一个页面，这上面的所有广告就被“显示”了1次，每个广告增加1个Impression。

Click：点击，是指互联网用户点击某个广告的次数。

CTR：Click Through Rate，点击率。就是用click除以impression的比例。

CPM：Cost Per Mille，这次实际上省略了impression，全文应该是cost per mille impression。Mille是千的意思，在英语中它只跟着per一起用，即per mille，就是汉语的“每千……”的意思。所以CPM是每千次展示的成本。

CPC：Cost Per Click，每次点击的成本。

Ads：就是广告（名词）的英语复数啦。Ads = Advertisements。如果是“做广告”（动词），应该用Advertising。

SEM：Search Engine Marketing的简称。就是搜索引擎营销。不过在中国，SEM其实仅仅指PPC。但是SEM事实上是PPC和SEO的统称。PPC和SEO是什么，下面有解释。

PPC：Pay Per Click的简称。一般是特指搜索引擎的付费竞价排名广告推广形式，因为搜索引擎竞价排名只有一种收费方式，即按照点击付费。虽然也有其他广告形式也是按照点击数量来进行收费，一般不被称为PPC，而被称为CPC，即Cost Per Click。为什么？似乎是约定俗成。

SEO：Search Engine Optimization的简称。就是搜索引擎优化，特别指搜索引擎搜索结果自然排名的优化。所谓自然排名，就是不通过给搜索引擎付钱就能获得的排名。不花钱就能被搜索引擎排到前面当然是好事，但大家（每个网站）都这么想，所以要出头还挺难的。懂得这个领域的高手过去能挣很多钱，但今天SEO却越来越短时间内就出效果，所以想要通过SEO挣快钱越来越难。

Social：社会化，是social marketing（社会化营销）或者social media（社会化媒体）的简称，具体指二者的哪一个要看场合。社会化媒体，在中国过去是人人网、开心网之类，现在是微信、微博、图片分享类网站应用等。

WA：Web Analytics的缩写。就是网站分析。

DA：Digital Marketing Analytics的缩写。数字营销分析。

Part2 数据分析领域

Dimension：维度。维度是对一指一个事物的不同的方面、特征或者属性。这么说太抽象。简单说，人可以分成男人和女人，性别就是人的一种维度。或者汽车可以分为白色、黑色、红色等，颜色就是汽车的一种维度。维度是最基本的数据结构，任何一个度量（指标）必须要依附于一个具体的维度才有意义。比如说，我说visit=100，这没有任何意义。我说搜索引擎给我的网站带来的visit=100，就有了意义。搜索引擎流量就是维度（即流量来源）的具体的值（就如同男人是性别这个维度的具体的值）。

Metric（常用作复数，即Metrics）：通常翻译为度量或者指标，但是因为指标含义更宽泛，例如KPI或者benchmark都可能被称为指标，所以在我的培训中metrics都是用度量来表示，这样更严谨。度量绝大多数都能能用数字表示，比如汽车的速度，速度就是度量。课程中涉及到的度量分为两类，一类是计数度量（比如常见的PV、UV、访次、停留时间等）和复合度量（两个度量四则运算而成，常见的有转化率、跳出率、留存率、活跃率等）。另外有些度量使用布尔量表示，即是或非。度量必须依附于维度才有意义。

Unique：Unique是指排重（排除重复）。Unique很少单独用，常用在计数类度量的前面，比如unique visitor，指排除对同一个访问者重复计数之后的访问者数量——同一个人今天到网站一次，明天又来一次，不能就因此变成两个人，unique visitor仍然是1。Unique visitor通常可以简化为visitor，两个可以通用。Unique visitor和unique user是唯一的两个可以加不加unique都算unique的度量。另一个例子是unique impression，即同一个人多次看同一个广告，还是计算为1次。Unique impression和impression是两个不同的度量，因为后者不排重。

Benchmark：我在大学的时候这个词被翻译为“定标比超”，真是不明觉厉的感觉呀。Benchmark就是“可以作为对比的参照值”。我的很多客户会问，这个指标在行业中的平均情况是什么样呀？他们的问题可以同样表述为：这个指标在行业中的benchmark是多少？

Pattern：指某种会重复出现的模式或规律。Pattern常常用于发现用户行为上的某些趋同特征。比如，我们发现用户都喜欢在晚上10点到11点打开某个app应用，这就是一种pattern。如果我说发现了一个pattern，很兴奋，实际上的意思就是说我发现了一个规律。规律这词，几十年前就有了，pattern这洋文多有逼格呢……

Random：随机数，或者随机性。但是老外们也用它来形容“混沌”之类的意思。

Cohort：很难翻译，也很难形容，我暂且把它翻译成“队列”。跟Segmentation有点类似，但内涵要多一点，多点排队的意思。你懂的，课堂上讲清楚。Cohort一般是一种分析方法，所以一般不单独出来，而是跟analysis在一起，即cohort analysis。

Filter：过滤。过滤是指摒弃掉不需要的数据，只留下需要的。过滤都需要遵循一定的规则（这是废话），而且过滤掉的数据往往不能找回。过滤是一种常用的定位某个细分领域的方法，与细分（segmentation）的区别在于，segmentation是把总体分成并列的若干块（segment），而Filter则只保留符合规则的块，而丢弃其他不符合规则的块。

Segmentation：细分。这是我们最基本的方法，即把总体按照一定的规则分成并列的若干块。做了segmentation之后，每一个块就是一个segment。所以segmentation和segment不是同义词。Segmentation怎么用？怎么发挥最大价值？课堂上有很多案例。

Part3 互联网和互联网营销分析技术领域

Cookie：Cookie并没有真正的中文翻译，cookie是在你浏览网页的时候，网站服务器放在你电脑（或移动设备）的浏览器里面的一个小小的TXT文件。这个文件里面存储了一个标识你这个人的匿名的ID，以及一些与你访问的这个网站有关的一些东西，这样当你下一次访问这个网站的时候，cookie就会知道你又来了，并且记住你上次访问时候的一些状态或者设置。Cookie以及与cookie类似的东西是互联网营销的最重要技术之一，几乎所有识别人和标记人的工作都需要cookie及类cookie技术完成。在这次培训中会有详细的说明。

Deep link：没有汉语直接对应名词，我觉得直接叫“深链”好了，但不能叫做“内链”，后者是另外一个东西。Deep link历史悠久，过去把能够链接到网站的内页（即非首页的页面）的链接都称为deep link，但此后很快deep link这个词的意义就消失了，因为这样的链接实在太普通，都不需要用一个专用的名词来表述。但随着移动端的app的出现，deep link又“东(si)山(hui)再(fu)起(ran)”，特指那些能够跨过app首屏而直接链接到app的内屏（类似于网站的内页）的链接。嗯？如果这个app还没有安装过怎么办？这两期的公开课会专门讲。

Link Tag：Link Tag特指在流量源头的URL后面加上的标记，用来标明流量源头的名称和属性。最典型的link tag是Google Analytics的UTM格式的标记。目前已经成为标明paid media（花钱购买的广告流量）的标准配置。如何用好它，比你想的丰富，课堂上详解。

Heat map：热图。在一个图上标明这个图上哪些是获得更多关注的部分。关注可以是眼光，也可以是鼠标点击或者手指的指指点点。热图是做行为统计学研究的好可视化工具。大家都看得懂的东西，但用好则要水平。

JavaScript：简称JS，网站页面上的程序，能够让页面除了展示内容之外，还能实现更多的程序运行和功能。网站分析工具监测代码就是JS代码，将JS代码部署在你要监测的网页中，就可以把用户在页面上的互动访问行为不间断的发送到相应数据分析工具的服务器，从而获取想要的用户数据。

Attribution：归因。但是实际上这个词被翻译成“归属”更好。归因是指在多种因素共同（或先后）作用造成的某一个结果时，各种因素应该占有造成该结果的多大的作用，即“功劳应该如何分配以及归属于谁”。为解决归因的问题而建立的模型被称为归因模型，即attribution modeling。但我一直可惜这个词没有翻译好，翻译成归属模型或许更容易理解。

Path：路径。任何构成先后次序的一系列事件或行为都可以用路径来描述。路径分析（path analysis）也是较为常用的一种分析方法。

UID：是User Identification的缩写，即用户ID。

Bots：机器人。非人产生的流量，都被称为机器流量，即bots traffic。Bots是互联网虚假流量主要的创造者之一。

Spider：常翻译为蜘蛛，蜘蛛是一个自动程序，它的作用是访问收集整理互联网上的网页、图片、视频等内容。比如百度蜘蛛会将互联网的各种内容抓取回来并分门别类建立索引数据库，使用户能在百度搜索引擎中搜索到想要的内容。

IP：是Internet Protocol（网络互联协议）的缩写。IP地址就是给每个连接在互联网上的主机分配的一个地址，过去用于判断不同的访问行为属于同一个人（因为都是同一个IP记录产生的访问）。但由于各种动态IP和虚拟IP技术，用它判断用户人数已经很不可行。现在游戏领域也常常说起 IP，不过那是另外一个意思，intellectual property，知识产权，往往指的是著名的小说、影视、游戏等作品的人物故事等等。

Tracking：翻译为跟踪，就是数据分析工具跟踪用户各种行为的“跟踪”，用户所有的线上行为都可以被跟踪。监测这个词的“监”这个字，就是tracking。而测，则是measurement。所以监测这个汉语词，最准确的翻译就是tracking and measurement。监测需要用一定的技术手段实现，其中核心技术之一就是监测代码（tracking code），是一串可以发挥监测功能的程序（很多都是脚本语言编写，比如JavaScript语言）。

Pixel：本意是像素，但是在监测领域，是tracking code（监测代码）的同义词。

VAST：即Digital Video Ad Serving Template。一种实现视频程序化广告的基础性协议。目前是4.0版本。

Part4 流量与用户行为领域的名词

Bounce Rate：跳出率。会在课堂上简单介绍。

Referral：翻译为引荐来源。现实生活中，如果我推荐你使用了某个产品，或者我介绍你加入我们光荣的党，我就是引荐人（referral）。而在数字营销中，referral是指那些给我的网站带来了流量的其他网站，通常这些网站上会有链接到我的网站的链接。如果没有做特殊的标记（如使用link tag标记）或者不是特殊的流量源（比如搜索引擎），那么大部分的流量来源都会被监测工具记录为referral。

Retention：指用户的留存。如何让用户能够留存，是一个重要的课题。在这两期公开课培训中会跟大家介绍如何提升retention。

Engagement：没有特别合适的中文翻译，这个指标指的是用户在网站或APP上的交互程度或者参与度，可以由多个指标组合而成。比如一个网站有很多交互行为，包括下载文档、观看视频、咨询等，那么会根据每个交互的重要程度给每个交互行为赋值，用户每完成一个交互及赋予相应的数值，这样可以判断不同类别用户的交互程度以及不同页面的交互差异。Engagement和其他一些名词比如effectiveness、performance、acquisition等相似，都是泛指性的名词。

Session：session实际上和visit是一回事。本来，各类工具都是将用户的一次访问（网站）称为visit，但是随着app的普及，visit app听起来很别扭（因为我们都是use app），所以app也就不存在visit了，于是就用session代替。为了统一表述visit和session，有些监测工具把visit改称session。

Visit：即访问。指对用户对网站的访问，通常以30分钟为区隔。如果超过30分钟在网站上没啥动静，则一次访问结束。

Direct：翻译为直接访问，比如用户直接在浏览器输入网址访问，或者用户直接点击收藏夹里的网址进行访问，都会被记为直接访问。除了上述情况，从QQ客户端聊天窗口或微信客户端的链接直接访问网站的也会被记为直接访问。

Exit：退出，即用户离开网站或APP的行为，用户离开网站前的最后一个页面称为退出页（exit page），离开APP时所在的最后一个screen叫做exit screen。

Part5 策略与运营

Acquisition：泛指用户获取。在用户运营中使用的极为广泛，做任何产品的运营的第一步就是获取用户，比如在网页端的推广流量的获取、App推广中用户的下载等。

Goal：目标，是想要达到某种效果，每个网站都会有一些作为目标的交互，比如点击下载说明书、登录、注册、提交订单等。那我们就可以将这些设定为目标，那么这里引出另一概念：转化（conversion）。每完成一次上述的目标，就可以认定为完成一次转化。

KBR：Key Business Requirement。关键商业需求。是一个企业商业目标中最关键的。KBR决定了一个企业的其他目标，并且也决定了我们应该如何制定digital marketing的目标，以及针对这些目标选用什么样的指标或KPI。

KPI：Key Performance Indicator的缩写，译为关键绩效指标，是若干个用于衡量业务表现的最重要的度量。不同的商业目标，不同的业务，所对应的KPI不同。如何设置KPI是一门技术，也是一门科学。在这次的培训中也会做详细介绍。

Part6 互联网广告领域的名词

Display Ads：展示广告。展示广告主要指静态的图片广告、动画广告，以及富媒体广告（就是能互动一下的flash神马的）。这一广告形式与文字广告（就是文字链）和视频贴片广告形式是并列的不同类广告形式。

Banner：广义上是图片或者动画展示类广告的统称。这个词的含义源于上街游行队伍中拉着写有标语的大横幅，后来扩展到互联网广告商，并与display ads同义。

Pre-roll：也叫pre-roll ads，即前贴片广告。就是视频播放之前的长达10秒到丧心病狂的120秒的视频广告。

Content Feeds：信息流广告。信息流（主要是在社交网站和APP上）是内容并列排列自上而下像瀑布流一般，而在信息流中插入跟信息内容形态一样的广告，这种形式就是信息流广告。课堂上会介绍。

Native Ads：原生广告，通俗说是那些看起来就像网站或者app中正常内容一样的广告。原生广告容易和信息流广告混为一谈，但它们并不是一回事。原生广告可以采用信息流来实现，但不仅仅局限于此。

Reach：人群触达。如果做互联网广告，能够让广告触达到多少人是广告主关心的。触达实际上等同于unique impression，所以它不是动词，而是一个名词，一个用来记录广告触及到了多少人的计数度量。

Coverage：人群覆盖。跟触达非常类似，只是它的含义更模糊一些。往往用百分比来表示，例如，希望reach到的人群是1个亿，而实际reach到的是6000万，那么coverage大约是60%。Coverage不是一个度量，而是一个约定俗成的说法。

Viewability：广告可视性。过去统计广告的曝光的时候，不考虑广告是不是真的被人看到了，所以有些广告处在一个很长的页面的第二屏或者更后面的位置，而某个同学只看了第一屏就离开了的情况下，这个广告其实是根本没有处于屏幕中的，这个同学根本看不到这个广告。在不考虑viewability的情况下，这个广告仍然因此而有增加一次曝光（impression），而若考虑viewability，这个广告不增加一次曝光。

Pre-click：点击前阶段。指流量入口（尤其是广告）在被用户点击之前（含点击本身）的相关用户行为及对应的营销监测与分析体系。

Post-click：点击后阶段。指流量入口在被用户点击之后的相关用户行为即对应的营销监测与分析体系。

Fraud：作弊，也有更通俗的写法即cheating，但fraud特别指流量作弊。反作弊是anti-fraud。另一个与fraud类似的反面词汇是spam，即垃圾短信、垃圾邮件之类的骚扰垃圾信息。

Campaign：特别难找到准确对应的汉语名词，大意是一次有始有终的营销活动。有始，是指营销活动是从严谨的策划和详细的执行计划开始的，有终，是指营销活动有清晰的执行结束的节点。所以心血来潮的营销“游击战”不能称为campaign，那些几乎永远不停止的营销行为（例如SEM投放）也不能称为campaign。

Audience：受众。就是广告的阅览者，普罗大众。受众这个词太书面化了，但是确实没有比这个更明确的词，所以在这两期公开课中都会用这个词。

Target Audience：目标受众。任何人都可能看到你的广告，但只有那些合适的人才会购买你的商品。所以，合适的人就是你的目标受众，是你最希望影响到的那群人。

Effectiveness：效果。这是广告主评估品牌推广类广告好坏的一个关键指标。效果的含义比较广泛，在不同的campaign目标下可能不尽相同。比如，能够覆盖到的人群情况（coverage）可以作为一种效果；或者，人们是否真正对你的品牌产生了认知（awareness）也被称为一种效果。类似的，人们也用performance来表示营销的好坏，二者是近义词，但又不完全相同。Performance更偏重有实际产出的具体效果，因此常常被翻译为“绩效”，例如campaign产生了多少的click，产生了多少的交易等等。因此，effectiveness较为抽象，几乎只在品牌推广中被提起，而performance较为具体，在效果类推广中更为常见。

Efficiency：效率，即达到某种效果所花费的成本（包括金钱与时间）。品牌推广类营销常用，效果推广类很少提及。

Branding：品牌推广。

Awareness：对品牌或产品的认知。做广告的首要目的，就是让消费者意识到你的品牌或者商品的存在，说白了就是搏存在感。看看近期密集发布的手机在各个新闻app、电商app中频频发力，就知道awareness对广告主有多重要了。

Buzz：消费者或网民对于品牌、产品等广告主在乎的事情在网上发出的各种声音。与IWOM是一个意思。Buzz是苍蝇蜜蜂之类的嗡嗡声，无数网民每天在网上发出的各种意见， 在上帝看来就像苍蝇蜜蜂般嗡嗡作响。

IWOM：Internet Word of Mouth的简称。即网络口碑。

Survey：调研。这个词是一个有意思的词，主要在它的发音。作名词的时候重音在前——[?s??ve?]，作动词的时候重音在后——[s??ve?]。

ePR：通过互联网进行的PR。

IP：Intellectual Property，即知识产权。就是过去说的那些原创的，有知识产权的东西。现在天天出现在各种口语和报道中的这个词指各种在互联网上创作的内容。例如，我的这个公开课也可以称得上是IP。Papi酱的网红视频？当然也是咯！与上篇的IP写法一样，意义完全不同。

Minisite/Microsite：没有对应的汉语名词，而且大家也从来不用汉语描述它。就是指为campaign专门定制的campaign网站，这些网站规模都不大，所以被称为mini（迷你）或者micro（微）。

Programmatic：程序化（广告）。一种革命性的广告运作方式。在课堂中会有详细的介绍。

DSP：Demand Side Platform（需求方平台）。程序化广告的广告投放管理系统平台以及相应的服务提供方。具体解释这里不多说了，到时候课堂上会详细介绍。

SSP：Supply Side Platform（供应方平台）。程序化广告的广告资源管理系统平台以及相应的服务提供方。具体课上介绍。

RTB：Real Time Bidding（实时竞价广告），这是程序化广告最重要的一种方式，也是理论上最佳的广告资源变现方案。但具体如何实现，优劣问题，以及国内的情况，课上详细讲。

Bid/Bidding：竞价。搜索引擎PPC广告，或者RTB广告，都需要竞价。类似于拍卖，但需要在预置条件的前提下通过程序来实现。课堂上详细说。

Bidder：Bidder即竞价者，在PPC广告范畴内，bidder就是普通SEM的操作从业者。在程序化广告范畴内，bidder一般就是DSP服务提供商。

DMP：Data Management Platform，数据管理平台。程序化广告（programmatic advertising）中为实现定向受众所需要倚仗的数据平台。但它能做的还远远不止这么多。培训课程中会专门涉及。

Verification：特指广告的验证。验证有两类，一类是验证广告是否真实被投放出去了，以及投放出去之后广告所处的环境是什么。什么是广告所处的环境？——对于PC web上的广告而言，环境就是这个网站以及具体承载广告的这个页面。另一类是验证广告覆盖的人群的情况是不是跟预想的一样。

Part7 效果营销领域的名词

Conversion Rate：转化率。是指从流量到实际销售转化的能力。与ROI本质是一样的。只是ROI衡量的是现金（收入）对现金（支出）的对比，而转化率衡量的是销售的数量与进入销售漏斗的人数（或者次数）的比例关系。

Churn和Churn Rate：客户流失和客户流失率。所有需要尽可能让用户反复购买（或付费）的生意，都有这个度量。看名字就知道，这个度量用来描述失去客户的情况。具体如何定义，以及如何分析，在课堂上会有详细说明。

SERP：Search Engine Result Page。就是搜索引擎的搜索结果页面。

Search Query：用户的搜索词。人们在各种搜索框（典型的如搜索引擎的搜索框）内填入的词，这些词可能很不结构化，且非常随意。而keyword，则是使用搜索引擎竞价排名的广告主设定的关键词。

Keyword：使用搜索引擎竞价排名的广告主设定的关键词，较为结构化，较规范。这些词不可能穷尽用户的search queries，因此搜索引擎会把用户的search queries转变为与之最相近（不过是否真的是最相近，那就只有搜索引擎知道了）的keywords，然后显示搜索的结果。

Organic Search：自然搜索流量源，即用户点击了自然搜索结果产生的流量，而不是点击了竞价排名（PPC）而产生的流量。

Affiliate Marketing：有时也就直接简称为Affiliate。这个词在国内没有对应的名词，在台湾被译作“联署营销”，但是这个翻译似乎仍然莫名其妙。Affiliate marketing就是典型的代销模式——你的东西，我帮你卖，卖出多少，你给我按照一定比例提成。在互联网上，affiliate marketing变成了我帮你引流量，我给你的流量如果有转化了，你给我提成。国内的亿起发、领克特等就是做affiliate marketing的专门平台。

EDM：Email Direct Marketing（电子直邮营销）的缩写，是利用电子邮件（Email）与受众进行商业交流的一种营销方式，电子邮件营销是网络营销手法中最古老的一种。

Performance：绩效，即通过营销之后获得“战果”。ROI就是一种典型的performance，销售额之类的也是。

GMV：Gross Merchandise Volume。这是电商经常会用到的词，书面是“毛销售量”，实际就是销售流水。当然，销售流水不等于最后赚到的钱。GMV=1销售额+2取消订单金额+3拒收订单金额+4退货订单金额。GMV是流水，只要你下了订单，生成订单号，就算了GMV。而这个订单转化为平台的实际收入还会有2、3、4这些流失量。下单以后后悔了取消订单，订单送到你面前了后悔了拒收订单，签收订单以后后悔了要退货（这个步骤不同的电商平台计算方法不一样，有的平台是不管退不退货都搜算进销售额中）。总之，人艰不拆，GMV数字大，好看，而且我们监测起来也最容易，所以这是最常用的。

AOV：Average Order Value。平均订单价格。

Monetization：变现。

MRR：Monthly Reoccurring Revenue，直译是每月都会产生的收入，实际就是用户要交的月费。比如我办了一个158元的包月电话套餐，对于电信公司而言，我就给他们贡献了MRR 158元。

Part8 移动端常用的

Screen：如果说web端用page view来记录页面被浏览的次数，那么screen就是app的页面，screen view就是app的页面浏览的次数。但因为screen没有page这个东西，所以就用screen来表示。我也不知道应该对应什么汉语名词，或者应该用“屏显”？反正相信你懂的。。

DAU：Daily Active User（日活跃用户数量）的缩写，通常统计一日（统计日）之内，登录或使用了某个产品的用户数（去除重复登录的用户），是用来衡量产品的用户粘性的重要指标。

MAU：Monthly Active User（月活跃用户数量）的缩写，概念与DAU相仿，区别在于时间跨度。MAU除了能衡量用户粘性，还可以分析产品衰退周期。

H5：是HTML5的简称。它实现的功能与Flash类似（用于实现动画和各种酷炫的人机交互界面等），但是比Flash具有更强的兼容性，可扩展性，稳定性以及安全性，因为该技术是HTML的延展，而非如同Flash一样是一个单独创立出来的事物。目前各大互联网钜子们——包括Adobe（Flash的所有者）——都已经加入支持H5，H5在移动端几乎已经完全取代了Flash。

ASO：App Store Optimization。狭义上指针对苹果应用商店的app排名所做的优化工作。广义则指对所有的应用市场的优化。与SEO类似，都是排名优化，只是优化的对象变成了应用市场。

LBS：Location Based Service，基于位置的服务。低逼格的讲就是用手机定位之后，能否关联一些服务或广告的。当然实际的应用比我说的肯定逼格高很多。

Part9 企业、组织机构与产品

Google Analytics：谷歌分析，简称GA，是全球用户量最大的网站和APP上流量用户行为的监测与分析工具。

Universal Analytics：简称UA，是GA在2013年左右做的一次大升级版本，目前无论是免费还是付费版的GA，都是基于Universal Analytics的。GA的付费版叫Google Analytics Premium，简称GAP。

GTM：Google Tag Manager，是谷歌公司用于管理网页上各种广告、监测和分析代码的平台型工具。课堂上会简单介绍。

DCM：DoubleClick Campaign Manager的简称 (即新版 DoubleClick for Advertisers 7)，DCM 是一个管理及投放广告的全面解决方案，覆盖从 广告策划、管理、定位、投放、优化到生成报告等。广告的impression和click等几乎所有的度量，都可以通过它来进行监测。

AdWords：全称Google Adwords，是谷歌搜索引擎的关键词竞价系统，按点击收费（CPC）。

AdSense：全称Google Adsense，是谷歌推出的针对网站主（简称发布商）联盟的一个互联网广告服务，通过程序来分析网站的内容，并且投放与网站内容相关的广告。

DAA：Digital Analytics Association，数据分析协会。美国的互联网营销数据分析行业协会，号称是全球协会，但主要章程和成员都在美国，对其他国家的影响力较小。

IAB：Interactive Advertising Bureau，美国的互动广告局，也是类似于DAA的行业协会，主要领域是数字广告。这个协会在美国，但对全球数字广告的影响力巨大，尤其是标准和技术上。

#### 如何发布 APP 到 Apple AppStore

#### 如何发布 APP 到 Google Play Store

#### 如何发布 APP 到 360 应用商店

#### 如何用 Google Analytics 做用户数据分析


