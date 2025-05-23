---
title: 关于时·刻APP的UI设计开发思路思考
date: 2025-04-30 23:13:05
tags:
    - UI设计
    - 项目
    - 软件
keywords: 时·刻 APP
categories: 
    - 项目
cover: /img/Chronotick.png
main_color: "#090664"
ai: true
---
<p>最后更新：2025年4月 | 版本：0.2 </p>
<p>我很喜欢在车上或者在短程路途中阅读点什么，但是这种方式的阅读方式并不理想，因为我需要花费很多时间来寻找适合的书籍，而且阅读的过程中往往是刚刚看上，而路途就到了终点。这种感觉令人困扰。</P>
<p>为此我最近在做一款名叫"时·刻"的APP，它可以帮助我在短程路上找到适合的短篇，集成了音乐播放的功能，每一个设计都是为了即刻当下而设计的，这样我就可以在短程路上轻松地阅读点什么了。</p>
<p><img src="/img/zhushitu.png" style="width:100%; max-width:100%; border-radius:10px; box-shadow: 0 2px 8px rgba(0,0,0,0.05); margin:1rem 0;"></p>
<p style="font-size: 0.95rem; color: #555; text-align: center;">Chronotick 时·刻</p>
<h2>设计</h2>
<p>首先说明一下，因为这个APP还在很初期的阶段，目前来说更多的还是一些想法，这个项目离结束可能还早的很。</p>
<p>时刻APP英文名字为 Chronotick Chronotick为"Chrono"（时间词根）+ "tick"（滴答声），"tick"与中文"刻"发音相似。该词兼具时间流动的动态意象与精准刻度感。</p>
<p>在设计APP时，市面上少有类似的APP，凸显自己的设计风格，我偏爱一些设计原则，如"超简洁化"、"直达"、"易用"等。</p>
<p>考虑APP的体量大小，作为一个小应用，我并没有做华丽的动效，所有的设计都是为了专注阅读。</p>
<p><img src="/img/APP开屏页.png"></p>
<p style="font-size: 0.95rem; color: #555; text-align: center;">APP开屏页与登录页</p>
<h2>UI 交互</h2>
<p>在设计交互时，我采用了"扁平化"的设计风格，所有的交互都是基于"直达"的原则，即用户不需要过多的操作，就可以完成想要的操作，单手操作阅读的感觉真的很好</p>
<p>首页设计我引入了一个“此刻”的概念，即用户可以每天在这里看到推荐的短篇，有可能是中篇的一段影评，一个故事，也有可能是一段经典，可以根据自己的需求进行筛选。</p>
<P>首页的设计是一个类似与“拍立得”或者”明信片“的设计，向下滑动就可以看到昨天的内容，向上滑动就可以看到今天的内容，不需要过多的操作，专注于自己的阅读。</P>
<p><img src="/img/首页与即刻预览.png"></p>
<p style="font-size: 0.95rem; color: #555; text-align: center;">首页与此刻文章预览</p>
<p>值得一提的是，如果用户不满足于此刻的短篇内容，在发现页面有详细的文章分类以及音乐精选，可以在阅读文章的同时聆听文章相关音乐，虽然软件是弱社交的工具APP,但是好友系统依旧得到了保留。</p>
<p><img src="/img/发现页.png"></p>
<p style="font-size: 0.95rem; color: #555; text-align: center;">发现页与即刻音乐</p>
<h2>其他功能与细节</h2>
<p>在功能模块之外，我也尽量在一些细节上做了设计。比如阅读页的字号可以根据用户习惯调节，白天和夜间会自动切换浅色/深色模式，这些都是我平时在使用其他阅读产品时常常感到缺失的功能。</p> 
<p>音乐播放模块是一个轻量级的浮动播放器，不占据页面主要视线。用户可以自由切换是否开启音乐，也可以将音乐最小化到页面底部，这样不会打断阅读节奏。</p>
<p>考虑到有些用户更偏好听书的方式，我也在实验「朗读模式」，用系统语音朗读当前文章。这对于通勤者或者视力不方便的人可能会是一个替代方式。</p> 
<p>发现页除了分类筛选，我还加了一些小的探索性功能。比如“随机一篇”，可以在无所事事时刷新出现一段文字，灵感来源其实是小时候翻日历，偶然看到一句话的那种体验。</p>
<p>设置页也做了简化处理。大部分默认设置都倾向“不过度打扰”，比如不强制推送、不会弹出评分请求，也不会自动登录第三方账号。我希望它是一个“你主动来用”的产品，而不是“它追着你用”的产品。</p>
<h2>总结与展望</h2>
<p>目前这款名为“时·刻”的APP还处在一个比较初步的阶段，我也并不急于上线，更多的是作为一个长期的尝试。</p>
<p>我自己很喜欢这种有点“偏静态”的工具型应用——没有干扰、不催促、不强调打卡，只是你想读的时候，它刚好合适地出现。</p> 
<p>后续可能还会继续优化一些体验，比如夜间模式、不同音乐风格的切换，甚至和一些平台联动，但这些都不会违背“简单”“轻量”“即时”的初衷。</p> 
<p>这个项目最初只是我为了解决“短途阅读焦虑”做的一点尝试，但在做的过程中，它逐渐变成了一个承载我个人阅读习惯和审美趣味的地方。</p> 
<p>希望它慢慢成长，也希望有人能在自己的碎片时间里，因为它，读到一段合适的文字，听到一首合适的音乐。</p>
<p>这个项目从一开始就不是为了“做一个产品”而起步的，而是基于一种真实的使用需求——我希望能在每天不那么完整、不那么安静的碎片时间里，读点什么、听点什么，不需要选太久，也不需要处理复杂的操作。</p> 
<p>很多功能，其实是在“我自己怎么用”这个前提下反推设计出来的。比如首页就是“我现在就想看点东西”，发现页就是“我现在想换个口味”，收藏夹就是“我之前看到一段不错，过几天还想回来看看”。</p>
<p>作为一个个人主导的小项目，它目前还缺乏完整的内容来源体系和内容审核机制，也没有真正开始规模化测试，但我觉得这些都不急。我更希望它先成为一个舒服、稳定、自洽的小工具。</p> 
<p>未来可能会加入的一些方向包括：</p> <ul> <li>内容合作：与一些公众号、短篇创作者进行非商业内容合作</li> <li>主题扩展：如电影摘录、日记风短文、读者投稿等内容板块</li> <li>体验增强：加入动画过渡、段落标记、音乐收藏列表等</li> </ul> 
<p>但不管增加多少功能，我会坚持它的节奏是“慢的”，内容是“轻的”，设计是“静的”。</p> 
<p>最后，如果这个APP将来真的上线，我想它的描述里也许只需要一句话：</p> <blockquote style="margin: 1rem; padding-left: 1rem; border-left: 4px solid #999; color: #444;"> “在这段路上，读点什么，听点什么。” </blockquote>