# CSGO的config文档 
## 文件与功能简介
1. `autoexec.cfg`
**适用于竞技模式**。将一些配置归于默认，用于恢复正常游戏设置。包含一些玩法优化，比如关闭音乐盒。**包含个人惯用配置，比如鼠标灵敏度，切记不要直接使用，修改为适合自己的配置**
2. `practice.cfg`
**练习模式**。自动开启服务器作弊模式，并且开启练习模式，比如无限子弹、金钱、复活等。
3. `myalias.cfg`
**一些alias命令**。*仅供参考，某些比赛禁用一键跳投，可以用双键跳投。*
4. **注意，文档可以用系统自带记事本打开并且修改，文档内附带注释。**
## 使用方法
1. 将.cfg文档放入游戏目录
一般位于`Counter-Strike Global Offensive/csgo/cfg/`
*Counter-Strike Global Offensive是游戏主目录，查找方式是：在Steam客户端右键点击csgo游戏->属性->打开游戏目录*
2. 进入游戏，在游戏设置内勾选“启用开发者控制台”，在控制台输入`exec autoexec`即可执行脚本。*`practice.cfg`则输入`exec practice,`,文件名去掉后缀即可*
3. 使用则在`游戏属性->高级启动项`内输入`+exec autoexec`。*autoexec是在游戏开启时默认执行的，无需输入启动项，其他文件名则需要，比如`+exec zombiecfg`*
