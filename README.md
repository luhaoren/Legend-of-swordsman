#  剑侠传奇
##  关于游戏

剑侠传奇是一款使用c++开发的文字冒险类游戏，可用于windows系统。

##  游戏制作

|| |
|--|--|
|策划 | @lhrfc |
|剧本 | @lhrfc |
|代码 | @lhrfc |
|赞助 | 无 |
|宣传 | @lhrfc |

##  游戏内容
玩家作为一名普通的老百姓，无意中卷入一场江湖之争，在修行和战斗中逐渐崛起，最终成为一代剑侠。

##  游戏设定
###  地图
一级地图：远峰茶馆，灵源当铺

二级地图：灵隐峰，邪剑派，剑客擂台

三级地图：武林大会，剑仙宫

### 等级
|级别| 称号 |
|--|--|
| 一级 |剑士  | 
|二级| 剑客|
|三级|剑侠|
|神级|剑仙|

###  故事情节
玩家来到远峰茶馆，听到武林盟主已经濒临死亡的消息，被抓住想要灭口，玩家逃出并被老道士所救，老道士发现玩家是练武的奇才，这时一个邪剑派的剑客也发现了，玩家可以选择去灵隐峰或是邪剑派。

在修行期间，玩家可以选择在剑客擂台与人战斗或是在当铺等地活动，也可以接受宗门的任务获取资源。

修行到剑侠级别后，玩家可以到武林大会与人战斗，如果打遍天下无敌手就能成为武林盟主。

成为武林盟主后，玩家被带到剑仙宫。
如果玩家善恶值大于等于零，就会接受上一任武林盟主的传功，并与邪恶的血剑王战斗。
否则，玩家会被上一任武林盟主和血剑王围攻。
如果玩家最终获胜，会被宣布通关游戏。

###  属性
剑气：剑客的根本，剑气增长能使剑客强大
若剑气小于等于100则为剑士，若剑气大于100且小于等于500则为剑客，若剑气大于500则为剑侠，若玩家通过游戏，则成为剑仙，剑气增加至10000

血量：若血量小于等于0，则判定死亡

血量上限：$剑气^2$

血量恢复速度：$\sqrt{血量上限\times武学资质}$

精力：使用技能需要精力，若精力小于等于0，则判断无法继续战斗，每次战斗前精力恢复至精力上限（$剑气\times级别$）

武学资质：初始值为7-15之间，随着剑气的增长而逐渐增加，武学资质决定修炼速度。武学资质上限为100

修炼速度：$(\sqrt{武学资质\times3} \times0.8)\space剑气/分钟$

善恶值：做善事会增加善恶值，否则会减少。

普攻：$\ln血量上限$


###  人物
###  物品
###  任务



