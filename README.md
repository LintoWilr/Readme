# ABCDEFG

**P5指路js使用教程**
 
1. 将你** JS 文件** 放入本地的 `user\raidboss` 文件夹中
    - 咖啡 ACT：`ACT\Plugins\cactbot-offline\user\raidboss\`
    - 呆萌、原生 ACT：`ACT.呆萌整合\Plugins\ACT.OverlayPlugin\cactbot\user\raidboss\`

2. 刷新 _Cactbot Raidboss_ 悬浮窗 以加载文件。

**Act问题集锦**

1. 初始化问题：
    - `请勿修改**小队列表队友位置**否则会出现标错，不标的情况`
    - `请勿开启**ID缩写**（国际服）`
    - `聊天框里**勾选默语频道显示**`
    - `队友名字请勿和区服名字一样，例如：紫水栈桥@紫水栈桥`
    - `职能问题请修改角色设置中的**职能内排序设置**`

2. 标记问题：
    - `检查鲶鱼精邮差版本是否为**3.2.1.5**`
    - `出现顶标时请检查队友是否开启标记功能`
    - `本地标点模式为本地场地标点，例如P5三运安全区（不推荐开启）`

3. 男女安全区报错：  
    - `Cactbotself请使用国服版本，确保显示有Opcode的日志`
    - `掉线重连后请手动执行团灭初始化触发器或者跳电网`

4. **加载顺序**：请保证你的加载顺序为以下顺序：
    - `解析插件 `
    - `Triggernometry`
    - `Cactbotself（Morelogline）`
    - `鲶鱼精邮差`
    - `抹茶插件（或者删除抹茶插件）`

5.Triggernometry报错问题
    - `检查加载顺序 `
    - `删除原来的Trn`
    - `重启ACT `
    - `安装MlmTrn `
    - `重启ACT `



