
*****

####  月灵银羽  
##### 1#       楼主       发表于 2025-2-11 20:05

 本帖最后由 月灵银羽 于 2025-2-12 11:02 编辑 

2月 11 日消息，Linux 内核社区近期爆发了一场关于编程语言的激烈争论，最终导致一位核心开发者退出项目。这场争论的核心在于是否应该更多地使用 Rust 语言来开发内核，以及开发者之间的沟通方式。

Asahi Linux 项目的领导者 Hector Martin 公开批评另一位资深内核开发者 Christoph Hellwig，阻碍 Rust 语言在内核中的应用。

Martin 认为，Rust 语言在内存管理方面更加安全和现代，应该在内核开发中扮演更重要的角色；而 Hellwig 则对从 C 语言迁移到 Rust 持谨慎态度，认为迁移过程会增加内核的复杂性，并直言在 Linux 中混用代码就是“癌症”。

Linux 之父 Linus Torvalds 的介入成为了事件的转折点。Torvalds 本人并不反对在内核中使用 Rust，但他对 Martin 公开批评 Hellwig 的方式表示强烈不满。

Torvalds 在内核邮件列表中批评 Martin，认为他应该反思自己的行为，并指出技术问题应该通过技术途径解决，而不是诉诸社交媒体。

在 Torvalds 的批评之后，Martin 宣布退出内核上游开发，转而专注于 Asahi Linux 的下游开发。他表示对内核开发流程和社区管理方式失去了信心，尽管如此，Martin 表示未来仍有可能向上游提交补丁。

