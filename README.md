**基本介绍**

开头预警：此mod是dol游戏的罗宾扩展mod，目前只是一个开头，只有部分功能的雏形，且十分简陋！所以readme也写得很随意...

目前已实现的功能详情可以下载仓库中"现存功能截图说明.docx"（截图说明目前版本有点滞后，等做出能拿"同舟共济"特质的雏形版后会统一更新，见谅），具体的文本和构想请下载"罗宾mod文本和构想整理.txt"（此文档同步更新），现有代码可直接在"game"文件夹下查看，在百度贴吧中也会更新制作过程。（贴吧账号：零环零理想）

本mod基于最新的0.4.7.5版本进行自测，旧版本可能会有不兼容的问题。

安装方式：下载release下test-version中的Degrees-of-Lewdity-RobinMod.zip，用平时玩游戏用的mod管理器加载完汉化mod后，再加载此mod，安装前记得保存自己的存档码，以防止出现bug无法恢复

**请忽略release显示的上传时间，Degrees-of-Lewdity-RobinMod.zip是会随readme同步更新的！**

**不正经的补充**

按理说这种刚开始做的mod不应该公开，但作者比较浮躁，做了一点点功能就急着分享...总之见谅！

作者是新手，代码和文笔都很糟糕的那种，如果各位不嫌弃的话请提供bug测试或者文本/功能上的建议，甚至code review
（完了我感觉我完全是来白嫖的，赶紧划掉这句）

**致谢**

感谢 Robin's GF 对mod的具体设定的构想以及文本创作，目前的构想是我们俩共同讨论出的结果。

感谢 @Nephthelana在最开始提供的代码修改！以及贴吧吧友提供的部分文本。

**目前进度**

（会持续更新，以下功能只做过基本的自测，且文本未经打磨，非最终版本，更详细的介绍请查看"现存功能截图说明.docx"）：

1. 柠檬水摊升级功能雏形，知道罗宾的债务问题后去柠檬水摊开启选项，升级成功后可实现每周存款增加，「买柠檬水」和「提供帮助」时增加防雨功能，且可使用当前拥有的水果尝试榨汁，成功后下周饮料单上会增加新饮料。

2. 热巧克力摊改造/升级功能（升级过柠檬水摊时选项展示为「改造」), 改造/升级成功后可实现每周存款增加，「买热巧克力」和「提供帮助」时增加防雪功能，且保留榨汁机和购买新饮料（热饮）功能。

* 柠檬水摊/热巧克力摊升级后，可以触发下列新增商品：和罗宾触发去电影院买爆米花，可以建议罗宾售卖爆米花；孤儿院阁楼解锁厨房后，可触发高自信罗宾主动售卖小点心。（其他商品待添加）

3. 去柠檬水摊时pc身上如果带有柠檬/血柠/野蜂巢，可以直接送给罗宾带来当周的存款增长，不需要前置条件。
  
4. 为罗宾推荐家教工作雏形，知道罗宾的债务问题后，pc去多瑙河街做家教时开启选项，需要随机到等级A以上的学科才能推荐成功，推荐成功后可以去找罗宾沟通，之后罗宾每天上学日15:06到16:20将位于多瑙河街，想一起放学/触发校门口事件的pc要抓紧时间！
   
5. 修改了罗宾债务的计算逻辑为和pc一样每周递增，一旦罗宾无力支付就会触发惩罚（原游戏逻辑是每周加进度，不是直接计算的金额），新开局无任何额外干预的情况下，原设定的罗宾28天后卖游戏机，35天后被卖码头可以正常触发。

6. 修改了原作「拥抱」后「哭泣」无法触发创伤察觉的bug，为承担债务后「要钱」的文本增加高自信差分
   
**未实现的功能构想**

（作者偷懒直接复制了目前"罗宾mod文本和构想整理.txt"中的未实装功能构想部分，所以内容有点多）

1. 柠檬水摊细节构想：
* 柠檬水摊升级后，榨汁机下需要再增加一段现有商品描述：包括帮pc卖花（帮忙浇花剧情触发），小点心（孤儿院阁楼解锁厨房后触发），
 气球（气球摊摊主出场后触发），爆米花（电影院买爆米花触发）四种商品。

* 根据现有额外商品数量(0到4），增加一条提示描述：
 扩大后的摊位现在有大量的额外空间/许多额外空间/一些额外空间/一点额外空间/摆满了各种各样的商品。

2. 罗宾存款增加细节构想:
* 罗宾每周存款分为固定存款和随机存款，为简化逻辑，只按照固定存款是否大于2000/4000, 来判断罗宾是否有能力承担自己/pc的债务。

* 固定存款增加方式：
  
（1）柠檬水摊基础（300）+ 升级(600)+ 全饮料(300)+ 小点心（300）+ 爆米花（300）+ 气球（有爆米花200，没有150）= 2000

（2) 家教750+摄影基础550=1300

（3）游戏直播（可加入直播时唱歌吸引人气的剧情，合并特长）：按周依次增加[100,300,500,700,1000,1500,2000]，上限2000

* 随机存款增加方式（只要不是100%能拿到的统一被归为随机存款）：
  
（1）给罗宾柠檬/血柠，每周增加pc送的柠檬/血柠的价值*个数*4，然后四舍五入取整

（2）卖花，卖pc日志中的花原价中的一半（另一半要在房间触发对话，每周交给pc)，每种花按自信一周卖50/100/150, 对应自信值40/80

（3）摄影收入，与pc一起拍摄，且pc容貌3以上/或模特名声达标，罗宾与pc一人获得1100，表现为随机收入550（PS：摄影本身有固定收入550，可以理解为pc不在罗宾去拍风景了，哈哈，pc在的话一人550总共1100,或者一人1100总共2200）

（4）直播的随机收入：当周基础*自信（百分比）+ [0，当周基础/2]之间的一个随机数

3. 罗宾工作前置构想：
* 所有工作共同前置：pc知道罗宾的债务问题，目前游戏内只有好感100%半夜受倾诉，或者罗宾被卖一次两个条件

* 柠檬水摊：周末直接去柠檬水摊即可，升级后其他细节见1，升级细节无概率条件

* 巧克力摊：可在柠檬水摊升级的基础上加入改造情节，改造花费300，效果一致，果汁可改为卖热饮（忽略冬季开局的情况）

* 家教：pc在多瑙河街做家教时随机到A以上的学科，可成功推荐罗宾做家教

* 摄影：与pc野餐时概率触发，无设备要求（剧情里可以说明罗宾有相机），概率暂定为20%

* 直播：「看罗宾玩游戏」后概率触发，概率暂定为20%，设备价格2000，可由罗宾自己支付，罗宾存款不够时也可由pc支付

4. 罗宾存款达标后特质构想：

* 罗宾能支付自己的债务后（周固定存款2000)，pc获得「同舟共济」特质：效果为锁罗宾自信50%（高于50%不受影响），pc每日压力-25,创伤-25

* 罗宾能承担pc的债务后（周固定存款4000)，pc同意后获得「被罗宾保护」特质：效果为锁罗宾自信100%，pc每日压力-100,创伤-25

5. 其他（待补充）
   
* 罗宾自信80或者91以后，可以加入反抗贝利的队伍中，不用再乖乖每周付钱了，平时也应该表现得更有反抗性

* 存款达标后应该有额外剧情，如向承担过债务的pc还钱，买回自己的游戏机，为其他孤儿付一周钱等等
