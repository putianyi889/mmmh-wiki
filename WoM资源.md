# 经验(Experience)
经验有三种获取途径：扫雷过程中每完成1个bv获得1点经验，受到装备“经验”加成；竞技场奖励经验，受到装备“竞技场奖励”加成；任务奖励经验，受到装备“任务奖励”加成。目前经验有两个作用：每获得1000经验可以获得1功勋点；达到一定经验值可以获得奖杯。会员每获得10000经验还可以额外获得一次免费提示。

功勋点用于强化装备。

# 金币(Coin)
金币有五种获取途径：
- 扫雷每开一局可以获得和难度相当的金币，受到装备“金币”加成。按照难度的机制，无论扫什么样的图，通过这种途径获取金币的速度大致是一样的。
- 竞技场奖励金币，受到装备“竞技场奖励”加成。
- 任务奖励金币，受到装备“任务奖励”加成。
- 活动结束后未消费的点数会以每点35金币的价值回收。
- 市场上卖出其他资源获得金币。

# 宝石(Gem)
宝石的获取途径较丰富。
- 从市场购买。
- 从活动商店，按照每宝石10活动积分的价格购买。
- 竞技场奖励宝石，受到装备“竞技场奖励”加成。
- 会员每天获得1个钻石。
- 赛季奖励包含钻石。
- 不同宝石的独有获取途径。红宝石、蓝宝石、黄玉、紫水晶要求经典模式且难度低于1000。缟玛瑙要求经典模式且难度不低于1000。除碧玉、石榴石、祖母绿、钻石以外，其他宝石受到装备“宝石”加成。
  - FL每开一局可以获得红宝石，NF每开一局可以获得蓝宝石。红宝石/蓝宝石数量和难度*bvs成正比：每1难度，1bvs获得0.001红宝石/蓝宝石。bvs超过3以3计算。
  - 连胜时可以获得紫水晶。紫水晶数量和难度成正比。尚不清楚其与连胜数、胜率之间的关系。无猜连胜不能获得紫水晶。
  - 每开一局可以获得黄玉。黄玉数量和难度成正比，和(IOE+K)的**十次方**成正比。对于初中高级，K分别为-0.05、0.05、0.1。对于自定义，K在-0.05和0.05之间但是不清楚具体值。当IOE+K=1时，每难度可以获得0.001黄玉。
  - 每开一局难度达到1000的图可以获得缟玛瑙。每1000难度获得3个缟玛瑙。
  - 每开一局无猜可以获得海蓝宝石。每1难度获得0.003海蓝宝石。
  - 任务奖励石榴石，受到装备“任务奖励”加成。
  - 每获得一局胜利（难度>=1）可以获得0.003祖母绿。
  

只考虑游戏过程中的奖励，玩高难图时每1000金币相当于1个缟玛瑙。玩无猜时每1000金币相当于2个海蓝宝石（假设有连胜）。玩低难度经典时每1000金币相当于最多3个红宝石/蓝宝石。

宝石的中英文对照：
|贴图|中文|英文|
|:-:|:-:|:-:|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/1.svg" width=20>|黄玉|Topaz|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/2.svg" width=20>|红宝石|Ruby|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/3.svg" width=20>|蓝宝石|Sapphire|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/4.svg" width=20>|紫水晶|Amethyst|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/5.svg" width=20>|缟玛瑙|Onyx|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/6.svg" width=20>|海蓝宝石|Aquamarine|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/7.svg" width=20>|祖母绿|Emerald|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/8.svg" width=20>|石榴石|Garnet|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/9.svg" width=20>|碧玉|Jade|
|<img src="https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/wom/10.svg" width=20>|钻石|Diamond|

# 竞技场门票(Arena ticket)
竞技场门票有三种获取途径：
- 从市场购买。
- 从活动商店购买门票包。
- 游戏时可获得。详情见[帮助-竞技场](https://minesweeper.online/cn/help/arena)

# 装备
装备通过其他资源合成/强化，装备又可以反过来提高其他资源的获取速度。

装备有五种：引擎（Engine）、船体（Hull）、鱼雷（Torpedoes）、雷达（Radar）、声呐（Sonar）。每种装备可能提供五种加成：
|加成名|引擎|船体|鱼雷|雷达|声呐|
|:-:|:-:|:-:|:-:|:-:|:-:|
|经验|✓|✓|✓|✓|✓|
|金币|✓|✓|✓|✓|✓|
|宝石|✓|✓|✓|✓|✓|
|任务奖励|✓|✓||||
|竞技场门票|||✓|✓|✓|
|每日任务|✓|||||
|赛季任务||✓||||
|活动|||✓|✓||
|竞技场奖励|||||✓|

所有装备的前三项加成都是经验、金币、宝石。引擎和船体的第四项是任务奖励，鱼雷、雷达、声呐的第四项是竞技场门票。第五项加成是专属加成，引擎是每日任务，船体是赛季任务，鱼雷和雷达是活动，声呐是竞技场奖励。

每个装备的每项属性最低是0%（不显示），最高是20%（未升级时）。装备的质量是该装备的五项属性之和。经验、金币、宝石、任务奖励、竞技场门票、竞技场奖励是连续属性，可以取到0%到20%的每个值。每日任务和赛季任务是离散属性，只要不为0%则作用都是+1。活动加成和每月的活动有关：轮盘活动和找票活动为连续属性（活动积分+x%），抢任务活动和送任务活动为离散属性（任务+1）。