[论坛助手,iPhone](https://bbs.saraba1st.com/2b/forum.php?mod=viewthread&amp;tid=2029836)

*****

####  i0ncube_R  
##### 2#       发表于 2025-2-11 20:15

看hackernews，kernel邮件列表上貌似吵了很久了

[论坛助手,iPhone](https://bbs.saraba1st.com/2b/forum.php?mod=viewthread&amp;tid=2029836)

*****

####  燕山雪  
##### 3#       发表于 2025-2-11 20:15

总觉得rust粉跟特么邪教一样

*****

####  双刀少女  
##### 4#       发表于 2025-2-11 20:15

一直想学rust，找不到应用场景啊...

*****

####  ryanz  
##### 5#       发表于 2025-2-11 20:20

这两者的矛盾本来就是不可调和的，最开始 rust 爱好者拿进内核来吹就觉得此事不长久。rust 需要 kernel 来证明自己，而 kernel 并不需要 rust 来保证所谓的安全性。

另外现在编译内核加个 ebpf 需要一堆依赖我就觉得麻烦的要死，更别提整另一个编译器依赖了。

*****

####  原装大小姐  
##### 6#       发表于 2025-2-11 20:22

rust确实蛮奇葩的，去到哪都想替换，从应用来看，替换造成的功能不可预期性比所谓的安全还值得担心

—— 来自 [鹅球](https://www.pgyer.com/xfPejhuq) v3.3.96-alpha

*****

####  weiyang  
##### 7#       发表于 2025-2-11 20:26

linus才55岁，就他这个级别来说不算老，起码还能镇压十年吧

*****

####  kumh  
##### 8#       发表于 2025-2-11 20:32

不如另开分支直接用rust实现完成kernel。

*****

####  thq  
##### 9#       发表于 2025-2-11 20:38

蟹粉为嘛不自己从头开始搞一个内核替代linux

*****

####  pwzzy  
##### 10#       发表于 2025-2-11 20:41

<img src="https://static.saraba1st.com/image/smiley/face2017/001.png" referrerpolicy="no-referrer">内核开发需要rust所谓的安全性吗，为了运行效率本来就允许用不安全的写法的，引入另一套体系复杂度不是爆炸了

*****

####  星空天神  
##### 11#       发表于 2025-2-11 20:55

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67397830&amp;ptid=2245923" target="_blank">pwzzy 发表于 2025-2-11 20:41</a>

内核开发需要rust所谓的安全性吗，为了运行效率本来就允许用不安全的写法的，引入另一套体系复杂度不是爆炸 ...</blockquote>
肯定一堆unsafe

*****

####  Nanachi  
##### 12#       发表于 2025-2-11 20:56

支持ruster重写kernel

—— 来自 [鹅球](https://www.pgyer.com/GcUxKd4w) v3.3.96

*****

####  厨具战士mk2  
##### 13#       发表于 2025-2-12 08:57

提到rust听到的大多都是重写，rust有没有自己的拳头应用？

*****

####  coyove  
##### 14#       发表于 2025-2-12 09:00

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67397779&amp;ptid=2245923" target="_blank"> kumh 发表于 2025-2-11 20:32</a> 不如另开分支直接用rust实现完成kernel。 </blockquote>
rinux，正好r l 不分来自: iPhone客户端

*****

####  幽箬筱  
##### 15#       发表于 2025-2-12 09:03

语言神批真的闹麻了

*****

####  YoumuChan  
##### 16#       发表于 2025-2-12 09:05

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399873&amp;ptid=2245923" target="_blank">厨具战士mk2 发表于 2025-2-12 08:57</a>

提到rust听到的大多都是重写，rust有没有自己的拳头应用？</blockquote>
Cloudflare的Pingora算吗？

*****

####  Jet.Black  
##### 17#       发表于 2025-2-12 09:06

搞成这个样子，是不是Linus Torvalds本人受够了C语言，想用Rust?

*****

####  神圣天使书记官  
##### 18#       发表于 2025-2-12 09:07

没有拿得出手的东西只能靠吹是这样的

*****

####  iamawaistcoat  
##### 19#       发表于 2025-2-12 09:08

还不是linus放进来的

*****

####  montanaB  
##### 20#       发表于 2025-2-12 09:10

<blockquote>pwzzy 发表于 2025-2-11 20:41
内核开发需要rust所谓的安全性吗，为了运行效率本来就允许用不安全的写法的，引入另一套体系复杂度不是爆炸 ...</blockquote>
Rust这玩意儿最奇葩的是，搞了一大堆，各种概念，各种限制，来保证所谓的内存安全性。但是在这些东西之外，他居然也留了unsafe的后门。

我当时看到这一点后，我就对这语言的吹嘘失去了兴趣。如果他的安全性真的这么厉害，这么坚不可摧，那为什么要留后门？

*****

####  trentswd  
##### 21#       发表于 2025-2-12 09:13

上次俄罗斯贡献者那事咋样了，冷处理成功了？

*****

####  Midnight.Coup  
##### 22#       发表于 2025-2-12 09:13

用 rust 写的系统有啊，RedoxOS，用的 DE 也是 rust 写的 COSMIC Epoch 

*****

####  高妹控  
##### 23#       发表于 2025-2-12 09:20

印象里起码5、6年前，ruster就到处布道了，恨不得从今以后所有东西都要用rust写，到现在这个局面一点也不意外<img src="https://static.saraba1st.com/image/smiley/face2017/068.png" referrerpolicy="no-referrer">

—— 来自 [S1Fun](https://s1fun.koalcat.com)

*****

####  王兰花秀丽  
##### 24#       发表于 2025-2-12 09:20

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399873&amp;ptid=2245923" target="_blank">厨具战士mk2 发表于 2025-2-12 08:57</a>

提到rust听到的大多都是重写，rust有没有自己的拳头应用？</blockquote>
区块链上面的solana，以及由基于rust的move语言的aptos和sui

*****

####  d2loader  
##### 25#       发表于 2025-2-12 09:34

<img src="https://static.saraba1st.com/image/smiley/face2017/112.png" referrerpolicy="no-referrer"> RIIR的人很多都很礼貌的

至少内核这件事上, C系开发者一个在别人演讲时突然打断演讲, 直球大喊大叫的

然后Christoph Hellwig说癌症

结果RIIR被泥潭骂邪教.... 

﹍﹍﹍

评分

 参与人数 1战斗力 +1

|昵称|战斗力|理由|
|----|---|---|
| darklinden| + 1|思维顽固了已经|

查看全部评分

*****

####  YoumuChan  
##### 26#       发表于 2025-2-12 09:36

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399968&amp;ptid=2245923" target="_blank">montanaB 发表于 2025-2-12 09:10</a>

Rust这玩意儿最奇葩的是，搞了一大堆，各种概念，各种限制，来保证所谓的内存安全性。但是在这些东西之外 ...</blockquote>
因为通过Rice Theorem(莱斯定理)可以证明你不可能构造一个编译器使其接受所有内存安全的程序并拒绝所有内存不安全的程序。

Rust选择接受内存安全的程序的一个子集（从而把语义性质变为语法性质），通过unsafe让程序员在需要的时候自行写出内存安全集合与这个子集的差集。

﹍﹍﹍

评分

 参与人数 1战斗力 +1

|昵称|战斗力|理由|
|----|---|---|
| darklinden| + 1||

查看全部评分

*****

####  小止  
##### 27#       发表于 2025-2-12 09:37

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399968&amp;ptid=2245923" target="_blank">montanaB 发表于 2025-2-12 09:10</a>

Rust这玩意儿最奇葩的是，搞了一大堆，各种概念，各种限制，来保证所谓的内存安全性。但是在这些东西之外 ...</blockquote>
按我理解用rust那套东西确实是可以实现所有功能，但是心智负担可能会增加到惊人的程度

*****

####  BetterCall  
##### 28#       发表于 2025-2-12 09:42

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399888&amp;ptid=2245923" target="_blank">coyove 发表于 2025-2-12 09:00</a>
rinux，正好r l 不分</blockquote>
r l不分是什么意思？

—— 来自 [鹅球](https://www.pgyer.com/xfPejhuq) v3.3.96-alpha

*****

####  Steel.Haze  
##### 29#       发表于 2025-2-12 09:56

坚决抵制Rust作为内核。它针对内核开发，除了所谓的捕风捉影的"内存安全"之外，全无任何比较优势，缺点却很多，这个话题发展到目前的程度就是一种匪夷所思，而且针对未来的亲智能计算时代的计算架构来说更是灾难性的麻烦。这玩意现在被硬推有政治性，我甚至怀疑它最近这波被推动和某类美国情报部门特殊的网络攻击后门手段应用有关。

无论如何，如果有Rust混入内核，我肯定会用原来C系内核的搞自己的分支，不会接受。

﹍﹍﹍

评分

 参与人数 1战斗力 +1

|昵称|战斗力|理由|
|----|---|---|
| ForeverTime| + 1|+1|

查看全部评分

*****

####  darklinden  
##### 30#       发表于 2025-2-12 10:03

<img src="https://static.saraba1st.com/image/smiley/face2017/001.png" referrerpolicy="no-referrer">

“嘿兄弟，我知道你是十年经验的老走钢丝侠，但是你先别急，我给你推荐一辆走钢丝专用轮椅”

“这玩意儿纯钢打造，操作失误会挨鞭子，并且无法后退，无法跳跃，无法拿大顶”

“但是相信我，这玩意儿绝对可以保证小脑发育不全的人都能安全走钢丝，甚至有些情况下比你还快得多”

“并且像你这样的高手，也可以按下【unsafe】按钮跳出轮椅爱怎么跳怎么跳，当然以你的经验是不会摔的”

“你看以后你只需要在轮椅发展的过程中以你的高超能力做【unsafe】相关的工作，剩下的事情训练过的猴子都能干，是不是很棒啊？”

“你为什么要走？兄弟？什么？你为什么要砸了它？”

*****

####  小野賢章  
##### 31#       发表于 2025-2-12 10:04

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399873&amp;ptid=2245923" target="_blank">厨具战士mk2 发表于 2025-2-12 08:57</a>

提到rust听到的大多都是重写，rust有没有自己的拳头应用？</blockquote>
从流行程度来看应该是 deno 和 Tauri，我自己用的最多的是 ripgrep，不过从功能来看这几个也都是广义重写，

排版软件 Typst 应该算原创<img src="https://static.saraba1st.com/image/smiley/face2017/067.png" referrerpolicy="no-referrer">

*****

####  カタカナジゴク  
##### 32#       发表于 2025-2-12 10:09

<img src="https://static.saraba1st.com/image/smiley/face2017/037.png" referrerpolicy="no-referrer">毕竟他们都写rust了<img src="https://p.sda1.dev/21/c16b2a8c35cbc2d3c36de9c24d01f4e9/image.jpg" referrerpolicy="no-referrer">

—— 来自 [鹅球](https://www.pgyer.com/xfPejhuq) v3.3.96-alpha

*****

####  迷路的石头  
##### 33#       发表于 2025-2-12 10:11

<blockquote>ryanz 发表于 2025-2-11 20:20
这两者的矛盾本来就是不可调和的，最开始 rust 爱好者拿进内核来吹就觉得此事不长久。rust 需要 kernel 来 ...</blockquote>
所以需要rust码农直接重写个runix

*****

####  montanaB  
##### 34#       发表于 2025-2-12 10:23

<blockquote>YoumuChan 发表于 2025-2-12 09:36
因为通过Rice Theorem(莱斯定理)可以证明你不可能构造一个编译器使其接受所有内存安全的程序并拒绝所有内 ...</blockquote>
既然从原理上就已经做不到了，那rust花费如此大的代价，就更不合算了。这套设计本来就对程序员的负担心智过重。我以前并不了解你说的这个原理，只是从直觉上觉得，无论是设计还是使用上，都付出了如此大的代价，却还是留下了不安全的后门，这不合理。现在你的说法更加坚定了我的想法：rust吹嘘的这套安全机制，并不能如他所说的那样，解决所有安全问题，他本质就跟Java语言的gc一样，是个为大部分场景设计的工具而已，但是Java的gc用起来很方便，你rust的安全系统，使用起来代价太大了

*****

####  montanaB  
##### 35#       发表于 2025-2-12 10:25

<blockquote>小止 发表于 2025-2-12 09:37
按我理解用rust那套东西确实是可以实现所有功能，但是心智负担可能会增加到惊人的程度 ...</blockquote>
如果真的能，那rust就不会为这套安全机制留个后门。楼上那位已经从理论上说明了，这套机制确实解决不了所有问题，只是一个子集，所以才留下unsafe的后门。

*****

####  r_ex  
##### 36#       发表于 2025-2-12 10:30

还是Rust自己写个内核吧。混合的东西确定不好

—— 来自 [鹅球](https://www.pgyer.com/GcUxKd4w) v3.3.96

*****

####  abcxiawei  
##### 37#       发表于 2025-2-12 10:34

 本帖最后由 abcxiawei 于 2025-2-12 10:39 编辑 
<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67400314&amp;ptid=2245923" target="_blank">Steel.Haze 发表于 2025-2-12 09:56</a>

坚决抵制Rust作为内核。它针对内核开发，除了所谓的捕风捉影的"内存安全"之外，全无任何比较优势，缺点却很 ...</blockquote>
如果rust真的能彻底解决内存安全问题，我不介意它代替其它语言，毕竟内存安全是个非常麻烦的问题。

问题恰恰是rust解决不了内存安全问题。我以前仅仅是直觉上觉得如此——你rust真能解决内存安全问题为什么要留unsafe后门呢？

现在好了，楼上有个理论大拿直接从定理证明，能彻底解决内存安全的编译器至少目前不存在！

那你rust花了那么大代价——无论是设计还是使用上——程序员用起你这个安全系统痛苦万分，付出如此大的代价后，发现你这东西其实是个半拉子，根本构建不起吹嘘的【彻底解决内存安全问题】的宏大叙事，那意义何在？

解决内存安全的半拉子工程现在就有样板：各个带有内存回收的语言，人家也是半拉子，解决不了所有内存安全问题，问题是人家这个半拉子给程序员用起来没有心智负担啊。

rust没戏，我以前只是直觉觉得如此，看了26楼那位大佬从基础理论论述为啥rust必须留unsafe后门后，我现在反而更坚定了这点。

*****

####  Steel.Haze  
##### 38#       发表于 2025-2-12 10:49

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67400650&amp;ptid=2245923" target="_blank">abcxiawei 发表于 2025-2-12 10:34</a>

如果rust真的能彻底解决内存安全问题，我不介意它代替其它语言，毕竟内存安全是个非常麻烦的问题。</blockquote>
是的，我也觉得肯定解决不了，内存安全怎么能单靠换个语言写法就搞定。不光是unsafe问题。编写的逻辑错误、FFI 交互等等都是不可避免的。

而且原则上，我觉得编译越麻烦的语言框架解决起来越难。所以现在的Linux的内核已经是一种接近逻辑、应用需求和简洁度相对自洽的状态。一旦混入Rust，那么可能造成的污染和带来的问题非常不可测。现在内核核心子系统（如调度、内存管理）高度依赖C语言实现的复杂数据结构与宏，Rust的强类型系统和所有权模型难以直接兼容，需通过大量 unsafe代码桥接，削弱安全性优势，甚至直接操作MMIO寄存器也要unsafe实现。本质上，引入混用，将直接给Linux内核在内存安全上开口子，而不是增强。而Linux内核层突破其实一直是美国情报机构想要“更便利”解决的一个问题。

而且本质上，目前unsafe代码需人工验证其正确性，但内核规模的代码库中，此类代码的交互可能引入难以追踪的底层问题。引入Rust后，实际上这部分安全性就拿捏到代码提交者手上，本质上这个也是一种“夺权”。

*****

####  a317216007  
##### 39#       发表于 2025-2-12 10:59

<img src="https://static.saraba1st.com/image/smiley/face2017/048.png" referrerpolicy="no-referrer">所以如果rust真的那么牛逼，为什么不直接重构一个内核分支去证明自己牛逼，而是老想着鹊巢鸠占

说白了这件事就根本不是技术驱动而是利益驱动罢了

*****

####  d2loader  
##### 40#       发表于 2025-2-12 11:00

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67400650&amp;ptid=2245923" target="_blank">abcxiawei 发表于 2025-2-12 10:34</a>
如果rust真的能彻底解决内存安全问题，我不介意它代替其它语言，毕竟内存安全是个非常麻烦的问题。</blockquote>
只是对你个人而已觉得心智负担大吧

但是新成长起来的00后码农很多人都会

—— 来自 [鹅球](https://www.pgyer.com/GcUxKd4w) v3.3.96


*****

####  d2loader  
##### 41#       发表于 2025-2-12 11:01

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67400901&amp;ptid=2245923" target="_blank">a317216007 发表于 2025-2-12 10:59</a>
所以如果rust真的那么牛逼，为什么不直接重构一个内核分支去证明自己牛逼，而是老想着鹊巢鸠占

说白了这件 ...</blockquote>
redoxOS项目并没有停止开发

—— 来自 [鹅球](https://www.pgyer.com/GcUxKd4w) v3.3.96

*****

####  takitaki  
##### 42#       发表于 2025-2-12 11:02

不知道为什么，rust爱好者越赞美rust，我越觉得这玩意后门多的数不胜数<img src="https://static.saraba1st.com/image/smiley/face2017/009.gif" referrerpolicy="no-referrer">


*****

####  manysun  
##### 43#       发表于 2025-2-12 11:08

rust崩溃论：unsafe
rust威 胁论：进Linux内核

然后每天用RIIR的东西。

*****

####  YoumuChan  
##### 44#       发表于 2025-2-12 11:14

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67400650&amp;ptid=2245923" target="_blank">abcxiawei 发表于 2025-2-12 10:34</a>

如果rust真的能彻底解决内存安全问题，我不介意它代替其它语言，毕竟内存安全是个非常麻烦的问题。</blockquote>
我觉得”如果一门语言无法完全解决内存安全问题，则无意义“是一个比较极端的想法。

对于C/C++来说，可以认为全部文件所有地方都是unsafe，所以内存安全问题可以出现在任意文件的任意地方。

rust的理念是，如果所有unsafe的地方都是sound的，那么编译器可以证明所有没有unsafe的地方一定也都是sound的。tradeoff是没有unsafe的地方会有一些比较严格的生命周期限制。

其实这种渐进的改进是有益的，毕竟缩小了攻击介面，一是绝大部分的business logic都不会有unsafe，unsafe一般占比是很小的。二是unsafe是一个显式的标志，很容易grep出来。那么做audit的时候可以集中考虑unsafe的部分，debug的时候也可以比较容易定位unsafe。

我写了快10年C/C++后来接触rust，我觉得rust把一些写C/C++脑子里需要自己维护的东西（生命周期）显性地表示出来其实反而降低了一些心智负担。据我观察，在C/C++中踩过的坑越多，对于rust上手越快。


*****

####  abcxiawei  
##### 45#       发表于 2025-2-12 11:16

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67400911&amp;ptid=2245923" target="_blank">d2loader 发表于 2025-2-12 11:00</a>

只是对你个人而已觉得心智负担大吧

但是新成长起来的00后码农很多人都会</blockquote>
又是这套“我头脑比你强”逻辑。

我自己也是程序员出身的。我已经不止一次看到你们这种逻辑了，越年轻的程序员往往越有这种自信。

可是朋友，心智负担这个东西，不是看人聪明不聪明，是看你用的编程工具方便不方便来比较的。

在一大票解决内存安全半拉子语言自带的内存回收面前，你rust那花里胡哨的设计，就是心智负担过重，作为工具，内存回收用起来难道不比rust那套所有权机制简单方便？

当汽车全部标配方向盘液压助力的时候，你开个没有方向盘助力的车，并向开有助力的司机表示：是你自己觉得方向盘重不好转吧，新成长起来的年轻人转的很好啊。。。

编程这个东西，从发展到现在，越来越偏向一个工具，工具就是要越简单，越多人能用为好，如果一个工具发明出来，解决问题的效果和其他工具区别不大，反而用起来难了很多，那它对使用者就是负担。这个不以使用者自身能力如何而决定。

上世纪80年代的时候，学术界曾经争论过HaskWell和C语言，谁会是新时代的主宰，那会几乎所有的专业人士，都更看好HaskWell，当时有个说法，说“HaskWell是给聪明人的设计，而C语言简陋，是为愚笨的人的设计”。最后如何呢，更“简陋”的C语言征服了世界，因为普通人用C语言比用HaskWell要容易的多


*****

####  abcxiawei  
##### 46#       发表于 2025-2-12 11:27

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401032&amp;ptid=2245923" target="_blank">YoumuChan 发表于 2025-2-12 11:14</a>

我觉得”如果一门语言无法完全解决内存安全问题，则无意义“是一个比较极端的想法。

对于C/C++来说，可以 ...</blockquote><blockquote>如果一门语言无法完全解决内存安全问题，则无意义</blockquote>不，你曲解了我的话，我不是认为没意义。而是，你不能付出如此巨大的代价后，最后实现的效果和别人家更简单的方式差不多。

rust这套机制，它实际不是解决问题，它是把新问题暴露在编译前，你作为一个已经写了10多年C、C++的人，对C系内存管理的弱点非常熟悉，所以你用rust，会有一种太好了，这玩意把问题在编译前暴露给我了，你肯定会觉得找到知己了。

但是对于没有这方面经验的人来说，第一步就被拦住了。

rust并没有解决问题，它只是把入门门槛抬起来，直接不让没有经验的人进来而已。

这看起来很美好，但是其实它把自己的路给堵了。我前面说，HaskWell和C语言的历史争论，最后是“更简陋，更为愚笨的人设计”的C语言赢了的


*****

####  abcxiawei  
##### 46#       发表于 2025-2-12 11:27

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401032&amp;ptid=2245923" target="_blank">YoumuChan 发表于 2025-2-12 11:14</a>

我觉得”如果一门语言无法完全解决内存安全问题，则无意义“是一个比较极端的想法。

对于C/C++来说，可以 ...</blockquote><blockquote>如果一门语言无法完全解决内存安全问题，则无意义</blockquote>不，你曲解了我的话，我不是认为没意义。而是，你不能付出如此巨大的代价后，最后实现的效果和别人家更简单的方式差不多。

rust这套机制，它实际不是解决问题，它是把新问题暴露在编译前，你作为一个已经写了10多年C、C++的人，对C系内存管理的弱点非常熟悉，所以你用rust，会有一种太好了，这玩意把问题在编译前暴露给我了，你肯定会觉得找到知己了。

但是对于没有这方面经验的人来说，第一步就被拦住了。

rust并没有解决问题，它只是把入门门槛抬起来，直接不让没有经验的人进来而已。

这看起来很美好，但是其实它把自己的路给堵了。我前面说，HaskWell和C语言的历史争论，最后是“更简陋，更为愚笨的人设计”的C语言赢了的


*****

####  云卷花开  
##### 47#       发表于 2025-2-12 11:38

编辑。。。


*****

####  darklinden  
##### 48#       发表于 2025-2-12 11:51

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401158&amp;ptid=2245923" target="_blank">abcxiawei 发表于 2025-2-12 11:27</a>

不，你曲解了我的话，我不是认为没意义。而是，你不能付出如此巨大的代价后，最后实现的效果和别人家更简 ...</blockquote>
恰恰相反，你看到的“高门槛”在目前ai助手满地的情况下根本不是事儿

ai满嘴胡话的情况下，rust编译器的小皮鞭抽着更容易写出健壮代码，而gc语言闹oom的几率则是**（糊哩哗啦）增加的

00后随便拉个无经验和ai聊天用rust做小脚本儿还能调优根本不是事儿，反而写着测试着没事儿跑一两天崩了才是头疼玩意儿

时代变了，老哥
<img src="https://static.saraba1st.com/image/smiley/face2017/002.png" referrerpolicy="no-referrer">


*****

####  abcxiawei  
##### 49#       发表于 2025-2-12 12:03

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401345&amp;ptid=2245923" target="_blank">darklinden 发表于 2025-2-12 11:51</a>

恰恰相反，你看到的“高门槛”在目前ai助手满地的情况下根本不是事儿

ai满嘴胡话的情况下，rust编译器的小 ...</blockquote>
那我们就继续看，看rust到底能不能在这个领域把C和C++的地盘侵蚀掉好了。

AI可以教人写rust脚本，照样可以教C和C++脚本，而且，越没门槛，AI教的越好，这是我的判断

*****

####  ryanz  
##### 50#       发表于 2025-2-12 12:07

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401345&amp;ptid=2245923" target="_blank">darklinden 发表于 2025-2-12 11:51</a>

恰恰相反，你看到的“高门槛”在目前ai助手满地的情况下根本不是事儿

ai满嘴胡话的情况下，rust编译器的小 ...</blockquote>
这种涉及借用权的恰恰 ai 可能绕不过那么多弯。昨天遇见群里有人问一个问题就顺道去问了 ai 

can the code run

fn main() {

    let mut v = vec![1, 3, 4, 5]; 

    v[v.len() - 1] = 4; 

    println!("{:?}", v); 

} 

ai 答错了，而正确的解答在这里 [https://users.rust-lang.org/t/ca ... ed-as-mutable/85785](https://users.rust-lang.org/t/cannot-borrow-as-immutable-because-it-is-also-borrowed-as-mutable/85785) 作为老早就在我书签里 2022 年的问答它应该学习到才对。


*****

####  redbuck  
##### 51#       发表于 2025-2-12 12:15

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399968&amp;ptid=2245923" target="_blank">montanaB 发表于 2025-2-12 09:10</a>
Rust这玩意儿最奇葩的是，搞了一大堆，各种概念，各种限制，来保证所谓的内存安全性。但是在这些东西之外 ...</blockquote>
逃生窗肯定要留的，这不算啥黑点

*****

####  Vacuolar  
##### 52#       发表于 2025-2-12 12:17

这个吵了得有两年了吧


*****

####  IIIIIlllllIIIII  
##### 53#       发表于 2025-2-12 12:20

<img src="https://static.saraba1st.com/image/smiley/face2017/018.png" referrerpolicy="no-referrer">
经典笑话之评论c和rust 哪个好
答案是高级c++
“我不知道 因为我用concepts和constexpr”

— from [S1 Next Goose](https://www.pgyer.com/GcUxKd4w) v3.3.96


*****

####  d2loader  
##### 54#       发表于 2025-2-12 12:41

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401158&amp;ptid=2245923" target="_blank">abcxiawei 发表于 2025-2-12 11:27</a>

不，你曲解了我的话，我不是认为没意义。而是，你不能付出如此巨大的代价后，最后实现的效果和别人家更简 ...</blockquote>
大哥, 你用C/C++上班工作一样要开各种静态检查和santinizer的, 还有调试必须会valgrind和gdb这些

你都会这么多东西了看看rust上手很容易的, 使用也不复杂

*****

####  白日依山尽  
##### 55#       发表于 2025-2-12 12:42

rust是面向老板编程，各类问题都要考虑到处理好，不然都跑不起来，一旦跑起来后续出现的问题几率相对小，不增减功能完全可以把程序员开了。

C之类就相反，把主要逻辑走通，跑起来再说，后面有问题再慢慢修，或许很久才出现当时没预计到的问题，不过这个时候可能程序员都已经换几个公司了。


*****

####  darklinden  
##### 56#       发表于 2025-2-12 12:45

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401446&amp;ptid=2245923" target="_blank">ryanz 发表于 2025-2-12 12:07</a>

这种涉及借用权的恰恰 ai 可能绕不过那么多弯。昨天遇见群里有人问一个问题就顺道去问了 ai 

can the cod ...</blockquote>

对于应用来说...ai应该...还行？

<img src="https://img.saraba1st.com/forum/202502/12/124352ie6jbi2ee63vje9x.png" referrerpolicy="no-referrer">

<strong>wtf.png</strong> (39.88 KB, 下载次数: 0)

下载附件

2025-2-12 12:43 上传


*****

####  ryanz  
##### 57#       发表于 2025-2-12 12:57

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401733&amp;ptid=2245923" target="_blank">darklinden 发表于 2025-2-12 12:45</a>

对于应用来说...ai应该...还行？</blockquote>
公司禁止用 copilot 不太了解关于它修复代码的原理，猜测可能因为编辑器的 linter 告诉 copilot 它才知道错了，这个猜测不一定对。直接拿这段代码问过 deepseek 和 chatgpt，它们都认为可以得到结果。

*****

####  YoumuChan  
##### 58#       发表于 2025-2-12 12:57

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401158&amp;ptid=2245923" target="_blank">abcxiawei 发表于 2025-2-12 11:27</a>

不，你曲解了我的话，我不是认为没意义。而是，你不能付出如此巨大的代价后，最后实现的效果和别人家更简 ...</blockquote>
那么你可以说rust有很陡峭的学习曲线，但我觉得跟加强心智负担是有区别的。

而C/C++也只不过是把rust陡峭的部分，藏在一次次的segmentation fault，gdb和asan中而已。

我个人其实觉得语言学习的第一门语言不应该是rust，先C/C++起手，延迟一小段时间再开始rust其实对于语言之间的tradeoff会有更好的理解。而跟rust编译器搏斗学到的生命周期，反过来对于写C/C++也是有帮助的，可以对于写C/C++潜移默化学到的内存安全规则形成更系统的理解。


*****

####  bcxzzz  
##### 59#       发表于 2025-2-12 13:03

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399968&amp;ptid=2245923" target="_blank">montanaB 发表于 2025-2-12 09:10</a>
Rust这玩意儿最奇葩的是，搞了一大堆，各种概念，各种限制，来保证所谓的内存安全性。但是在这些东西之外 ...</blockquote>
对于这种后出来的语言，美国的棱镜计划之类的，会不会直接在编译器里埋后门？

—— 来自 HUAWEI LIO-AL00, Android 12上的 [S1Next-鹅版](https://github.com/ykrank/S1-Next/releases) v2.5.4


*****

####  Jet.Black  
##### 60#       发表于 2025-2-12 13:08

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401866&amp;ptid=2245923" target="_blank">bcxzzz 发表于 2025-2-12 13:03</a>

对于这种后出来的语言，美国的棱镜计划之类的，会不会直接在编译器里埋后门？

—— 来自 HUAWEI LIO-AL0 ...</blockquote>
肯定有啊，美国政府强推Rust，你以为他们真关心技术啊。

<img src="https://static.saraba1st.com/image/smiley/face2017/043.png" referrerpolicy="no-referrer">


*****

####  d2loader  
##### 61#       发表于 2025-2-12 13:15

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401893&amp;ptid=2245923" target="_blank">Jet.Black 发表于 2025-2-12 13:08</a>

肯定有啊，美国政府强推Rust，你以为他们真关心技术啊。</blockquote>
你们到底在胡说什么啊.... 华为是唯一非美国的rust基金会白金赞助商

而且servo项目被华为接过来了准备以后做鸿蒙webview的底层, 做自己掌控的浏览器

<img src="https://static.saraba1st.com/image/smiley/face2017/003.png" referrerpolicy="no-referrer">


*****

####  Jet.Black  
##### 62#       发表于 2025-2-12 13:26

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401936&amp;ptid=2245923" target="_blank">d2loader 发表于 2025-2-12 13:15</a>

你们到底在胡说什么啊.... 华为是唯一非美国的rust基金会白金赞助商

而且servo项目被华为接过来了准备以 ...</blockquote>
想表达啥？华为又不是神，傻逼事情可没少干。

美国政府几次三番强推Rust不是新闻了，没有其他目的我是不信的。


*****

####  白笛之音  
##### 63#       发表于 2025-2-12 13:30

作为modern c++的用户，我能理解rust要干什么，但我觉得他们的解决方式不甚雅观（当然c++可能有不雅观的部分和历史包袱）

深入到实际的软件工程，rust带来的不甚可靠的安全性就未必值得给linux这样的成熟项目额外带来工程上的复杂度了。


*****

####  montanaB  
##### 64#       发表于 2025-2-12 13:37

<blockquote>redbuck 发表于 2025-2-12 12:15
逃生窗肯定要留的，这不算啥黑点</blockquote>
rust如果不吹它那一套“”彻底解决内存安全问题“”那这就不是黑点。问题是rust天天在吹这个，那这个逃生窗就成了个笑话

*****

####  montanaB  
##### 65#       发表于 2025-2-12 13:37

<blockquote>bcxzzz 发表于 2025-2-12 13:03
对于这种后出来的语言，美国的棱镜计划之类的，会不会直接在编译器里埋后门？

—— 来自 HUAWEI LIO-AL0 ...</blockquote>
你谈的是另外一个层面的问题


*****

####  abcxiawei  
##### 66#       发表于 2025-2-12 13:43

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401825&amp;ptid=2245923" target="_blank">YoumuChan 发表于 2025-2-12 12:57</a>

那么你可以说rust有很陡峭的学习曲线，但我觉得跟加强心智负担是有区别的。

而C/C++也只不过是把rust陡峭 ...</blockquote>
没心智负担怎么会那么多和编译器搏斗的笑话？你别和我说这都是程序员水平不行造成的，当一个工具开始使劲强调使用者的水平的时候，它的竞争力就要下降了。

不好用就是不好用，不用给工具找理由。

要解决内存安全性问题的初衷没有错，但是rust的这个解法肯定是有问题的，学习曲线陡，使用起来照样困难。

我没有说C/C++容易，实际上这两个语言也是以难度高，难以精通著称的。

而且：rust搞了大堆眼花缭乱的东西，难度没降低，最终也没解决内存安全问题。然后声称要取代C/C++。。。

rust只是用一个问题掩盖另外一个问题，这个搞法从方法论上来说就不对。

*****

####  ywydsd  
##### 67#       发表于 2025-2-12 13:43

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67399968&amp;ptid=2245923" target="_blank">montanaB 发表于 2025-2-12 09:10</a>
Rust这玩意儿最奇葩的是，搞了一大堆，各种概念，各种限制，来保证所谓的内存安全性。但是在这些东西之外 ...</blockquote>
可能就是为了留后门

—— 来自 [鹅球](https://www.pgyer.com/xfPejhuq) v3.3.96-alpha

*****

####  万恶淫猥手  
##### 68#       发表于 2025-2-12 13:45

Rust 粉和 NodeJS 粉已经快接近之前的 PHP 了<img src="https://static.saraba1st.com/image/smiley/face2017/053.png" referrerpolicy="no-referrer">


*****

####  abcxiawei  
##### 69#       发表于 2025-2-12 13:49

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401711&amp;ptid=2245923" target="_blank">d2loader 发表于 2025-2-12 12:41</a>

大哥, 你用C/C++上班工作一样要开各种静态检查和santinizer的, 还有调试必须会valgrind和gdb这些

你都会 ...</blockquote>
我没觉得C/C++简单，本来这就是两个难以学习和精通的语言。

所以我也不觉得rust容易。

问题是rust搞了这么多东西后，内存安全问题没有解决啊。

用rust的和编译器搏斗的困难，取代和C/C++的各种漏内存，异常等搏斗的困难，最后，内存安全问题还是没有解决。

为啥要换呢？找不到足够的理由啊。

你愿意换是你的自由。但我觉得当一个语言没有解决既往语言面对的问题的时候，那它的存在价值就是要打问号的。


*****

####  darklinden  
##### 70#       发表于 2025-2-12 14:15

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401819&amp;ptid=2245923" target="_blank">ryanz 发表于 2025-2-12 12:57</a>

公司禁止用 copilot 不太了解关于它修复代码的原理，猜测可能因为编辑器的 linter 告诉 copilot 它才知道 ...</blockquote>

claude, copilot一开始死不悔改说没错，但是认编译器报错，可以正确提示修改意见

ds问了死不悔改说没错，再问busy了就没试成编译器错误信息回复，理论上应该会认...

gpt不开search和reason也是死不悔改，开了就一次过...

<img src="https://img.saraba1st.com/forum/202502/12/140937qchs38dchmnac8f7.png" referrerpolicy="no-referrer">

<strong>wtf.png</strong> (280.66 KB, 下载次数: 0)

下载附件

2025-2-12 14:09 上传

﹍﹍﹍

评分

 参与人数 1战斗力 +2

|昵称|战斗力|理由|
|----|---|---|
| ryanz| + 2|欢乐多|

查看全部评分


*****

####  pigbayspy  
##### 71#       发表于 2025-2-12 14:46

写过 c++ 的人就知道 rust 有多好了

真的是彻底地把 c++ 底下哪些要自己注意的一堆隐式的东西都给你暴露出来了

虽然暴露出来的这些限制，会让完成一些东西很困难（著名的rust新手第一步写个双向链表

但是真的从工程实践上来说，规避了很多坑


*****

####  phorcys02  
##### 72#       发表于 2025-2-12 15:02

rust的问题和node一样，是 crates.io


*****

####  woodey  
##### 73#       发表于 2025-2-12 15:58

 本帖最后由 woodey 于 2025-2-12 15:59 编辑 

我知道rust很好，那为啥不用rust新做一个系统？<img src="https://static.saraba1st.com/image/smiley/face2017/001.png" referrerpolicy="no-referrer">


*****

####  Steel.Haze  
##### 74#       发表于 2025-2-12 16:27

 本帖最后由 Steel.Haze 于 2025-2-12 16:29 编辑 
<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67401032&amp;ptid=2245923" target="_blank">YoumuChan 发表于 2025-2-12 11:14</a>

我觉得”如果一门语言无法完全解决内存安全问题，则无意义“是一个比较极端的想法。

对于C/C++来说，可以 ...</blockquote>
你这个说法太理中客。且不说换内核的整体工程代价。这种集中化模式其实增加易于被几种攻击的点而已。你只是初摸rust觉得好上手问题。这个主题讨论的是用rust去换linux的内核和混入内核，不是写个小应用。这个前提问题就不一样。rust这个架构必然是只是一种“过客”语言，一种语言有个局部优势就去奉若神明，甚至拿去替换核心OS的内核，然后这个漫长的工程推进中，它本身就已经过时了，变成了一种不上不下漏洞明显的产物。这样的语言我们见得还少吗？rust又不是最近才出来的吧？它真有竞争力早该被主动在内核领域开始应用了。不需要这么激烈的碰撞来推动。反而rust在话题热度了一段时间后被很多人抛弃了，是最近又被翻出来炒作吧，为了配合混入linux内核和替代部分其它内核与底层程序在炒作吧？而且有美国政府参与推动吧？为什么呢？


*****

####  yvev  
##### 75#       发表于 2025-2-12 17:20

这怎么从rust不能进内核歪到rust是天下第一cjb语言了。反正rust再怎么烂也还是“现代语言”，至于能不能进内核，反正c++进不去<img src="https://static.saraba1st.com/image/smiley/face2017/067.png" referrerpolicy="no-referrer">


*****

####  d2loader  
##### 76#       发表于 2025-2-12 17:42

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67403526&amp;ptid=2245923" target="_blank">Steel.Haze 发表于 2025-2-12 16:27</a>
你这个说法太理中客。且不说换内核的整体工程代价。这种集中化模式其实增加易于被几种攻击的点而已。你只 ...</blockquote>
<img src="https://static.saraba1st.com/image/smiley/face2017/003.png" referrerpolicy="no-referrer">
根本不是你说的能阻止或者禁止的，现在是个人按照教程就能用rust写内核驱动

—— 来自 [鹅球](https://www.pgyer.com/GcUxKd4w) v3.3.96


*****

####  samfs  
##### 77#       发表于 2025-2-12 17:47

非计算机专业，图一乐的话，rust 值得学吗，和 C 比呢

*****

####  ryanz  
##### 78#       发表于 2025-2-12 17:50

<blockquote>samfs 发表于 2025-2-12 17:47
非计算机专业，图一乐的话，rust 值得学吗，和 C 比呢</blockquote>
图一乐现在学 python 玩最火的 ai 吧。


*****

####  yxz_00  
##### 79#       发表于 2025-2-12 17:55

Rust是一门很值得学的语言. 写了几千行rust之后再回去写C++我感觉到了自己的功力提升 (我有10年C++经验)

然而Rust过于复杂了, 说简单的人我打赌它们没有认真设计过一个跨线程的rust框架, 或者就是很多流氓ruster说的那种, "搞不懂生命周期? 拷贝就行."

另外, rust的宏对我来说比C的宏还难以阅读.

这么复杂的一个语言生产力是存疑的, 他能吸引的智力也是存疑的. 我想这也是为什么至今rust还没有自己拿的出手的大应用. 而是热衷于跑去重写别人的系统来证明自己. 

同时既要面对现实需求的复杂度, 又要面对语言本身的复杂度, 再牛逼的人都会心累. 重写至少只用面对后者.

至于说什么AI帮忙, AI如果写rust牛逼, 写C++只会更牛逼.


*****

####  bcxzzz  
##### 80#       发表于 2025-2-12 18:02

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67402093&amp;ptid=2245923" target="_blank">montanaB 发表于 2025-2-12 13:37</a>

你谈的是另外一个层面的问题</blockquote>
从技术上来说，可能给一种语言留后门么？ 比如考虑下：1、语言的解释器、编译器是公开代码的么？ 2，即使在语言中留了某个后门，怎么让它在预定的地方起作用？  从技术上说，这能实现不？


*****

####  我是蓝石头  
##### 81#       发表于 2025-2-12 18:10

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67404180&amp;ptid=2245923" target="_blank">samfs 发表于 2025-2-12 17:47</a>
非计算机专业，图一乐的话，rust 值得学吗，和 C 比呢</blockquote>
建议python，一个上午就可以零到一写一个简单的有监督机器学习训练加推理，感受朴素的机器学习乐趣。
再花一个下午可以零到一部署一个带前端，带后端，带数据库，甚至还有api看板的全栈应用。
再花一个上午，把自带的文件上传接口后面接上刚训练的那个模型的推理，好了，你有了一个图片分类站点<img src="https://static.saraba1st.com/image/smiley/face2017/172.png" referrerpolicy="no-referrer">


*****

####  非教徒  
##### 82#       发表于 2025-2-12 18:57

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67404353&amp;ptid=2245923" target="_blank">我是蓝石头 发表于 2025-2-12 18:10</a>

建议python，一个上午就可以用pytorch零到一写一个简单的有监督机器学习训练加推理，感受朴素的机器学习 ...</blockquote>
来个教程的链接啊...


*****

####  iamawaistcoat  
##### 83#       发表于 2025-2-12 18:58

<blockquote><a href="httphttps://bbs.saraba1st.com/2b/forum.php?mod=redirect&amp;goto=findpost&amp;pid=67404297&amp;ptid=2245923" target="_blank">bcxzzz 发表于 2025-2-12 18:02</a>

从技术上来说，可能给一种语言留后门么？ 比如考虑下：1、语言的解释器、编译器是公开代码的么？ 2，即使 ...</blockquote>
和npm一样，在cargo拉进来的那一堆依赖里面？

*****

####  Xerxes_2  
##### 84#       发表于 2025-2-12 19:03

看这个帖子就高潮的人是不是根本对前情没有一点了解就来输出的？

首先 Rust 进 Linux 是 Linus 本人首肯的，C++都没进

其次前几个月在 Rust4Linux 会议上有 C 的支持者当众指着鼻子骂，这才是这些纷争的导火索

