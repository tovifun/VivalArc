CN | [EN](doc_configure-vivaldi.md)

### 💡**几点说明：**

1. 它的本质是使用 Vivaldi 浏览器的自定义 UI MOD 的功能改变外观，整个配置过程大约5分钟
2. 如果想返回原来的效果，只需要将本地的 CSS 删掉
3. 这个配置在 Windows 上也可以使用。在设置快捷键的过程中，只需要将 `Command` 换成 `Ctrl`
4. 在添加 CSS 的时候我只知道如何改变元素样式和隐藏元素，如果你知道如何实现更好的效果，可以跟我分享一下你的CSS😂


### 第一步：安装Vivaldi浏览器

- 因为这本质还是Vivaldi浏览器，所以第一步，去安装一个[Vivaldi浏览器](https://vivaldi.com)吧。如果你之前没用过这个浏览器，可以去它的官网看看，了解它的更多功能。

### 第二步：打开浏览器的设置

> 设置过程中时候，可以在「设置」页左上角进行搜索关键词快速定位

- **外观** > **窗口外观** > `把「在标签中打开设置」勾上`
- **标签** > `「标签栏位置」设置为左侧`
- **标签** > **标签组** > `设置为「折叠式」或者「禁用」（重要）`
- **标签** > **锁定标签** > `将「已锁定标签下方显示分割线」勾上`
- **标签** > **标签处理** > `将「关闭最后一个标签后不关闭窗口」的勾去掉`
- **面板** > **面板选项** > `将「悬浮面板」勾上`
- **地址栏** > `将「显示地址栏」的勾去掉`
- **快捷命令** > `将「在新标签页打开链接」勾上`
- **键盘(**设置必要的快捷键)
    - **新建标签** > 移除「新建标签」的快捷键
    - **快捷命令** > 在原来基础上加上 `Command + T`
    - **页面另存为** > 移除「页面另存为」的快捷键
    - **标签栏** > `Command + S`
    - **地址栏** > `Command + B`（Windows下需先移除「书签」的快捷键）
    - **创建书签** > 移除「创建书签」的快捷键
    - **固定/取消固定标签** > `Command + D`
    - **打印** > 移除「打印」的快捷键
    - **面版** > `Comand + P`

### 第三步：自定义 UI MOD

- [下载这个文件](https://github.com/tovifun/VivalArc/archive/refs/heads/main.zip)，解压保存在一个你不会删除的地方
- 主题 > 打开主题 >  选择ArcLight.zip主题
- 打开 `vivaldi://experiments` 并开启  `"Allow for using CSS modifications"`
- 打开设置 > 外观 > `自定义UI MOD`
- 选择文件夹 > 选择刚才解压的文件夹
- 重启 Vivaldi，这时你应该可以看到你的浏览器效果跟我上方的图片效果一样了
- 换一张你喜欢的壁纸，你刚解压的文件夹里我放了几张进去，可以换上看看

---

## 相关链接

- **Arc评测：**[https://type.cyhsu.xyz/2022/08/arc/](https://type.cyhsu.xyz/2022/08/arc/)
- **Vivaldi官网**：[https://vivaldi.com](https://vivaldi.com/)
- **Vivaldi论坛，Modding Vivaldi：**[https://forum.vivaldi.net/topic/10549/modding-vivaldi](https://forum.vivaldi.net/topic/10549/modding-vivaldi)