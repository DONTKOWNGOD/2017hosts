<h2>更新预告：</h2>
<h4>1.有网友向我反馈，目前Hosts里支持的各项服务还是会存在某些页面打不开的情况，经过检查是因为Hosts内还缺少某些网页元素的域名，近期会排查调整。</h4>
<h4>2.有47位给我发邮件的+github三位网友向我反馈，他们使用hosts时发现youtube视频速度始终上不去，因为这个不太好查所以会往后延迟点在顾及再修复。</h4>

<h2>友情提示：</h2>
<h4><strong>1.因twitter上一些不可描述内容的原因，各地运营商开始干扰https的twitter连接，方式和当年干扰Google是一模一样的，遇到打不开这个问题你可以使用赛风暂时翻墙上推。</strong></h4>
<h4>2.最近因为youtube上的一些内容的原因，导致youtube被攻击，随后youtube视频服务器就屏蔽了来源是中国的ip，包括中国企业网络的AS，这就是为什么ipv6下看youtube看不了的原因。</h4>
<h4>3.经过25天的整理测试添加，ipv6hosts终于上线了，不过ipv6hosts部分服务还是没有找到ipv6地址（我尽力了），所以只能用ipv4代替（Twitter、Tumblr、XDA等等），请校园网用户在使用时注意自己的流量。</h4>
<h4>4.绝大多数网站均需要以https方式打开，置顶提醒！tumblr网页版播放视频都是从用户的子域名获取文件的，这个域名数量大约有几百万个，因此无法添加到hosts，所以没法播放。</h4>
<h4>5.已经应网友要求添加pornhub，博讯等网站，下一步找到可用更好速度ip时将继续跟进调整。</h4>
<h4>6.为了能让你少费点心，不用每次上网都提心吊胆需要加https，建议在浏览器安装httpseverywhere插件，chrome点此下载：https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp?utm_campaign=en&utm_source=en-et-na-us-oc-webstrext&utm_medium=et </h4>
<h4>7.有人向我反馈，在deepin社区看到有人拿着这边hosts怎么怎么样的，不过我想说，我还是那句话，只要是正常使用，从这里拿的hosts不必要写明来源，这个人的软件其实还是挺好用的，不过hosts是我这里的。（遇见我的话最好还是别那样）帖子链接：https://bbs.deepin.org/forum.php?mod=viewthread&tid=140287&extra=</h4>


<img src="https://camo.githubusercontent.com/af4cf563b43a022ec902562c91c26521d2ed9dbb/68747470733a2f2f7777772e676f6f676c652e636f6d2f6c6f676f732f646f6f646c65732f323031362f686f6c69646179732d323031362d6461792d332d736f75746865726e2d68656d697370686572652d353138353031313932393035353233322d687032782e676966"></a>


 
**请你花大约两到三分钟时间仔细看看readme吧，应该对你了解这个项目有帮助**

**请各位网络喷子，网评员，水军等人自觉绕道，左拐不送！**

**这里不排斥任何小白，因为再厉害的人那都是从小白过来的，有什么问题无论确不确定或者是不知道怎么说合适的话，你就按你的意思直说就行（请注意你的言行），如果需要帮助请尽可能提供有关情况更详细信息**


#### 近期说明更新在：2017年6月21日

## 简介

这里更新最新可用的hosts，这里更新的分为手机版和电脑版。

使用本hosts更新源提供的hosts可以获得完美的youtube视频和其他服务的较完美体验，windows替换的话请在杀毒软件内添加hosts信任！如果你要想添加什么网址你可以开启一个lssues并清晰地表明你的意愿。本hosts不保证随时可用，但是我会尽我最大努力让它高可用，努力做全网最好，你的积极分享是对我的最大鼓励。

手机版则可以访问play商店并下载应用，youtube在设备支持的情况下国内网络带宽足够的情况下可以裸连观看720p或480p,欢迎将本项目分享给更多的人，方便更多人自由上网。 本处的hosts如果你需要转载到个人博客等等途径进行分享的话是不需要你声明来源是本处的（hosts不是软件，所以不受计算机软件相关协议约束）如果你认为他人需要持续更新，那么还是建议加上来源比较好。

