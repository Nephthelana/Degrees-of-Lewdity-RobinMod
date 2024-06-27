# DomRobin扩展mod

- [基本介绍](#基本介绍)
- [安装方式说明](#安装方式说明)
- [反馈/讨论方式](#反馈/讨论方式)
- [详细内容介绍](#详细内容介绍)
    - [1. 柠檬水摊升级](#1.柠檬水摊升级)
    - [2. 三种新工作](#2.三种新工作)
    - [3. 两种新特质](#3.两种新特质)
    - [4. 反抗线](#4.反抗线)
    - [5. 日常约会](#5.日常约会)
    - [6. 对原版内容的细节修改](#6.对原版内容的细节修改)
- [数值变动详解](#数值变动详解)
    - [1. 罗宾的债务计算说明](#1.罗宾的债务计算说明)
    - [2. 罗宾的收入计算说明](#2.罗宾的收入计算说明)
    - [3. 反抗线租金战斗机制说明](#3.反抗线租金战斗机制说明)
    - [4. 特质效果说明](#4.特质效果说明)
- [致谢](#致谢)
- [未实现的功能构想](#未实现的功能构想)


## 基本介绍
本模组是dol游戏的罗宾扩展mod，制作方向是成就一个独立的，高自信的，甚至可以保护pc的罗宾，mod目前已为罗宾增加了柠檬水摊升级（榨汁机+四种新商品），三种新工作，两种新特质（以及一个反抗贝利特质），两种新约会和三种新的自愿遭遇战。模组的文本与功能仍在不断完善中，欢迎各位提供测试与建议。

模组的主线内容可以由下列四个新增成就概括：其中「同舟共济」达成条件为罗宾固定周收入超过2000；「被罗宾守护」达成条件为罗宾固定周收入超过4000，pc高创向罗宾倾诉两次以上，或者常规租金战斗/反抗线租金战斗失败；「联合作战」达成条件为反抗线2V5遭遇战成功，「万众一心」达成条件为触发反抗线剧情杀后，与曾经被帮助过的孤儿们一同反抗贝利。（可在[详细内容介绍](#详细内容介绍)中查看具体触发条件）
<details>
  <summary>点击查看图片</summary>
![新增成就](https://github.com/ZeroRing233/Degrees-of-Lewdity-RobinMod/blob/master/assets/feats.png)
</details>

模组名称补充说明：dom罗宾主要是在玩罗宾的自信在代码里是dom这个梗，同时游戏内高自信的罗宾本身就会对pc更有保护欲，在关系中也会是更占主导的一方，而在加入这个童话向/爽向的模组后，罗宾的自信甚至会被特质锁定为100，所以希望各位都是喜欢高自信罗宾的玩家。

## 安装方式说明
本模组基于当前最新版本(0.5.0.x)进行自测，旧版本会存在不兼容的问题，请确保您手上的游戏是最新版本，然后下载release下0.0.3-alpha中的domRobin.mod.zip（请不要下载source code），并使用平时游玩汉化版时使用的mod管理器加载完汉化模组后，再加载此模组。
<details>
  <summary>点击查看图片</summary>
![需要安装的文件](https://github.com/ZeroRing233/Degrees-of-Lewdity-RobinMod/blob/master/assets/download.png)
</details>

## 反馈/讨论方式
bug反馈群群号：964015275
讨论群群号：789448964（进讨论群需写50字以上角色理解）
贴吧开发过程记录贴：[试图做一个罗宾mod](https://tieba.baidu.com/p/9001189698) 
（繁中用户）作者的plurk账号：[ZeroRing](https://www.plurk.com/ZeroRing)

## 详细内容介绍
### 1. 柠檬水摊升级
#### 简介
知晓罗宾的债务问题后，去柠檬水摊可开启升级选项，升级成功后可实现每周存款增加，「买柠檬水」和「提供帮助」时增加防雨和防晒功能，且可使用当前拥有的水果尝试榨汁，成功后下周饮料单上会增加新饮料，同时可触发四种新增商品。
#### 四种新商品
* 孤儿院阁楼解锁厨房后，可触发高自信罗宾（需自信80以上）主动售卖小点心。
* 让罗宾帮忙浇花且pc手上的鲜花超过两种后，可以建议罗宾帮忙卖花，每周都会根据罗宾的自信随机消耗拥有的鲜花并与罗宾平分卖花的收益。（某两种花除外）
*  和罗宾去电影院买爆米花后，可以建议罗宾售卖爆米花，注意此功能与让气球摊摊主帮助罗宾互斥。
* 气球摊摊主出场后，可以建议罗宾售卖气球，注意此功能与让气球摊摊主帮助罗宾互斥。
#### 热巧克力摊升级
升级柠檬水摊后，冬天热巧克力摊「升级」选项会变为「改造」，且升级费用减半。热巧克力摊改造/升级成功后，「买热巧克力」和「提供帮助」时增加防雨和防雪功能，且保留榨汁机和购买新饮料（热饮）功能，也保留柠檬水摊中新增的四种商品。
#### 送柠檬/血柠/野蜂巢
（此功能无需前置条件）去柠檬水摊时pc身上如果带有柠檬/血柠/野蜂巢，可以直接送给罗宾带来当周的存款增长，送野蜂巢后，当周「买柠檬水」选项会改为「买蜂蜜柠檬水」，且有文本细节变化。
#### 自愿遭遇战补充
柠檬水摊/巧克力摊升级后，如果某个属性4级以上，且与罗宾处于恋爱关系，可以选择“爬到摊位底下"。
#### 柠檬水摊完全体示意图
<details>
  <summary>点击查看图片</summary>
![柠檬水摊完全体示意图](https://github.com/ZeroRing233/Degrees-of-Lewdity-RobinMod/blob/master/assets/complete.png)
</details>

###  2. 三种新工作
#### 家教
知晓罗宾的债务问题后，pc去多瑙河街做家教时开启选项「为罗宾推荐家教工作」，需要随机到等级A以上的学科才能推荐成功，推荐成功后可以去找罗宾沟通，之后罗宾每天上学日15:06到16:20将位于多瑙河街，想放学后和罗宾一起回家的pc要抓紧时间！

#### 直播
知晓罗宾的债务问题后，「看罗宾玩游戏」时有20%概率触发灵感，需要罗宾或pc存款足够才会展示提议选项，提议成功后罗宾每周存款递增且会随机收到打赏，且每天晚上七点到八点将处于直播状态，诡术判定成功后可以偷看罗宾的直播内容。如果某个属性4级以上，且与罗宾处于恋爱关系，可以选择在罗宾直播时「闯入」并「爬到桌子底下」。

#### 摄影
罗宾自信80以上时，在晴天与罗宾野餐后可触发选项，可自己按提示准备服装也可穿罗宾（随机）赠送的服装，摄影收益会根据pc当周是否参与摄影/某两项属性是否达标而变化，pc参与摄影时会与罗宾平分收益。

### 3. 两种新特质
#### 同舟共济
罗宾固定周收入达到2000时周日会有提示，收到提示去罗宾的房间可以直接获取特质，该特质效果为pc每日压力创伤减少，罗宾承担自己的债务，且自信锁定在50以上。（关于固定周收入的计算和特质的具体数值变动请参考[数值变动详解](#数值变动详解)）

#### 被罗宾守护
罗宾每周固定收入达到4000时周日会有提示，之后可通过常规/反抗线租金战斗失败，或者在拥抱时崩溃/哭泣两次这两种方式获取特质，该特质效果为pc每日压力创伤大幅减少，罗宾承担自己和pc的债务，每日创伤额外减一，且自信锁定在100。

#### 两种特质共同后续
* 如果pc曾替罗宾承担债务，帮助罗宾升级柠檬水摊/热巧克力摊/购买直接设备，将会触发罗宾还钱剧情。
* 罗宾会主动买回自己曾经卖掉的游戏机。
* 罗宾会替其他孤儿付一周钱，并收到受助者的回报（两者触发概率均为所有孤儿院大厅随机事件的3%)
* 会有两种不同的新告白信和接受告白场景。

#### 额外小剧情
（此剧情无前置条件）常规租金战斗失败后，未达到被守护条件，但罗宾存款够付当周房租时，pc可以免受当周惩罚。

### 4. 反抗线
#### 反抗贝利
* 获取「同舟共济」特质后，每周可以选择一次「说服罗宾一起反抗贝利」，罗宾同意（需要自信91，固定周收入超过4000）后进入反抗线。
* 反抗线每周在孤儿院大厅触发一次专属租金战斗，规则详情见[数值变动详解](#数值变动详解)。
* 战斗胜利后，获取成就「联合作战」，「被罗宾守护」特质将切换为「同舟共济」；战斗失败后，结束反抗线，「同舟共济」特质将切换为「被罗宾守护」。
* 反抗线打赢三次以上，罗宾与pc各至少帮助过一名孤儿，孤儿院的氛围「革命性」后，可触发剧情杀，剧情杀后可获取新特质「贝利的反抗者」和成就「万众一心」。
* 「贝利的反抗者」与「被罗宾守护」基础效果一致（当然，不会扣除罗宾每周的存款），且锁定孤儿院的氛围为「革命性的」。

#### 反抗惠特尼
食堂触发惠特尼欺凌事件时，罗宾自信大于91或者已经进入反抗线，将会触发新的遭遇战——双人合揍惠特尼（及其朋友），同时修改惠特尼走廊欺凌时罗宾的反应。

### 5. 日常约会
#### 观星
柠檬水摊触发相关对话，且开启孤儿院阁楼后可去购物中心购买天文望远镜，安装望远镜后新增阁楼文本描述，柠檬水摊对话更新，孤儿院大厅随机事件等细节改动，并开放观星约会剧情，约会剧情会根据季节和随机值有细微差分。

#### 海边游泳
柠檬水摊触发相关对话后可在罗宾房间向罗宾提议去海边游泳，但只有在指定时间才会触发约会选项，约会前可选择去购物中心与罗宾互送泳衣（可借此开启异装线），约会可持续一整个白天，约会结束后可在更衣室触发自愿遭遇战。

### 6. 对原版内容的细节修改
* 为承担债务后「要钱」的文本增加高自信差分。
* 晚上九点到十二点，罗宾不在学习时可主动爬罗宾床。
* 罗宾主动爬床之后会在意pc的进度。

##  数值变动详解
（普通游玩可以忽略这一节）
### 1. 罗宾的债务计算说明
为增强代入感，pc未承担债务时，原游戏中罗宾每周要交的债务被改为了和pc一致，按当前周数扣[100,300,500,700,1000,1500,2000]之一，同时修改了原游戏中按照当前进度判断是否卖游戏机/被卖码头的逻辑，改为了只有当罗宾金钱确实为负数时才会受到惩罚。若在开局未进行任何干预的情况下，原设定的罗宾28天卖游戏机，35天受到惩罚依然会正常触发。
（仍然保留进罗宾房间后才会触发第一次惩罚的机制）

### 2. 罗宾的收入计算说明
罗宾每周存款分为固定存款和随机存款，为简化逻辑，只按照固定存款是否大于2000/4000, 来判断罗宾是否有能力承担自己/pc的债务。

固定存款增加方式：
（1）柠檬水摊基础（300）+ 升级(600)+ 全饮料(300)+ 小点心（300）+ 爆米花（300）+ 气球（有爆米花200，没有150）= 2000

（2) 家教750+摄影基础550=1300

（3）游戏直播（可加入直播时唱歌吸引人气的剧情，合并特长）：按周依次增加[100,300,500,700,1000,1500,2000]，上限2000

随机存款增加方式（只要不是100%能拿到的统一被归为随机存款）：
（1）给罗宾柠檬/血柠，每周增加pc送的柠檬/血柠的价值*个数*4，然后四舍五入取整

（2）卖花，卖pc日志中的花原价中的一半（另一半要在房间触发对话，每周交给pc)，每种花按自信一周卖50/100/150, 对应自信值40/80

（3）摄影收入，与pc一起拍摄，且pc容貌3以上/或模特名声达标，罗宾与pc一人获得1100，表现为随机收入550
（PS：摄影本身有固定收入550，可以理解为pc不在罗宾去拍风景了，哈哈，pc在的话一人550总共1100,或者一人1100总共2200）

（4）直播的随机收入：当周基础*自信（百分比）+ [0，当周基础/2]之间的一个随机数


### 3. 反抗线租金战斗机制说明
（1）初始条件:贝利血量800，打手数量4人，罗宾血量在200-400之间(自信是倍率)

（2） 分配罗宾受到的攻击：1. pc有行动力的情况下，打手数量三或四时，随机两名打手打罗宾; 打手数量一或二时，随机一名打手打罗宾；打手数量为零时，贝利轮流打pc和罗宾。
pc无行动力的情况下，所有人都来攻击罗宾，反之亦然。

（3）罗宾的固定作战策略：除第一回合使用喷雾加挑衅以外，其余回合都会挑选当前血量最小，且正在攻击自己的敌人进行攻击。

（4）罗宾的攻击力：除第一回合外，默认动作为双手击打+踢+挑衅，默认罗宾英语A*，体能为中等体型满体能，自信作为倍率。所以每回合的攻击力范围是30*3-30*6（90-180）。

（5）罗宾的血量： 默认罗宾科学 A*, 效果为疼痛值 * 0.6，基础血量200，是pc疼痛上限的两倍，敌人每回合双手击打。故罗宾血量每回合扣48*正在攻击罗宾的敌人数量，每击退一名敌人罗宾回血15*2=30。血量为0时，罗宾将无法行动。

（6）罗宾的创伤：罗宾血量小于一半时，每回合创伤+1。罗宾血量小于20%时，每回合创伤+2。每击败一名敌人创伤-2。创伤对战斗过程无影响。

（7）遭遇战结束条件：敌人血量为零（胜利），或者pc和罗宾均失去行动能力（失败）。

### 4. 特质效果说明
#### 「同舟共济」效果
* pc每日压力减少500（上限的二十分之一，平时减压都是乘以系数80的，所以没有特别夸张），创伤根据自控减少75到112点，罗宾自信锁定在50以上。
* pc不再承担罗宾的债务，无法再触发创伤线。


#### 「被罗宾守护」与「贝利的反抗者」共同效果
* pc每日压力减少2000，创伤根据自控减少150到224点，罗宾每日创伤额外减一。
* 所有（-/--/---罗宾的自信）界面文字描述消失（实际功能当然也会消失）。
* 日志中原本的收租提醒内容会发生改变，不会再触发常规收租事件。
* 各种未交租事件不会再触发，不用担心贝利帮雷米袭击农场/不能进育儿室/夜袭等问题。
#### 「被罗宾守护」独有效果
* 罗宾每周需要支付的债务翻倍，为简化逻辑，根据罗宾当前的债务而不是pc的来算，且忽略孩子数量（反正pc承担债务以后也是按自己要交的钱来翻倍的，所以别在意细节！）
####「贝利的反抗者」独有效果
* 罗宾与pc均无需支付贝利的房租。
* 孤儿院的氛围锁定为「革命性的」。




## 致谢

- 感谢 Robin's GF 对mod的具体设定的构想，文本创作以及观星约会图标创作，目前的构想是我们俩共同讨论出的结果。

- 感谢 [脸木挤白/苯环](https://github.com/Nephthelana) 在mod编写之初提供的代码修改！这是本mod得以起步的基础。

- 感谢群友"蜜雪冰城分店"为观星创作的两种精美图标。（暂未实装）

- 感谢贴吧吧友"电珠皮神"在mod编写前提供的部分文本。

- 感谢各位d级人员的试玩和bug反馈：（暂时列贴吧ID）无敌可爱乐园，kid1412870，空灵cream，该昵称未存在。

- 感谢[Miyazawa](https://github.com/miyakoAki4828)对本模组的持续关注以及对游戏图片格式的说明。

- 感谢 [脸木挤白/苯环](https://github.com/Nephthelana)，[隨風飄逸](https://github.com/chris81605)，[鲤鱼旗](https://github.com/koooooiCarp) 在模组开发群内的答疑和讨论。

- 感谢[Lyoko-Jeremie](https://github.com/Lyoko-Jeremie)大神开发了Modloader以及所有预置模组、[Number_Sir](https://github.com/NumberSir)大佬开发了模组编写助手，以及两位魔法师在模组开发群里提供的教程和指导。

- 感谢[Number_Sir](https://github.com/NumberSir)，[闰人](https://github.com/omvjro)，[丧心病](https://github.com/MissedHeart) 翻译了dol代码编写通用注意事项。

- 感谢原游戏作者，贡献者，汉化组全体成员以及所有为游戏社区做过贡献的玩家们。（ps: 感觉开始从盘古开天辟地感谢起了...）


## 未实现的功能构想
（纯粹是在画饼）
### 荒原观星

1. 与罗宾一起观星两次后，第三次开始触发对话"因城市光污染严重，想要去荒原观星"，罗宾自信大于91，且已经是沼泽小队的成员的情况下才会答应，否则每次约会时保留选项。
2. 荒原观星路线为森林湖——瀑布——小溪——沼泽——荒原，到达荒原即可触发观星剧情和成就（无需探索荒原）
3. 成就暂定为银成就，名为"counting stars"

### 其他补充事件

1. 在码头救援替换罗宾后，新增各种重逢场景（这是作者自己的心愿）
2. 野餐时判断罗宾是否处于哺乳期（随便加个规则），如果是的话就可以喝奶
3. 获取特质「被罗宾守护」后，每天早上可以被罗宾叫醒（daily.daddyWake)
4. 去咖啡馆买酒后晚上回家可以和罗宾一起喝酒，罗宾醉酒后可以「顺从」，「反压」或者「哄睡」
5. 罗宾与pc一起直播（内容待构想）
6. 有神圣转化时pc可带罗宾从天台等处滑翔（ps: 其实用罗宾专属知更鸟转化可能更合适，这个之后再说）
7. 获取特质「贝利的反抗者后」，罗宾可以和pc一起帮助其他孤儿找工作（如管理柠檬水店），从而达到兼济天下（？）的效果
8.  柠檬水摊/柠檬水店正式化，点击购买有正式的商店界面，购买商品后会有手持效果，并添加日志中的对应物品。
（待补充）