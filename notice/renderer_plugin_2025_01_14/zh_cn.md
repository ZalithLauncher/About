<h2 align="center">Zalith Launcher 渲染器插件功能</h2>

由于 Zalith Launcher 受到来自 PojavLauncher 社区某些极端人员的歧视与威胁，我决定移除 LTW 渲染器，但这并不代表 Zalith Launcher 以后将不能使用 LTW 渲染器，因为我随即为 Zalith Launcher 支持了渲染器插件功能，你可以通过额外安装渲染器插件以加载更多的渲染器！

### 功能：
- 在 Zalith Launcher 本体并不携带某渲染器的情况下，通过渲染器插件自行插入并使用
- 可以同时插入多个渲染器，但如果渲染器 ID 冲突，那么就会进行覆盖 (仅保留一个)
- 直接支持使用 FCL 渲染器插件

### 如何使用？
- 渲染器插件本质上就是一个带有特定标识信息、渲染器 .so 文件本体的安卓安装包
- 你可以在一些地方找到渲染器插件的安装包，直接安装到安卓设备上，启动器就可以自行识别它！
- Zalith Launcher 仅支持包名开头以 `com.mio.plugin.renderer` 或 `com.movtery.zalithplugin.renderer` 的渲染器插件
- 一些渲染器插件可能无法在一些设备上使用，请自行选择！
- 你可以使用 [FCL Renderer Plugin](https://github.com/FCL-Team/FCLRendererPlugin)
 或者 [Zalith Renderer Plugin](https://github.com/ZalithLauncher/ZalithRendererPlugin) 项目自行构建符合要求的渲染器插件！

<div align="end">
    <p>MovTery</p>
    <p>2025/01/14</p>
</div>
