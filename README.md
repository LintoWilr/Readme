# 问题集锦


1. JS使用教程：将**JS 文件** 放入本地的 `user\raidboss` 文件夹中：
    - 咖啡 ACT：`ACT\Plugins\cactbot-offline\user\raidboss\`
    - 呆萌、原生 ACT：`ACT.呆萌整合\Plugins\ACT.OverlayPlugin\cactbot\user\raidboss\`

 刷新 _Cactbot Raidboss_ 悬浮窗 以加载文件。

2. JS相关问题：
    - 怎么没指路啊？：勾选启动SPL API端口`47774`

**Act问题集锦**

1. 初始化问题：
    - 请勿修改`小队列表队友位置`否则会出现标错，不标的情况
    - 请勿开启`ID缩写`（国际服）
    - 聊天框里勾选`默语频道显示`
    - 队友名字请勿和区服名字一样，例如：紫水栈桥@紫水栈桥
    - 职能问题请修改角色设置中的`职能内排序设置`

2. 标记问题：
    - **检查鲶鱼精邮差版本是否为**`1.3.2.5`
    - 出现顶标时请检查队友是否开启标记功能
    - 本地标点模式为本地场地标点，例如P5三运安全区（不推荐开启）

3. 男女安全区报错：  
    - `Cactbotself`请使用**国服版本**，确保显示有Opcode的日志
    - 掉线重连后请手动执行团灭初始化触发器或者跳电网
    - 安全区画错请看Spl问题解答

4. 请保证你的**Act插件加载顺序**为以下顺序：
    - `解析插件 `
    - `Triggernometry`
    - `Cactbotself（Morelogline）`
    - `鲶鱼精邮差`
    - `抹茶插件（或者删除抹茶插件）`

5. Triggernometry报错问题：
    - ①检查加载顺序 
    - ②删除原来的Trn
    - ③重启ACT 
    - ④安装MlmTrn 
    - ⑤重启ACT 

**Spl相关问题集锦**

1. SPL相关问题：
    - 请确保你的Splatoon 为`3.2.1.3`版本（或者使用SplatoonX）
    - Spl有中文，**请调Splatoon language为Chinese**
    - 我的预设颜色太厚了看不见！
**SPL-布局-找到你要改那一条预设-点击线条粗细/覆盖文本里的颜色-修改`A:255`的值**
    - 我想要预设变成那种网格！ SPL-一般设置-勾选使用矩形填充线-将最小间隔改为`0.05~0.15`之间的值 
    - 导入脚本：**`SPL`-`Scripts`-复制要导入的脚本-点击`Install From clipboard`安装（导入网址要开梯子）`**
    - 天箭脚本：共有两个，一个绘制范围，一个绘制安全点，名字不一样，**可以一起导入**，谢谢
    - 删除脚本：**按住`Ctrl` 点击<img src="https://github.com/LintoWilr/ReadMe/blob/main/2.png">**
    - 请使用SplatoonX导入绝欧画图精装版整合，SplX请Github搜索Gamous寻找他的底库
    - SPL画图重复了！挡视线！**删除功能一样的重复预设，或者关闭触发器的功能重复的画图**
    - SplX是这个
    - <img src="https://github.com/LintoWilr/ReadMe/blob/main/1.png">



