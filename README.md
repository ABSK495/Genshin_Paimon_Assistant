# 原神派懵 Genshin_Paimon_Assistant
这是一个正在开发的原神自动化项目，原神派懵致力于简化和提升原神PC端的游玩体验。

目前已适配1080p和2k分辨率，打开派懵会自动识别对应分辨率并调整。目前暂时不支持其他分辨率，不支持窗口化，不支持云原神，不支持16:10显示器，不支持21:9显示器，不支持手柄。

高分辨率例如原生4K显示器也可以使用2K版本，派懵会自动调整桌面分辨率至2K，再在游戏中切换2K分辨率窗口模式，并且按下alt+enter切换全屏即可使用。

派懵在每个月月初会发布最新版本，在github仓库、蓝奏云以及QQ群均会同步更新，欢迎提交建议和bug。使用前记得阅读压缩包内的注意事项，并且使用管理员身份运行（重要）。

目前已经更新到0.1.7版本，更新内容可查看压缩包内的更新日志。派懵可以直接在github仓库、蓝奏云以及QQ群进行下载，有问题随时联系作者。蓝奏云下载地址：https://wwsn.lanzoue.com/b03x0kjij 密码:shfy

如何使用？解压缩后，使用管理员身份运行压缩包中的派懵.exe，勾选需要执行的功能，直接全屏进入游戏即可。默认勾选了所有实时功能，可以仅勾选自己需要的功能，提高运行速度。

QQ1群：210389345 

QQ2群：827797041

QQ3群：868782270

## 一、派懵目前有哪些功能
### 派懵全流程功能演示
演示地址：https://www.bilibili.com/video/BV1n94y1H7Fp/

### 1. 自动完成探索派遣、每日委托奖励的领取
演示地址：https://www.bilibili.com/video/BV1VN411b7iK/

当你通过完成4次每日委托或者获取到足够的历练点数之后，返回凯瑟琳处按下F开启对话，就能够完成领取奖励和探索派遣，这个操作由派懵自动完成。需要勾选通用功能中的「跳过剧情」和「选择对话」。

### 2. 自动完成纪行奖励的领取
当你完成纪行的每日任务、每周任务以及本期任务时，派懵会自动为你领取奖励，不用进行繁琐的点击。需要勾选通用功能中的「领取纪行」。

但是需要注意玩家当前操作可能会打断纪行的领取，导致派懵乱点的情况出现，常出现于完成委托后进行传送，传送落地后打开纪行界面失败，从而乱点。

如果你的纪行已经达到50级，可以取消勾选该选项节约性能，使得通用功能中的其他功能运行速度更快。

### 3. 自动跳过剧情、活动等对话
当你在进行剧情任务或者一些需要跳过对话的场景时，派懵会自动持续帮你跳过对话，并且选择第1个选项为你推进剧情。如果对话中存在黄色感叹号则会优先选取。需要勾选通用功能中的「跳过剧情」和「选择对话」。

和铁匠进行对话时会默认选择锻造选项，但要注意带有特殊图标的对话，例如限时活动对话是无法被识别到的，仍然会选择第1个带有气泡的选项。

在做任务时出现的黑屏念白、活动以及探索的提示、角色初次见面的角色介绍，打开的信件或者物品，勾选「跳过剧情」后均会全部自动跳过或者关闭。

### 4. 隐藏功能
当你在进行城市声望对话时，派懵会自动选择100点数的讨伐任务接取。当你完成3次讨伐后，派懵会自动领取奖励。

当你完成3次讨伐并领取奖励后再次进行声望对话，派懵会自动接取3次居民请求。需要勾选通用功能中的「选择对话」。

当你被冻住后，派蒙会狂按空格帮你解冻。

派懵会自动接受联机的副本挑战邀请，自动点掉副本内的地脉提示。需要勾选通用功能中的「跳过剧情」。

### 5. 半自动钓鱼
演示地址：https://www.bilibili.com/video/BV1Rw411c7fW/

开启自动钓鱼功能后，只需要手动抛竿，派懵会自动完成拉条和收杆的操作，适用于游戏内所有种类的鱼。

目前自动钓鱼的代码存在问题，精度低并且会出现无法使用的情况，暂时不推荐使用。

### 6. 自动拾取物品
演示地址：https://www.bilibili.com/video/BV1Qu4y1A7Ne/

