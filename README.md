# 猎人模式 HunterMode
![在这里插入图片描述](./img/H-MOD.jpg)

>&emsp;&emsp;Hunter模式(简称:H-MODE),是一个与感染者Hunter对抗的游戏.人类玩家可通过选择单人或多人模式进行游戏通关.由于Hunter不间断对玩家进行骚扰和攻击,造成游戏的难度大大的提升,游戏的目的也是为了锻炼玩家的反应能力与技术的提升

# 一、模式程序
## Ⅰ、程序开发:紫冰(ZB) & 葵花(HI MA)
- [特别感谢人员名单](#特别感谢)
## Ⅱ、版本更新内容(1.8)
- [最新版本更新内容](#本次更新)(2024-1-8)
<hr>

**<font color=#3399EA>H-mod v1.8(<font color=red>难度与BUG海量修复更新!!!</font>)</font>**  
<font color=red>由于Hunter的AI在不断的优化,已经高度模仿正常玩家的攻击行为,可以给玩家造成很大的困扰,足以拟补以前的缺点.所以在1.8版中,将坦克将不会使用连跳,恢复为正常的坦克,Hunter的骚扰将会提升到一个新的难度.为此本版本的各模式Hunter对玩家攻击的血量大幅度下调.</font>  
<font color=#FF9900>新增功能:</font>  
挂机玩家30秒误操作自动转入空闲  
4人练习模式  
2v2允许单人通关(牺牲3)  
营救动画出现时增加换图提示  
梯子上可以开枪和推特感  
重写官方触发机关引发尸潮,快速冲向终点时,感染者不刷新BUG  
<font color=#FF9900>排行榜更新</font>  
1.增加每个玩家通过每一张地图记录  
2.增加整体流程记录  
3.增加牺牲3通关记录  
<font color=#FF9900>更新功能</font>  
取消坦克连跳设定  
3人练习投票失败修复  
双人排行榜倒地一次黑白画面取消,但保留心跳声音  
取消推Hunter的信息提示  
添加被感染者控制时禁止旁观  
禁止玩家投票修改难度  
坦克出生位置调整  
部分模式下只允许在第一关更换人物  
修复系统日期显示符合国人习惯  
限制WITCH数量仅有1只,每间隔一段时间会自动刷新在前方

<font color=#FF9900>地图BUG修复:</font>
- 车站  
NAV感染者导航路线修复  
地图门取消
- 寂静1  
地图灯光修补  
出生点NAV/路线遮挡物/僵尸分部  
终点安全门前卡坦克问题  
第一个丧尸手里补手枪  
感染者爬墙箭头取消  
坦克出生位置NAV导航  
- 寂静4  
终点安全门前灯光补光
- 丧钟1  
第一关安全室门口坦克卡点  
安全室屋内坦克卡点
- 丧钟2  
终点安全门前卡坦克问题  
机关警报卡特感问题
- 丧钟3  
起点开门开关故障  
新区域拓展NAV及布景制作  
终点卡特感尸潮位置
- 丧钟4  
新区域拓展NAV及布景制作  
坦克复活卡点问题  
安全室新区域导航修复
- 收获1
新增武器位置
- 收获4
终点安全门开启  
NAV终点导航修复
- 收获5
小屋窗户卡坦克  
仓库卡坦克"
- 牺牲1  
牺牲第一关信号弹光感  
- 牺牲3  
拓展新机关区域  
- 医院2	  
最后武器点信号弹  
临近安全室门口2楼BUG卡点  
机枪检查  
终点安全门周边屋子无门视觉问题
- 医院3
救护车卡坦克NAV问题
医院3下水道加灯
减少医院门口坦克可以打的铁"
- 医院4
病床卡坦克问题NAV
- 医院5
电台机关等待时间过长修正
- 坠机1  
人类扮演感染者无法进入复活点
- 坠机2  
捷径警报车BUG

<font color=#FF9900>新增模式:</font>
- 硬核模式(高强度)  
- 枪法练习  
  1. 本模式不能推飞扑的Hunter  
  2. Hunter强度与对抗相同  
  3. 被扑中扣去少量血量  
  4. 如果空爆Hunter,玩家奖励大量血量  
  5. 坦克伤害不高

更多[模式介绍](#modemore)

<a id="特别感谢">特别感谢</a>

游戏各模式测试 : **热心网友**

# 二、游戏介绍
## Ⅰ、中文介绍
### 1.地图说明
#### ⑴.地图设定
① 开局提供所有物资,最终营救关卡补给医疗包  
② 无投掷,无大枪,无医疗包,途中只有药丸,药!药!药!  
③ 所有刷枪点刷弹药点开放初级武器  
④ 特感只有Hunter,多Hunter无尽复活  
⑤ 每张地图第一关终点会刷新坦克(部分除外:牺牲1/大坝3)  
⑥ 人类被杀后可以在营救点立刻复活,复活次数根据营救点而定  
⑦ 服务器刷新速率支持 60tick  
⑧ 地图是作者重新设计,限专家模式体验
#### ⑵.地图解锁/重制
  - 解锁
    1. 人类可以打破原先只有特感才能打破的墙壁  
    2. 开启隐藏区域  
    3. 解锁人类扮演的感染者无法进入DLC人类复活点.

- **重制**
1. 所有机关开启时间调整为秒开.

##### a.毫不留情
- 第四关:
  1. 开放电梯隐藏区域
  2. 电梯抵达后会释放坦克
- 第五关:
  1. 修复BUG卡点

##### b.坠机险途
- 第一关:解锁终点隐藏区域
##### c.死亡丧钟
- 第三关:解锁终点安全屋内隐藏区域(安全门可开启)
- 第四关:解锁终点安全屋内隐藏区域(安全门可开启)
##### d.寂静时分
- 第一关:
   1. 重制死亡丧钟与寂静时分衔接剧情地图
- 第三关:部分BUG点修复.
##### e.大坝(非官方自带地图,需下载)
 - 第一关:
    1. 结尾引发无限尸潮取消
    2. 果园尸潮数量修复
 - 第二关:
    1. 结尾机关无限尸潮取消
    2. 结尾机关尸潮数量修复
- 第三关:
    1. 开放本关地图所有药丸位置
    2. 取消最终营救前触发的坦克
    3. 触发油桶机关开始引发尸潮直到第二部电梯前结束.
    4. 修改最后机关打完坦克才能自动开启逃生大门

##### f.血型收获
- 第一关:解锁安全室附近的地下区域
##### g.牺牲
- 第二关:修复悬挂上船BUG
- 第三关:修复卡坦克BUG点
##### h.末路车站
- 解锁官方隐藏地图

### 2.地图顺序
官方地图剧情顺序:
毫不留情 > 坠机险途 > 死亡丧钟 > 寂静十分 > 大坝   >血型收获 > 牺牲 > 末路车站  
大坝:(非游戏自带地图,需自行下载)

### 3.游戏指令
**<font color=#3399EA>游戏常用指令(<font color=#FF662A>指令仅叹号+小写字母</font>)</font>**
```sm
申请位置:!sq (!sq+空格+你想说的话,例:!sq 带我玩玩)
加入人类:!jr | !jiaru | !join | !sur		(有空闲活着的电脑人时可以加入)
加入感染:!pb | !gr | !inf		(挑战模式/练习模式才可以加入感染者)
旁观空闲:!pg | !afk | !away
改变外观:!bx | !hr
主动自杀:!zs | !kill
查询排名:!pm | !top		(天梯模式前十名)
查询信息:!xx | !rank		(天梯模式个人统计)
查看总分:!zf | !point 	(天梯模式查看积分总数)
查看积分:!jf | !score 	(天梯模式查看当前关卡自己已获得分数)
更多指令:!ml
模式投票:!tp|!mode
玩法说明:!hmod
游戏简介:!motd
```
### 4.官方BUG修复
修复官方缺陷设定和新增辅助功能  
① 起点安全屋属于保护区域,玩家在该区域不能互相伤害  
② 手持药丸,准心指向队友可以按E键传递药丸(修复右键判断成推,而不是给药的错误)  
③ 禁止卡住攀爬的梯子的感染者  
④ 新增标记点,按键T(喷漆键)  
⑤ 解锁部分官方为开放地图区域(丧钟3/4终点安全门,血型收获)  
⑥ 开放丧钟与寂静时分两张地图的衔接剧情地图(隐藏彩蛋)
<hr>

## Ⅱ、英文介绍(English Explain)
------Map mode setting ------  
① start to provide all the supplies, and finally rescue the level replenishment medical package  
② no throw, no big gun, no medical kit, only pills  
③ brush gun point brush ammunition point open all primary weapons  
④ special feelings Hunter endless resurrection  
⑤ map is the master redesign, limited expert mode experience

-----Single mode-----  
Hunter threw the survivor's blood to automatically die  
① 2 Hunter+5 zombies, the final level has a corpse  
② attacking damage: 25HP, paw injury: 10HP  
③ paws can not cause damage when pushing the Hunter  
④ players have no fall, no blood and die  
⑤ powerful players can apply to increase the number of Hunter

-----Double mode-----  
Hunter needs a teammate to rescue. Team teamwork.  
① 3 Hunter+10 zombies, corpse tide: 10  
② claw damage: 15HP, the number of falls: 1

-----Three-person mode-----  
① 3 Hunter+20 zombies, corpse tide: 20  
② claw damage: 20HP, the number of falls: 2

-----Quad Mode-----  
① 3 Hunter+30 zombies, corpse tide: 30  
② claw damage: 40HP, the number of falls: 2
<hr>

<a id="modemore"></a>
# 三、模式介绍
## Ⅰ、休闲模式
<font color=#00adb5>普通模式游戏设定(<font color=#FF662A>新手</font>)</font>  
<font color=#276694>默认官方游戏设定  
游戏难度:★☆☆☆☆  
适合水平:专家难度游戏时间(50小时)</font>

-----单人模式-----  
<font color=#276694>Hunter扑倒幸存者会自动扣除一定血量</font>  
① 猎人:1,僵尸:5,营救有尸潮  
② 扑人伤害:3HP,爪子伤害:5HP  
③ 推Hunter时,爪子无伤害力  
④ 坦克生命:3000HP  
⑤ 坦克伤害:10HP  
⑥ 玩家无倒地,无血即死 

-----双人模式-----  
<font color=276694>被扑需队友营救.团队配合,倒地一次黑白</font>  
① 猎人:2,僵尸:10,尸潮:10  
② 爪伤:5HP,倒地:1  
③ 坦克生命:4000HP  
④ 坦克伤害:10HP  
⑤ 扶起队友速度加快

-----三人模式-----  
① 猎人:2,僵尸:15,尸潮:20  
② 爪伤:5HP,倒地:2  
③ 坦克生命:6000HP  
④ 坦克伤害:10HP

-----四人模式-----  
① 猎人:3,僵尸:20,尸潮:30  
② 爪伤:5HP,倒地:2  
③ 坦克生命:8000HP  
④ 坦克伤害:10HP

## Ⅱ、进阶模式
<font color=#00adb5>进阶模式游戏设定(<font color=#FF662A>专家</font>)</font>  
<font color=#276694>Hunter智商提高/坦克智商提高,击倒玩家不打死,  
游戏难度:★★★☆☆  
适合水平:专家难度两个月游戏时间(1500小时)</font>

-----单人模式-----  
<font color=#276694>Hunter扑倒幸存者会自动扣除一定血量</font>  
① 猎人:2,僵尸:3,营救有尸潮  
② 扑人伤害:10HP,爪子伤害:10HP  
③ 推Hunter时,爪子无伤害力  
④ 坦克生命:3000HP  
⑤ 坦克出现时,有Hunter干扰  
⑥ 玩家无倒地,无血即死

-----双人模式-----  
<font color=276694>被扑需队友营救.团队配合,倒地一次黑白</font>  
① 猎人:2,僵尸:10,尸潮:10  
② 爪伤:10HP,倒地:1  
③ 坦克生命:4000HP  
④ 扶起队友速度加快

-----三人模式-----  
① 猎人:2,僵尸:15,尸潮:20  
② 爪伤:10HP,倒地:2  
③ 坦克生命:6000HP

-----四人模式-----  
① 猎人:3,僵尸:20,尸潮:30  
② 爪伤:10HP,倒地:2  
③ 坦克生命:8000HP

## Ⅲ、硬核模式
<font color=#00adb5>硬核模式游戏设定(<font color=#FF662A>练枪</font>)</font>  
<font color=#276694>特感与坦克智商进阶难度基础上再次提升  
玩家水平:★★★★☆  
玩家水平:专家难度(视个人能力)</font>  
-----单人模式-----  
1.本模式不能推飞扑的Hunter  
2.Hunter飞扑血量与对抗相同  
3.被扑中扣去少量血量  
4.如果空爆Hunter,玩家奖励大量血量  
5.坦克伤害不高  
① 猎人:2,僵尸:3,尸潮:5  
② 扑人伤害:3HP,爪伤:10HP  
③ 坦克生命:8000HP  
④ 坦克出现时,有Hunter干扰  
⑤ 玩家无倒地,无血即死

## Ⅳ、怀旧模式
<font color=#00adb5>经典版本:猎人模式1.5(<font color=#FF662A>旧版特感强化</font>)</font>  
-----单人模式-----  
<font color=#276694>Hunter扑倒幸存者会自动扣除一定血量</font>  
① 猎人:2,僵尸:无,营救有尸潮  
② 扑人伤害:25HP,爪子伤害:10HP  
③ 推Hunter时,爪子无伤害力  
④ 坦克生命:3000HP  
⑤ 玩家无倒地,无血即死

-----双人模式-----  
<font color=276694>被扑需队友营救.团队配合,倒地一次黑白</font>  
① 猎人:3,僵尸:10,尸潮:10  
② 爪伤:10HP,倒地:1  
③ 坦克生命:4000HP

-----三人模式-----  
① 猎人:3,僵尸:15,尸潮:20  
② 爪子:10HP,倒地:2  
③ 坦克生命:6000HP

-----四人模式-----  
① 猎人:3,僵尸:20,尸潮:30  
② 爪伤:10HP,倒地:2  
③ 坦克生命:8000HP

## Ⅴ、天梯模式
<font color=#00adb5>排行设置(<font color=#FF662A>积分获得方法 / 玩家数据统计说明</font>)</font><br>
1.积分只有成功通过当前光卡的玩家才被系统记录保存.  
2.获得积分:空爆Hunter,空爆石头,击杀坦克,秒杀Witch,完整地图  
3.玩家数据:击杀总数,击杀Hunter,空爆Hunter,空爆石头,击杀坦克,秒杀Witch  
4.多人模式:当前关卡死亡玩家,队友如果过关,死亡玩家无积分.  
5.多人模式:当前关卡死亡玩家,当前关卡已获得积分清零.  
6.多人模式:当前关卡死亡玩家,中途被队友营救.当前关卡积分将重新统计.  
7.中途加入游戏(非第一关)的玩家,通过最终营救,将无法获得完整地图的高额奖励.  
8.中途更换模式(非第一关)的所有玩家,通过最终营救,将无法获得完整地图的高额奖励.  
9.队伍灭团(游戏重开)将被扣除积分.积分为0时,将不会再扣除玩家积分.  
<font color=red>注意:<br>&emsp;&emsp;本系统只是为了帮助玩家提升水平,并根据玩家水平给出一个综合的评定.如发现有玩家利用游戏漏洞或不正当手段获取积分,一经发现该玩家将直接积分归为负数,负数积分的玩家,将不会出现天梯模式的排行中.如情节恶劣者,直接封号.</font>  
<font color=skyblue>&emsp;&emsp;如果有玩家发现BUG或作弊进行及时反馈与举报,将按照情节严重程度,给予反馈玩家一定奖励.</font>
### 月赛/季赛/半年度/全年度

## Ⅵ、练习模式
- 玩家可以扮演猎人(Hunter)和坦克(Tank),提升玩家对抗水平
## Ⅶ、其他模式
### 1.附加类
<font color=#276694>附加模式:(<font color=#FF662A>可以在任何模式中,通过投票附加此模式功能</font>)</font>

#### ⑴.写实模式
<font color=#276694>仿真视觉游戏环境(<font color=#FF662A>附加</font>)</font>
#### ⑵.吸血鬼模式
<font color=#276694>全程无医疗品物资补给(<font color=#FF662A>附加</font>)</font>  
空爆特感增加血量:3HP  
杀死特感增加血量:1HP  
空爆石头增加血量:5HP  
杀死坦克满血奖励(未完成)  
杀死女巫满血+药丸奖励(未完成)
### 2.娱乐类
#### ⑴.手雷大战
- 开局玩家获得手雷和小药,通过互投手雷击杀对方,最后幸存者获得胜利.  
  1. 开局30秒,分配手雷及药丸  
  2. 每人只有一颗药丸  
  3. 手雷分:土质与火瓶可按键切换
#### ⑵.坦克追杀令(制作中)
- 开局只有坦克出现,会在地图各处围追堵截玩家  
  1. 地图物资默认官方设定  
  2. 玩家每局满血  
  3. 玩家每局提供药丸补给  
  4. 玩家子弹无限  
  5. 坦克每拳伤害为30HP-90HP(待测试后设定玩家存活几率次数)
#### ⑶.大逃杀(待开发)
- 灵感源于电影<BR大逃杀>剧情,后有绝地求生游戏类似.  
  1. 玩家随机分散出生在地图的各处  
  2. 武器随机分配  
  3. 玩家可携带2把主武器,2颗雷,1个医疗包,5个小药(吃药虚血慢增长再衰减)  
  4. 地区资源默认官方设定2-3倍  
  5. 最后玩家胜利,可选择投票换图或继续游戏  
  6. 可以设置团队模式.(按角色分配队伍(按人数配置团队))
#### ⑷.捉迷藏又名躲猫猫(待开发)
- 玩家在固定区域变成物品模型,在一定时间内进行躲藏,如果被玩家找到失败.如果躲藏渡过指定时间,则玩家胜利.  
根据玩家人数,设定下列不通条件,如5人(1鬼找4藏)  
  1. 寻找者武器有10发子弹  
  2. 游戏时间5-10分钟  
  3. 被找到的玩家将进入下一轮被排进随机当鬼  
  4. 未被找到的玩家将继续进行躲藏,直到所有人当过一轮鬼
#### ⑸.黑暗森林模式(待开发)
- 灵感源于小说<三体>,玩家在写实状态下都会隐身,只有开枪或攻击时会显现真身.游戏采用淘汰大逃杀方式.
#### ⑹.猎人派对(制作中)
- 事实证明Hunter病毒才是传播性感染性最强大的.所有的感染者人类都疯狂了,他们都会模仿Hunter去袭击你,他们没有任何理智.而你作为真正的Hunter进化者,一位强大的狩猎者,你才是最理智最清醒的,现在正是你进化过程中的衰弱期,人类的武器暂时还有用,拿起它,追寻军队的脚步,找到继续进化的办法.

# 四、版本介绍
## - 版本更新
<a id="本次更新">本次更新</a>  
2024-1-8  
1. 调整硬核模式部分参数
2. 新增投票 - 附加功能 - 硬核功能
3. 更新排行榜旁观者可实时查看当前玩家数面板



## Ⅰ、历史版本
    1.7g - 2022-04-1
      -----天梯模式
      1.完整地图通关,地图基础奖励积分提升2倍
      2.新增天梯双人模式
      -----练习模式
      1.新增三人模式
      2.修正机枪拉坦克BUG,机枪改2代机枪
      -----其他
      1.调整营救关卡机枪位置
      2.调整天梯模式游戏难度
      3.修复过关安全门不出坦克的BUG
      -----地图
      1.修复大坝第1关,果园处尸潮数量问题
      2.修复大坝第2关,终点机关尸潮数量问题
      3.调整大坝第3关游戏机制(油桶引发尸潮一直持续到第2电梯处结束)
    1.7f - 2022-3-15
      -----增加练习模式(人vs人)
      单人模式将调整玩家被扑后可以立即起身
      双人时保持正常,被被扑后人物身体会显示半透明状态的无敌时间.
    1.7c - 2022-2-13
      1.排行榜分数调整
      完整通关积分算法:
      (关卡数量*(每关基础分数*关卡数量)) + 存活奖励
      如:基础分数为2,存活奖励:5
      毫不留情完整通关将获得额外55分奖励
      坠机险途完整通关将获得额外13分奖励
      牺牲战役完整通关将获得额外23分奖励
      分数根据关卡数量难易度提升额外奖励
      2.击杀女巫不在受限每关分数上限.
      如:每关分数上限23分+击杀女巫数量*5分=你当前过关分数
      3.新增1v2与2v2 人人对战模式
    1.7a 2022年
      2022年猎人模式重制版
      重写制作模式及编写代码及游戏逻辑
      更新感染者的智商判断,更加聪明与各种技术对抗
      新增更多模式与玩法.
      系统部分:
      1.游戏系统全部重写(运行稳定流畅)
      2.Hunter模式,猎人智商提高(会埋伏人类)
      3.允许玩家加入感染者队伍,指令!pb(仅限练习模式)
      4.新增玩家打爆坦克石头,会发出特殊语音
      5.新增空爆Hunter时,有提示音
      地图部分:
      1.解锁官方隐藏区域
      2.新增死亡丧钟与寂静十分之间未开放的衔接地图
      3.调整部分地图视觉问题
      4.人类可以打破感染者才可以破坏的墙壁(捷径路线)
      5.修复旁观者在最终关卡屏幕视角被卡住问题.
      修复历史BUG:
      6.修复1.6
      5.吸血鬼模式,全程无补给品,打特感奖励血量
      6.新增游戏玩法说明菜单,指令!motd
      其他模式:
      1.默认模式(官方默认)
      2.猎人模式(Huntre模式)
      3.练习模式(人类可以扮演感染者,阻挠合作玩家)
      4.吸血模式(无补给,打感染者给生命奖励)
      5.手雷模式(娱乐模式:手雷互炸)
      6.坦克模式(娱乐模式:不停出坦克,玩家速跑通关,锻炼身法)
    ​v1.6
      1.安全门恢复正常开关速度
      2.新增系统提示:打爆坦克投掷物提示玩家名称
      3.修复双人模式,倒地进入一次黑白状态
      4.坦克出现安全门自动锁定,坦克死亡安全门解锁
      5.吸血鬼模式,全程无补给品,打特感奖励血量
      6.新增游戏玩法说明菜单,指令!hmod
    v1.5
      1.多人游戏,Hunter扑倒玩家时,其他玩家如果离的太近会被震退,请保持2人间距
      2.进阶模式启用2代坦克设定,打倒玩家后去追寻其他幸存者.
      3.挑战模式,限制右键连续使用次数.连续使用会卸力,玩家需要短暂时间恢复右键力量
      4.修复1.4版本玩家死亡后,游戏不能重新开始的问题.
      5.调整地图和一些其他的BUG
      6.服务器支持60tick刷新率,提升流畅度
    v1.4
      1.调整安全门,禁止玩家跑图
      2.修复人类卡住特感攀爬或楼梯BUG
      3.修复人类跳楼捷径BUG
      4.新增模式投票,输入!tp选择玩法
    v1.3
      1.新增进阶模式
      2.加强Hunter智商,仿人类玩家
      3.增加空爆Hunter,玩家名称提示
      4.加强TANK智商,会连跳加速
      5.增加玩家杀坦克攻击输出统计
      6.新增牺牲地图单人模式通关
    v1.2
      1. 修复单人模式Hunter扑人不扣血
      2. 调整Hunter复活时间
      3. 调整僵尸刷新速度
      4. 新增Hunter多人合作模式
      5. 替换所有二级武器
      6. 禁止地图补给及投掷物
    v1.1
      7. 增加单人模式  
      8. 调整单人模式坦克血量  
      9. 调整单人模式僵尸数量  
    v1.0
      1.2018年10月20 系统化建立Hunter模式游戏规则,简称H-MODE  
      10. 2017年 尝试创建只有Hunter的过关方式  
      11. 2016年 药抗模式启发,想单机练习打Hunter  
      12. 2014年 尝试制作单通模式游戏规则  
      13. 2012年 追求挑战,单人无电脑辅助,单通专家所有地图

  **下载链接:[H-MOD v1.1](https://pan.baidu.com/s/13yZAge3I459BJJBUqbDRzw)(提取码:jipx)**  
  **CSDN下载:[H-MOD v1.1](https://download.csdn.net/download/ZBzibing/16672123)**