<h2 align="center">Zalith Launcher Renderer Plugin Feature</h2>

Due to discrimination and threats from certain extreme individuals in the PojavLauncher community, I have decided to remove the LTW Renderer from Zalith Launcher. However, this does not mean that Zalith Launcher will no longer support the LTW Renderer. Instead, I have implemented a renderer plugin feature, allowing you to load additional renderers by installing renderer plugins!

### Features:
- Add and use renderers via plugins when they are not included in the Zalith Launcher by default.
- Multiple renderers can be added simultaneously. However, if renderer IDs conflict, the conflicting renderers will be overwritten (only one will be retained).
- Direct support for using FCL Renderer Plugins.

### How to Use?
- A renderer plugin is essentially an Android installation package containing specific identification information and the renderer’s `.so` file.
- You can find installation packages for renderer plugins in some repositories, install them directly on your Android device, and the launcher will recognize them automatically!
- Zalith Launcher only supports renderer plugins with package names starting with `com.mio.plugin.renderer` or `com.movtery.zalithplugin.renderer`.
- Some renderer plugins may not work on certain devices. Please choose plugins at your discretion!
- You can use the [FCL Renderer Plugin](https://github.com/FCL-Team/FCLRendererPlugin) or the [Zalith Renderer Plugin](https://github.com/ZalithLauncher/ZalithRendererPlugin) projects to build compatible renderer plugins.

<div align="end">
    <p>MovTery</p>
    <p>2025/01/14</p>
</div>
