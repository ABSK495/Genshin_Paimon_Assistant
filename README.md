# 原神派懵 Genshin_Paimon_Assistant
这是一个正在开发的原神自动化项目。目前已适配1080p和2k分辨率，打开派懵会自动识别对应分辨率并调整。目前暂时不支持其他分辨率，不支持窗口化，不支持云原神，不支持16:10显示器，不支持手柄。

高分辨率例如原生4K显示器也可以使用2K版本，派懵会自动调整桌面分辨率至2K，再在游戏中切换2K分辨率窗口模式，并且按下alt+enter切换全屏即可使用。

派懵以每周为单位正在进行第4次测试，测试时间截止至12月18日，欢迎提交建议和bug。使用前记得阅读压缩包内的注意事项，并且使用管理员身份运行（重要）。

目前测试版已经更新到0.0.4版本，更新内容可查看更新日志。测试版可以直接在仓库或者蓝奏云分流地址以及QQ群进行下载，有问题随时联系作者。

分流地址：https://wwsn.lanzoue.com/b03x0kjij 密码:shfy

QQ1群：210389345（已满）

QQ2群：827797041（已满）

QQ3群：868782270

## 一、派懵目前有哪些功能
### 派蒙全流程功能演示
演示地址：https://www.bilibili.com/video/BV1n94y1H7Fp/

### 1. 自动完成探索派遣、每日委托奖励的领取
演示地址：https://www.bilibili.com/video/BV1VN411b7iK/

当你通过完成4次每日委托或者获取到足够的历练点数之后，返回凯瑟琳处按下F开启对话，就能够完成领取奖励和探索派遣，这个操作由派懵自动完成。需要勾选通用功能中的“选择对话”。

### 2. 自动完成纪行奖励的领取
当你完成纪行的每日任务、每周任务以及本期任务时，派懵会自动为你领取奖励，不用进行繁琐的点击。需要勾选通用功能中的“领取纪行”。

### 3. 自动跳过剧情、活动等对话
当你在进行剧情任务或者一些需要跳过对话的场景时，派懵会自动持续帮你跳过对话，并且选择第1个选项为你推进剧情，整个过程可以让双手完全离开键盘鼠标直至对话结束。需要勾选通用功能中的“跳过剧情”和“选择对话”。

### 4. 自动多情景选择对话选项
当你在进行普通对话时，派懵会默认为你选择最上面的选项。当你在完成一些委托任务时，会为你选择带黄色感叹号的提交选项，并且为你自动提交任务物品。当你在进行城市声望对话时，会为你选择声望任务，并且自动接取讨伐和居民请求等。需要勾选通用功能中的“选择对话”。

### 5. 钓鱼检测，自动完成钓鱼力度条控制以及收杆
演示地址：https://www.bilibili.com/video/BV1Rw411c7fW/

派懵能够帮助你完成游戏内的全部钓鱼任务，包括雷鸣仙、假龙类、炮鲀类、雪中君、渊下宫鳐鱼、枫丹机械鱼以及它们的观赏鱼类型。你可以使用派懵帮助你完成鱼叉、竭泽、灰河渡手等钓鱼武器的获取，或者是用于完成通通400铃的成就等。目前钓鱼精度比较低，需要等待后续优化算法。

### 6. 自动拾取所有物品
演示地址：https://www.bilibili.com/video/BV1Qu4y1A7Ne/

派懵能够帮助你自动拾取大世界的采集物、怪物掉落物品、蔬菜水果、晶蝶、矿石、调查点、圣遗物、低星武器等一切可拾取物品，目前提供3种拾取模式，根据使用情形自主选择。

### 7. 锚点传送辅助
演示地址：https://www.bilibili.com/video/BV1ew411W7tz/

派懵能够辅助你进行所有情况下的传送，包括普通锚点，秘境，七天神像，尘歌壶，声望，活动传送点等。只需要使用鼠标点击一次目标点，便能够迅速完成传送过程。但要注意如果误操作将无法撤回。

### 8. 辅助强化圣遗物
演示地址：https://www.bilibili.com/video/BV1yu4y1n7Ee/

派懵能够辅助你迅速完成圣遗物的强化，自动取消这个过程，不用等待显示动画，节省你的大量时间。按下V键持续强化5次圣遗物。

### 9. 那维莱特一键重击
演示地址：https://www.bilibili.com/video/BV1494y1t72a/

派懵能够帮助你的那维莱特实现秒喷和自动转圈。按下0.5秒V键开始吸取水滴转圈。

### 10. 自动跑路

按下0.5秒CapsLock键开始自动跑图，派懵会持续按住W以及连续冲刺，再次按下CapsLock键取消，停止会存在一定延迟。需要在通用功能中勾选自动跑路。

### 11. 跟跑浏览器

勾选启用浏览器后重启，在派懵界面粘贴需要查看的视频网址，点击加载即可。5后退，6前进，7减小不透明度，8增加不透明度，9隐藏恢复窗口。

## 二、派懵接下来会加入的功能

### 1. 加入圣遗物狗粮12小时AB线的自动采集路线设计
使用派懵能够自动规划路线，完成每天圣遗物狗粮的采集。

### 2. 加入所有采集物的采集路线设计
使用派懵能够自动规划路线，完成特定采集物的采集，例如甜甜花，绝云椒椒，鸣草，劫波莲，幽光星星等。

### 3. 加入所有矿物的采集路线设计
使用派懵能够自动规划路线，完成特定矿物的采集，例如铁矿，白铁矿，水晶矿，紫晶矿，石珀等。

### 4. 加入所有木材的采集路线设计
使用派懵能够自动规划路线，完成特定木材的采集，例如松木，萃华木，御伽木，证悟木，悬铃木等。
