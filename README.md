**基本介绍**

开头预警：本mod是dol游戏的罗宾扩展mod，制作方向是成就一个独立的，高自信的，甚至可以保护pc的罗宾，mod目前只是一个开头，只有部分功能的雏形，且十分简陋！所以readme也写得很随意...

目前已实现的功能详情可以下载仓库中"现存功能截图说明.docx"（截图说明目前版本已经滞后了，等做出一个基础版本后会统一更新，见谅），具体的文本和构想请下载"罗宾mod文本和构想整理.txt"（此文档每次提交同步更新），现有代码可直接在"game"文件夹下查看，在百度贴吧中也会更新制作过程。（贴吧账号：零环零理想）

本mod基于最新的0.4.7.5版本进行自测，旧版本可能会有不兼容的问题。

安装方式：下载release下0.0.2-temp中的domRobin.mod.zip，用平时玩游戏用的mod管理器加载完汉化mod后，再加载此mod，安装前记得保存自己的存档码，以防止出现bug无法恢复。

备注：0.0.2-temp和0.0.1-temp目前的区别只有 10.新增特质「被罗宾守护」（见下文），此特质的逻辑性改动有一点大，可能需要多测试。

**请忽略release显示的上传时间，domRobin.mod.zip是会随readme同步更新的！**

**不正经的补充**

按理说这种刚开始做的mod不应该公开，但作者比较浮躁，做了一点点功能就急着分享...总之见谅！

作者是新手，代码和文笔甚至思维都很糟糕的那种，如果各位不嫌弃的话请提供bug测试以及文本/功能上的建议（意见），甚至（需要捏着鼻子看的）code review
（完了我感觉我完全是来白嫖的，赶紧划掉这句）

扣扣群号：789448964

**致谢**

感谢 Robin's GF 对mod的具体设定的构想以及文本创作，目前的构想是我们俩共同讨论出的结果。

感谢 @Nephthelana在最开始提供的代码修改！以及贴吧吧友提供的部分文本。

感谢各位d级人员的试玩和bug反馈：（暂时列贴吧ID）无敌可爱乐园，kid1412870，空灵cream。

**目前进度**

（会持续更新，以下功能只做过基本的自测，且文本未经打磨，非最终版本，更详细的介绍请查看"现存功能截图说明.docx"）：

1. 柠檬水摊升级功能雏形（文本已更新），知道罗宾的债务问题后去柠檬水摊开启选项，升级成功后可实现每周存款增加，「买柠檬水」和「提供帮助」时增加防雨和防晒功能，且可使用当前拥有的水果尝试榨汁，成功后下周饮料单上会增加新饮料。

2. 热巧克力摊改造/升级功能（升级过柠檬水摊时选项展示为「改造」), 改造/升级成功后可实现每周存款增加，「买热巧克力」和「提供帮助」时增加防雪功能，且保留榨汁机和购买新饮料（热饮）功能。

* 柠檬水摊/热巧克力摊升级后，可以触发下列新增商品：
（1）和罗宾触发去电影院买爆米花，可以建议罗宾售卖爆米花，注意此功能与让气球摊摊主帮助罗宾互斥。
（2）孤儿院阁楼解锁厨房后，可触发高自信罗宾主动售卖小点心。
（3）让罗宾帮忙浇花且pc手上的鲜花超过两种后，可以建议罗宾帮忙卖花，每周都会根据罗宾的自信随机消耗拥有的鲜花并与罗宾平分卖花的收益。（某两种花除外）
（4）气球摊摊主出场后，可以建议罗宾售卖气球，注意此功能与让气球摊摊主帮助罗宾互斥。

3. 去柠檬水摊时pc身上如果带有柠檬/血柠/野蜂巢，可以直接送给罗宾带来当周的存款增长，不需要前置条件。送野蜂巢后，当周「买柠檬水」选项会改为「买蜂蜜柠檬水」，且有文本细节变化。
  
4. 为罗宾推荐家教工作雏形，知道罗宾的债务问题后，pc去多瑙河街做家教时开启选项，需要随机到等级A以上的学科才能推荐成功，推荐成功后可以去找罗宾沟通，之后罗宾每天上学日15:06到16:20将位于多瑙河街，想放学后一起回家/触发校门口事件的pc要抓紧时间！
   
5. 修改了罗宾债务的计算逻辑为和pc一样每周递增，一旦罗宾无力支付就会触发惩罚（原游戏逻辑是每周加进度，不是直接计算的金额），新开局无任何额外干预的情况下，原设定的罗宾28天后卖游戏机，35天后被卖码头可以正常触发。

6. 修改了原作「拥抱」后「哭泣」无法触发创伤察觉的bug，为承担债务后「要钱」的文本增加高自信差分

