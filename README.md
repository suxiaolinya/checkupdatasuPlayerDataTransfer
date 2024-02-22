# suPlayerDataTransfer 玩家数据转移
## 功能
* 转移某个玩家的数据到另一个玩家上
* 可用于玩家换号数据迁移
### 已经实现：
* 1.迁移背包物品
* 2.迁移末影箱物品
* 3.迁移等级
* 4.迁移进度
## 指令+权限
#### 玩家：
* /pdt setpassword [密码]--suPlayerDataTransfer.pdt--用于设置迁移时的密码
* /pdt transfer [旧玩家名] [旧玩家密码] [新玩家]--suPlayerDataTransfer.pdt--迁移
#### 管理：
* /adminpdt setpassword [玩家名] [密码]--suPlayerDataTransfer.pdt--设置某个玩家迁移时的密码
* /adminpdt transfer [旧玩家名] [新玩家]--suPlayerDataTransfer.pdt--迁移玩家数据
## 配置文件
* 只有一个检查更新选型
* 其他配置文件别动

## 注意：需要两个玩家同时在线


![统计信息](https://bstats.org/signatures/bukkit/suPlayerDataTransfer.svg)
