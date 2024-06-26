# CS2 的 config 文档 
## 文件与功能简介
1. `autoexec.cfg`
**适用于竞技模式**。 将大部分配置恢复到默认状态。包含一些玩法优化，比如关闭音乐盒。
2. `practice.cfg`
**练习模式**。自动开启服务器作弊模式，并且开启练习模式，比如无限子弹、金钱、复活等。
3. `myalias.cfg`
**一些 alias 命令**。*仅供参考，某些比赛禁用一键跳投，可以用双键跳投。*
4.  `grenade_practice` **投掷物练习合集。**
5. **注意，文档可以用系统自带记事本(推荐 Notepad 3)打开并且修改，文档内附带注释。**
## 注意
1. **这些文件包含个人惯用配置，比如惯用手等，不推荐直接使用，建议查看注释后修改为适合自己的配置。**
2. **现在 CS2 没有原始输入(raw input)相关的设定项和指令，如果想在游戏内启用原始输入可能需要进入系统设置关闭鼠标加速。（也可能 CS2 默认启用原始输入）**
## 使用方法
1. 将.cfg文档放入游戏目录
一般位于`Counter-Strike Global Offensive\game\csgo\cfg`
*Counter-Strike Global Offensive 是游戏主目录，查找方式是：在 Steam 客户端右键点击 Counter-Strike 2 游戏->属性->打开游戏目录*
2. 进入游戏，在游戏设置内勾选“启用开发者控制台”，在控制台输入 `exec autoexec` 即可执行脚本。*`practice.cfg` 则输入 `exec practice`,文件名去掉后缀即可。*
3. 使用则在 `游戏属性->高级启动项` 内输入 `+exec autoexec`。*autoexec是在游戏开启时默认执行的，无需输入启动项，其他文件名则需要，比如`+exec practice`*