7. 新增特质「同舟共济—罗宾」，罗宾固定周收入达到2000时周日会有提示，收到提示去罗宾的房间拿特质，效果为pc每日压力创伤减少，罗宾自信永远不会低于50（作弊也不行）
* 注意：此时pc不再承担罗宾的债务，所有以此为前提的剧情（包括告白信）都将无法触发，已经成为恋人的话没有影响，之后会慢慢补上新版告白信等差分剧情
* 注意2：新增特质的版本装上后会偷偷计算pc为罗宾承担的债务总数，之后会有还钱剧情的
* 注意3：新增成就——同舟共济，如果已经拿到过该特质，请使用魔法（不要问我为什么不写一个自动更新，逃）：
<<link [[手动获取同舟共济成就|$passage]]>><<earnFeat "In the Same Boat">><</link>>

8. 新工作—直播的雏形，知晓罗宾的债务问题后，「看罗宾玩游戏」时有20%概率触发灵感，需要罗宾或pc存款足够才会展示提议选项，成功后罗宾每周存款递增且会随机收到打赏，且每天晚上八点到九点将处于直播状态，诡术判定成功后可以偷看罗宾的直播内容。

9. 新工作—摄影的雏形，罗宾自信达标后，与罗宾野餐时可触发选项，可自己按提示准备服装也可穿罗宾（随机）赠送的服装，摄影收益会根据pc当周是否参与摄影/某两项属性是否达标而变化，pc参与摄影时会与罗宾平分收益。

10. 新特质——被罗宾守护，罗宾每周固定收入达标后出现提示，之后可通过租金战斗失败/拥抱时倾诉创伤两种方式触发特质和对应成就，该特质详细效果如下：
   
* pc每日压力减少2000（上限的五分之一，平时减压12/24那些都是乘以系数80的，所以没有特别夸张），
创伤根据自控减少75到112点（与另两种特质完全一致），罗宾每日创伤额外减一
* 所有（-/--/---罗宾的自信）界面文字描述消失（实际功能当然也会消失）
* 日志中原本的收租提醒改为"你已无需支付贝利的房租。" 不会再触发收租事件。
* 罗宾每周需要支付的债务翻倍，为简化逻辑，根据罗宾当前的债务而不是pc的来算，且忽略孩子数量
（反正pc承担债务以后也是按自己要交的钱来翻倍的，所以别在意细节！）
* 各种未交租事件不会再触发，不用担心贝利帮雷米袭击农场/不能进育儿室/夜袭等问题。

11. 额外小剧情：交租战斗失败后，未达到被守护条件，但罗宾存款够付当周房租时，pc可以免受当周惩罚


**未实现的功能构想**

目前各工作雏形已有，是时候想下一步了！

一、「同舟共济」特质后续：

1. 拿到「同舟共济」特质后，罗宾存款达标后可以向承担过债务的pc还钱，买回自己的游戏机，为其他孤儿付一周钱
2. 两种特质对应的表白信要尽快补上


二、「被罗宾守护」特质获取与对应细节构想（已放雏形）:

1. 罗宾周固定收入达到4000以后，展示一次金字提示，但罗宾不会主动来承担pc债务，而需要触发条件，方式为(二选一）：
（1）高创倾诉，「哭泣」两次or「崩溃」两次即可
（2）租金战斗失败/选择顺从后，罗宾主动来承担债务
（ps: 这里可以再做一下细分，比如罗宾当前存款够交pc租金，pc免于本次惩罚，无需前置）
2. 「被罗宾守护」特质获取后，默认直接跳过交租环节，但pc仍然可以要求罗宾一起反抗贝利
3. 特质效果：锁罗宾自信100%，pc每日压力-2000（五分之一）,创伤根据自控-75~112，罗宾每日创伤额外-1


三、反抗线构想：

1. 获取「同舟共济」或「被罗宾守护」特质后，每周pc可以选择一次「说服罗宾一起反抗贝利」，罗宾同意（自信91）后进入反抗线，
反抗线会有专属的租金战斗，根据罗宾自信算攻击力，失败后罗宾仍然有机会交钱不会受惩罚。
（PS：专属战斗失败，罗宾钱够应当也可以拿「被罗宾守护」特质）
2. 同样的反抗方式会用在惠特尼食堂欺凌上，这里不用说服，直接开打就行。


四、甜甜的日常构想：

1. 温馨的约会：买望远镜，给罗宾买泳衣，日常出门新增选项:"一起观星","一起去海滩游泳"
2. 好的涩涩：半夜pc主动爬罗宾床，柠檬水摊/巧克力摊和直播时"爬到桌子底下"