## 下载hosts文件（可直接把地址复制，输入第三方下载器，下载好改名为hosts替换进设备）
* [电脑(windows)版](https://raw.githubusercontent.com/wangchunming/2017hosts/master/hosts-pc)

windows替换文件路径  `C:\Windows\System32\drivers\etc\hosts`

* [手机版](https://raw.githubusercontent.com/wangchunming/2017hosts/master/hosts-mobile)

手机替换文件路径 `/etc`  **需root**（在linux平台下同样是这样，只不过是需要通过终端获得root后，再调出gedit或者vim编辑。）
## 维护目的

**维护hosts不为别的，自己用的同时还有就为方便同时开发者或者特定群体的你/您，因此本项目不接受任何捐款，如果你觉得有用，就请把它分享给更多人**

**两万余行，这一切只为了更好的体验！已经在发布时100%验证可用性，敬请放心使用，献给所有热爱自由的人们！（如果万一替换后无效请自己手动转文档格式）**

## 警告

WALL具备刺探TLS的能力（可以知道你访问的URL详细地址并且可以拿到交换的证书也可以检查提交的表单），请大家小心，因此请勿使用直连方式来进行一些私人行为，谢谢，**这不是危言耸听**，一旦触发规则则会返回诸如“*此网站无法提供安全连接*”、“*x处的网页无法链接*”等错误。

## 提示

* 如果你位于中国电信网内，该项目处提供的hosts可能会无法正常使用，因为电信众所周知的出国慢，我也没有解决办法。

* 想要加什么网站（当然需要支持https），尽管拍砖尽管吼哦，毕竟这是方便你和我的好事，不用客气。

* 回答网友们的一个问题，本处的hosts对于处理各项服务而言，如果可以找到稳定的官方ip那么就会优先使用官方ip，如果找不到就用代理，从2017年5月25日起，本处的hosts发布前需要经过上海闵行，四川成都，山东青岛，山东莱芜，北京房山，河北石家庄，河南平顶山，广东深圳南山，山东枣庄，山东东营广饶这些多地网友共同测试后才会发布，以此严把质量关，确保服务在发布时100%可用，如果实在无法做到可用的话本处会置顶提醒。

* 如果突然连着连着ip就不通了有70%的可能是被运营商反向封了访问权限，只需要重新拨号或者重启手机即可解决，如果无法解决就是ip失效，运营商经常使用此种方式临时封堵ip，中国移动网内还没有这项技术，但是联通电信却在广泛使用。

* 少数地区的运营商，例如移动或者鹏博士或者爱普，也可能无法正常使用本处提供的hosts，这个是你我不能左右的。
* Google 等网站请通过 https 方式访问，如 https://www.google.com/ncr 或者 https://www.google.com.hk 避免因响应http请求时的重置连接。这几版的hosts会一直更新，敬请大家留意关注。

## 测试情况：

### 手机

* 客户端可用：<br />
play市场，Google搜索，chrome，googleplus,google街景,google报亭,google环聊,google健身,google地图,googleallo,googleDuo,tumblr,twitter,facebook,instragram,duckduckgo,dropbox（等等）
* 客户端不可用：<br />
Gmail：<br />
不可用原因：没有可用stmp服务器，并且gmail不支持通过简单代理使用。<br />
telegram：<br />
不可用原因：telegram客户端使用ip地址方式直接连接服务器（并非域名），其所使用的ip地址在国内已被屏蔽。
* 功能不可用：查找设备（安卓）【因为纯UDP流量过不了墙，所以无法使用】
* 网页可用：100%可用。
* 有瑕疵：line google新闻 还有各类googleapps的帮助页面打不开。
  
### 电脑

* **youtube**
发布时测试功能98%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/QQ%E6%88%AA%E5%9B%BE20170121230113.png"></a>

* **youtube看视频速度(联通）**：
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/100.PNG"></a>
* **youtube看视频速度（位于移动网测试）**：
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/cnmb.PNG"></a>

* **Tumblr**
发布时测试功能：50%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/QQ%E6%88%AA%E5%9B%BE20170121230507.png"></a>

* **Google**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/1.png"></a>

* **Facebook**
发布时测试功能99%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/2.png"></a>

* **维基百科**
测试功能正常率100%
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/3.png"></a>
* **Dropbox**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/4.png"></a>

* **Twitter**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/5.png"></a>

* **vimeo**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/6.png"></a>

* **github**
发布时测试功能100%正常
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/7.png"></a>
* **Bing（HK）**
发布时测试功能100%正常（需要https打开）
<img src="https://raw.githubusercontent.com/wangchunming/2017hosts/master/img/8.PNG"></a>


## Devming's Q&A：

##### 网友们发邮件给我总是会问一些奇奇怪怪的问题，于是乎我就在这里回复下吧。

* hosts替换一次能用多久？
#### 本处的hosts会尽量做到稳定与速度兼顾，请你放心，如果是失效或者打不开的话的话请及时来github报issuses。
* hosts替换之后打开浏览器经常提示正在解析主机？
#### 非常抱歉哈，本处的hosts为了让你有个更好的体验，各类网址都是非常全的，hosts文件很大，系统读取可能会比较慢（条目完整性是github全网第排二，ipv4 hosts第一，第一家是github上的ipv6hosts那个，截至发本篇说明前是这样的）因为几乎很完整的原因，因此从而可以做到秒开各类网站或者youtube视频的效果，如果你因为设备所限制，不想使用完整的服务，仅仅是需要部分服务的话，请前往wiki页面找到几个备用的更新源来选择合适的版本 
* 更新这个hosts的都是什么人，怎么这么好用？会不会有阴谋诡计？
#### 你不用担心安全性问题，本hosts不会添加任何恶意网址，如果有网友申请添加的hosts条目中有恶意网址的话我也会不理睬相关请求，甚至对该网友做怼回去屏蔽等相关处理。
#### 我是个学生，现在在山东莱芜上学，我也不是什么世外高人。正如我上面提到的那样，我既然能花很小的力气去帮助几千个人甚至几万个人解决他们的实际问题，我何乐而不为？
* 既然你都努力更新hosts了，那为什么不给点免费的ss账号用用。
#### 某个网友给我发邮件提到了这个，我在这里回复一下，我现在没有很好的经济条件，零用钱不是很多，目前金额仅仅只能满足我上学使用和买一个2.5美元的vps所需，暂时还没办法这样，我其实认为这样更好，以后条件好点了我会这么办的，为学生和程序员和外网重度用户提供免费服务我也很愿意。 
* 难道不能做一个像gohosts那样的应用吗？一键在手机上替换hosts？
#### 暂时没有精力，抱歉啦，不过你可以在gohosts里设置备用源设置一个我这里的。 
* 哎，你有twitter等社交媒体吗？我想关注你( •̀ ω •́ )y

#### Facebook:@chunmingshq 
#### twitter:https://twitter.com/wangDevming 
#### instagram: https://instagram.com/chunmingshq 
#### telegram: @wangDevming 
#### Blog： https://51kly.net 
#### QQ:1787149097（或者搜chunmingshq@gmail.com，加好友暗号：I‘m still Ok) 
#### Weibo：http://weibo.com/2116467627 
#### Mi chat：349395816

#### 有什么事情需要及时协商或者是有兴趣骚扰一下都可以 O(∩_∩)O

#### 做hosts累不累啊？
* 做hosts累的地方就在于抓包，我不像其他更新hosts的人那样，别人提问题我才会更新，而是我自己找到问题的时候我自己就修了（github上这么努力的更新hosts的人不超过4个），我在17年4月的时候为了解决手机hosts的facebook和ins显示图片这个问题，我拿着手机一直刷趴在电脑跟前三十多个小时没睡觉，然后赶在网友提出这个问题2小时之后解决掉了这个问题，给了他一个满意的答复。
* 总之，各位热心的分享是我更新的最大动力，这比捐款对我的激励作用都大，分享无需注明来源。