派懵能够帮助你自动拾取大世界的采集物、怪物掉落物品、蔬菜水果、晶蝶、矿石、调查点、圣遗物、低星武器等一切可拾取物品，目前提供3种拾取模式，根据使用情形自主选择。

快速拾取模式：只要检测到对话框出现就会按下F，拾取速度最快，必定误触，推荐野外打怪时选择该模式。

中间拾取模式：能够排除一些特殊情况，例如对话气泡框，烹饪图标，齿轮图标等，拾取速度适中，但也存在误触情况，推荐一般情况下选择该模式。

稳定拾取模式：拾取速度最慢，但是几乎不会误触对话选项，不推荐选择该模式。

### 7. 锚点传送辅助
演示地址：https://www.bilibili.com/video/BV1ew411W7tz/

派懵能够辅助你进行所有情况下的传送，包括普通锚点，秘境，七天神像，尘歌壶，声望，活动传送点等。只需要使用鼠标点击一次目标点，便能够迅速完成传送过程。但要注意如果误操作将无法撤回。

当一个锚点和另外一个锚点或者秘境太过于靠近时，需要保证鼠标点击的位置离你想要传送的锚点最近，这样才能传送到想要的锚点。为了保证传送的准确性，可以滑动滚轮将地图稍微放大。

可以点击锚点附近的世界boss图标，或者每日委托，地脉花等选项，同样可以完成传送过程。尘歌壶的房子传送可能会出现按得太快传送失败的情况，多点几次即可。后续可以考虑让用户根据机器性能自定义延时时间。

### 8. 辅助强化圣遗物
演示地址：https://www.bilibili.com/video/BV1yu4y1n7Ee/

派懵能够辅助你迅速完成圣遗物的强化，不用等待显示动画，节省你的大量时间。切换到强化圣遗物功能后，在游戏内按下V键即可开始强化。

强化次数可自定义，默认为按下一次V键强化5次。

### 9. 那维莱特一键重击
演示地址：https://www.bilibili.com/video/BV1494y1t72a/

派懵能够帮助你的那维莱特实现秒喷和自动转圈。按下0.5秒V键开始吸取水滴转圈。支持自定义转圈速度，方向，时间。

转圈速度默认为1倍屏幕宽度大的像素，1K屏幕为1920，2K屏幕为2560。可以根据这个数值适当调整。例如1K屏幕修改转圈速度为2880，那么速度会变成默认的1.5倍。

转圈时间默认为3.0秒，可以精确到小数点后1位。那维莱特0命重击持续时间为3秒，4命或者6命转圈时间可能会有所不同，计算后进行修改即可。例如满命那维莱特可以尝试设置为12.0秒。

转圈速度为正，顺时针旋转。转圈速度为负，逆时针旋转。

### 10. 自动跑路
按下0.5秒CapsLock键开始自动跑图，派懵会持续按住W键，再次按下CapsLock键取消，停止会存在一定延迟。需要在通用功能中勾选「自动跑路」。

适用于长距离的移动，不需要一直按下W键了，缓解手部压力，延长键盘寿命。派懵操作使得做任务途中刷手机成为可能。

### 11. 派懵浏览器，攻略查找视频跟跑
在「浏览器」选项卡中点击「打开浏览器」即可启用派懵浏览器。初次启动会打开B站搜索，可以搜索视频点击观看，也可以在派懵界面粘贴需要查看的视频网址，点击加载网址即可跳转。

派懵内置了针对B站视频攻略跟跑的快捷键，其中波浪键~用于暂停和播放，但需要保证当前没有音乐播放器正在播放，或者在播放器设置禁用系统媒体快捷键。

数字键5进度条后退，6进度条前进，7减小不透明度，8增加不透明度，9隐藏恢复窗口，所有功能键均不会打断游戏内的操作。

部分用户打开派懵会出现红屏的情况，此时可以尝试安装微软的webview2库，但有可能安装了还是红屏，属于疑难杂症，需要更多样本。

webview2库下载地址：https://developer.microsoft.com/zh-cn/microsoft-edge/webview2/，通常下载独立安装程序的x64版本。

### 12. 一键购买
一键购买属于单次执行功能，会屏蔽其他实时通用功能，使用完毕后需要取消勾选，并且禁止和其他单次执行功能同时勾选。

勾选一键购买后，在商店界面选中商品按下V键清空商品，可自定义次数。如果次数大于1，派懵会从上到下依次购买指定次数的所有商品。

