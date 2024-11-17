# ![icon](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-icon.svg)SLOS-GIMPainter
SLOS-GIMPainter 是为 GIMP 2.10.20 或更高版本的画笔包。

[演示](https://space.bilibili.com/14824534/channel/seriesdetail?sid=1169812&ctype=0) | [English Description](https://github.com/SenlinOS/SLOS-GIMPainter)

# 更新
SLOS-GIMPainter 稳定版
- 总计：115个 = 107个画笔 + 8个工具

**2022-04-29**
- 改进工具预设：046a_Wet-FanBrush.gtp, 056_Watercolor-1.gtp, 057_Watercolor-2.gtp

2021-06-17
- 增加了5个画笔。详情请看截图，[这里](https://github.com/SenlinOS/databox/blob/master/SLOS-GIMPainter_new-brushes-zh.jpg)。

2021-01-09
- 改进：016_Digital-Brush (数码画笔)，涂抹效果更明显。
- 新增15个笔刷预设。视频演示：[这里](https://www.bilibili.com/video/BV1g5411n7JU)

![img](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-By-SenlinOS.jpg)

GIMP 是功能强大的图像处理自由软件，当然也可以用来绘画，但对于现在的 GIMP 来说没有一套专业的画笔。
<br />以前的画笔预设已经不适用于现在的 GIMP 版本，如果想用 GIMP 绘画的用户必须自己去制作画笔，从而造成不便与浪费时间。

因为我决定使用 GIMP 作为主要绘画软件，所以我从 2.10.12 开始制作画笔，到 2.10.14 制作完毕，
<br />但是以前这些 GIMP 版本在工具选项都存在 Bugs，所以我没有将制作完成的画笔发布。

GIMP 2.10.20 修复了 Bugs，我在这段时间也对 SLOS-GIMPainter 增加了预设与改进效果。

**注意：** 以前的画笔形状文件也可以继续使用：.VBR、.GBR、.GIH

- 在GIMP中创建丰富效果的画笔需要三个设置的组合：
<br />**笔刷 (画笔形状) + 动态 + 工具预设**

# 项目名称
这个项目的名称 = `我的名字缩写` + `GIMP` + `Painter`

- **Painter** 这个词更能说明项目的功能，GIMP 与 Painter 中的 `p` 相邻，所以将这两个 `p` 合并。

项目名称就是 **SLOS-GIMPainter**

# 特点
- 画笔显示为图标。(适合不同语言的用户)
- 排列有序，分类清晰。
- 选择合适的画笔并替换笔刷形状以获得新的效果。(避免总是创建新画笔)
- 项目中包含的SVG文件(路径)可以与画笔一起使用来创建效果线。

# 安装方法

**如何下载：** 在GitHub项目中，点击绿色的 **Code** 按钮，然后点击 **Download ZIP**。
<br />国内用户也可以在我的爱发电附件中下载：[这里](https://afdian.net/p/e5596c4e894d11ecaed752540025c377)，或微云网盘下载：[这里](https://share.weiyun.com/IMP3xYlL)

**菜单，设置安装：**

- 编辑 -> 首选项 ->(文件夹 -> 笔刷)、(文件夹 -> 动态)、(文件夹 -> 工具预设)
- 点击 [添加新文件夹] 按钮，分别打开 SLOS-GIMPainter 文件夹中对应的目录：

    示例位置： `□ /.../SLOS-GIMPainter/brushes`

    示例位置： `□ /.../SLOS-GIMPainter/dynamics`

    示例位置： `□ /.../SLOS-GIMPainter/tool-presets`

    **依次点击图中的 1、2、3 位置打开对应的目录。点击确定按钮完成。**
    <br />（ /home/.../ 是演示位置，以你存放 SLOS-GIMPainter 的位置为准）

    ![brushes](https://raw.githubusercontent.com/SenlinOS/senlinos.github.io/master/img/1-brushes.jpg)

    ![dynamics](https://raw.githubusercontent.com/SenlinOS/senlinos.github.io/master/img/2-dynamics.jpg)

    ![tool-presets](https://raw.githubusercontent.com/SenlinOS/senlinos.github.io/master/img/3-tool-presets.jpg)

- 重启 GIMP

**注意：** 不要勾选前面的复选框，避免更改 SLOS-GIMPainter 的默认设置。

- 我没有通过将相应目录复制到GIMP配置文件文件夹来安装SLOS-GIMPainter。因为复选框不能取消。(也许你会不小心修改默认参数)
- 我建议的方法是使用GIMP的菜单（编辑 -> 首选项 -> 文件夹...）手动打开这个项目文件夹中的相应目录。

# 显示对话框
打开 窗口菜单：可停靠对话框 -> 工具预设，就可以看到 SLOS-GIMPainter

- 点击工具预设对话框右上的小三角形按钮，点击`以网格方式查看`
- 点击工具预设对话框右上的小三角形按钮，`预览大小`，选择`较大`
- 选择工具预设对话框上方的 `SLOS` 标签，可以隐藏 GIMP 的内置预设。

    **设置完成后，在菜单，编辑 -> 首选项 -> 界面(窗口管理)中，如图操作保存设置，点击确定按钮完成。**

    ![wmment](https://raw.githubusercontent.com/SenlinOS/senlinos.github.io/master/img/wmment.jpg)

# 许可证
本项目采用 MIT 许可证。有关更多信息，请参见 LICENSE 文件。

---

![Vimg](https://raw.githubusercontent.com/SenlinOS/databox/master/video-demo-img.jpg)

**关于详细的讲解，请看我的视频演示：**
<br />(无声 / 字幕)

[在B站的演示视频合集](https://space.bilibili.com/14824534/channel/seriesdetail?sid=1169812&ctype=0)。

对于线艺术，请查看文字说明：[这里](https://github.com/SenlinOS/databox/blob/master/For-Line-Art_SLOS-GIMPainter.md)。

手动保存临时预设：[这里](https://senlinos.github.io/post/manually-save-temporary-presets/) 和 [这里](https://t.bilibili.com/519640070146405433?tab=2)。

**其他技巧：**

- GNU/Linux(X11)中将软件变成描图纸：[我的B站视频](https://www.bilibili.com/video/BV18R4y1j7g6)。

- GIMP中怎样制作透视线：[我的B站视频](https://www.bilibili.com/video/BV1AS4y1V7AB)。