一键购买常适用于清空杂货店，以及活动商店等。

### 13. 一键烹饪
一键烹饪属于单次执行功能，会屏蔽其他实时通用功能，使用完毕后需要取消勾选，并且禁止和其他单次执行功能同时勾选。

勾选一键烹饪后，在烹饪界面选中菜谱按下V键即可开始烹饪，可自定义次数。

派懵会识别烹饪条进行自动烹饪，通常能够完美判定，但遇到仙跳墙这种完美判断条很短的菜谱，可能会判定失败。属于精度问题，可以后续优化。

一键烹饪常适用于没有熟练度的菜谱自动烹饪的解锁。

### 14. 自动普攻重击
自动普攻属于单次执行功能，会屏蔽其他实时通用功能，使用完毕后需要取消勾选，并且禁止和其他单次执行功能同时勾选。

勾选一键普攻后，按下Caps即可开始自动普攻，中途按下Z键可以切换普攻模式和重击模式，适用于散兵、宵宫等角色。

### 15. 自动砍树
演示地址：https://www.bilibili.com/video/BV1vr421872M/
自动砍树属于单次执行功能，会屏蔽其他实时通用功能，使用完毕后需要取消勾选，并且禁止和其他单次执行功能同时勾选。

勾选自动砍树后，使用芭芭拉装备须弥砍树道具王树瑞佑，输入砍树次数并更新，在游戏内按下V键即可开始循环砍树。

芭芭拉普攻不会改变角色位置，即使程序出现错误也能继续砍伐。根据自身电脑性能，可以适当增加开门延时以及读条延时。

尽量站在单次砍伐数目最多的点位，单日获取每种木材的上限数为2000个，频繁的登录操作可能会引起风险检测，需要根据具体情况调整。

### 16. 账号切换
目前仅支持国服，首先登录账号，开门进入游戏内部后，点击保存账号给账号命名，账号数据会保存在对应的位置。

保存你的所有账号之后，如果需要切换，就在下拉栏点击切换对应的账号，在下方会显示当前的账号名称。之后启动原神账号就会切换到对应账号。

推荐切换对应账号后，按下派懵中的按钮启动原神，非常方便。如果不想要某个账号，切换到对应账号点击删除即可。

### 17. 派懵启动原神
首先选择原神启动目录，可以是原神的YuanShen.exe文件，也可以是第三方的启动exe，例如loader.exe，然后点击原神启动，支持勾选无边框模式。

### 18. 米游社签到
派懵可以实现原神的米游社签到，首先需要保存账号，在派懵文件夹内的config.ini对应账号的 "cookie_xxx = " 处填入账号对应cookie信息，获取方式可以查看我的专栏。

如何获取cookie：https://www.bilibili.com/read/cv30435015/

填入cookie后保存，点击派懵的米游社签到按钮即可完成签到。

但要注意该cookie具有时效性，会在一段时间后失效，需要重新登陆。并且针对多个账号时，可能需要在多个浏览器登录，因为如果从同一个浏览器退出登录，则cookie一定会失效。

### 19. 查看今日天赋武器材料，查看世界Boss周本Boss材料
在今日材料选项卡，点击对应按钮可以查看今日天赋材料、今日武器材料、周本Boss材料对应角色表、世界Boss材料对应角色表。后续会添加更多表格。

### 20. Bug反馈
按下F12，也就是派懵的暂停键，会同时对当前屏幕截图并且保存到派懵文件夹内test目录中，文件名为test.bmp，并且截图会自动涂黑uid，如果遇到需要截图反馈bug的情况可以将这张图片发给我。

派懵的根目录存在一个debug.log文件用于输出所有调试信息，遇见bug也可以将这个文件发给我。

## 二、派懵接下来会加入的功能

### 1. 自动秘境
采用yolov8识别石化古树，已经初步实现功能，等待后续精度优化后上线。

### 2. 加入圣遗物狗粮12小时AB线的自动采集路线设计
使用派懵能够自动规划路线，完成每天圣遗物狗粮的采集。

### 3. 加入所有采集物的采集路线设计
使用派懵能够自动规划路线，完成特定采集物的采集，例如甜甜花，绝云椒椒，鸣草，劫波莲，幽光星星等。

### 4. 加入所有矿物的采集路线设计
使用派懵能够自动规划路线，完成特定矿物的采集，例如铁矿，白铁矿，水晶矿，紫晶矿，石珀等。
