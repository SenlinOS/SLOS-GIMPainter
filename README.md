# ![icon](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-icon.svg)SLOS-GIMPainter
SLOS-GIMPainter is a brush package for **GIMP 2.10.20 or Later**.

[Demo](https://github.com/SenlinOS/SLOS-GIMPainter#demo) | [中文Chinese](https://github.com/SenlinOS/SLOS-GIMPainter/blob/master/README-zh.md)

# Update
SLOS-GIMPainter stable version
- Total: 115 = 107 Brushes + 8 Tools

**2025-02-17➤‍‍**
- Optimization:

    - Delete the (foreground (color parameter in the tool-presets. Only 052_Glow needs this parameter, and others don't need the foreground color parameter.
    - The parameter of the palette is changed to Standard.
    - Uploaded 053a_Gradient-Pen_ForG3.gtp tool preset. If you are using GIMP 3.0 RC3, you can put this file in the tool-presets/SLOS directory and delete the 053a_Gradient-Pen.gtp file. (Because 053a_Gradient-Pen.gtp will not start the default rainbow gradient in GIMP 3.0 RC3.)

2022-04-29
- Improve Tool Presets: 046a_Wet-FanBrush.gtp, 056_Watercolor-1.gtp, 057_Watercolor-2.gtp

2021-06-17
- Added 5 brushes. Please see the screenshot for details, [Here](https://github.com/SenlinOS/databox/blob/master/SLOS-GIMPainter_new-brushes.jpg).

2021-01-09
- Improvement: 016_Digital-Brush, the smudge effect is more obvious.
- Add 15 new brush presets. The video demo for details, [Here](https://youtu.be/NJNWc4V8k4Q).

![img](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-By-SenlinOS.jpg)

The GIMP is a powerful image processing Free (Libre) Software and can certainly be used for painting,
<br />But there is no professional brush set for the GIMP.
<br />The previous Brush Presets is no longer applicable to the current GIMP version.

If you want to paint with GIMP, you have to make your own brushes, which causes inconvenience and waste of time.
<br />Because I decided to use GIMP as the main painting software, I started to make brushes on 2.10.12 and finished on 2.10.14.
<br />But previous versions of GIMP had Bugs in the Tool Options, so I didn't publish the finished brushes.

GIMP 2.10.20 fixed Bugs, and I also added presets and improvements to SLOS-GIMPainter during this period.

**NOTE:** Old Brush Shape files can also continue to be used: .VBR, .GBR, .GIH

- Creating brushes with rich effects in GIMP requires a combination of three settings:
<br />**Brushes (Brush Shape) + Dynamics + Tool Presets**

# Project Name
The project name = `My Name Abbreviation` + `GIMP` + `Painter`

- The word `Painter` to better explain the function of the project. GIMP is adjacent to the `P` in Painter, so the two `P` are merged.

The name of the project is **SLOS-GIMPainter**

# Features
- Brushes are displayed as Icons. (Suitable for users of different languages)
- Orderly arrangement and clear classification.
- Choose a suitable Brush and replace the brush shape to get a new effect. (Avoid always creating new brushes)
- SVG files (Paths) included with the project can be used with brushes to create effect lines.

# Installation

**How to download:** Click the green **Code** button and click **Download ZIP**.
<br />![Code button and Download ZIP](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-Installation/Code_button-and-Download_ZIP.png)

**Menu, Setting Installation:**

- Edit -> Preferences ->(Folders -> Brushes), (Folders -> Dynamics), (Folders -> Tool Presets)
- Click the [Add New Folder] button to open the corresponding directories in the SLOS-GIMPainter folder respectively:

    Example location: `□ /.../SLOS-GIMPainter/brushes`

    Example location: `□ /.../SLOS-GIMPainter/dynamics`

    Example location: `□ /.../SLOS-GIMPainter/tool-presets`

    **Click position 1, 2 and 3 in the screenshot to open the corresponding directory. Click OK to finish.**
    <br />(/home/.../ is the demo location, subject to the location where you store SLOS-GIMPainter)

    ![brushes](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-Installation/1-brushes.jpg)

    ![dynamics](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-Installation/2-dynamics.jpg)

    ![tool-presets](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-Installation/3-tool-presets.jpg)

- Restart GIMP.

**NOTE:** Do not check the box to prevent changing the default setting of SLOS-GIMPainter.

- I didn't install SLOS-GIMPainter by copying the corresponding directory to the GIMP-Profile-Folders. Because the Checkbox cannot be canceled. (maybe you will accidentally modify the default parameters)
- My suggested method is to manually open the corresponding directory in the Project Folder by using the (Edit -> Preferences -> Folders...) of GIMP Menu.

# Show Dialog
Open the Window menu: Dockable Dialogs -> Tool Presets, and you can see SLOS-GIMPainter.

- Click the small triangle button on the upper right of the Tool Presets dialog, and click to `View as Grid`.
- Click the small triangle button on the upper right of the Tool Presets dialog to `Preview Size` and select the `Large`.
- Select the `SLOS` tab at the top of Tool Presets dialog to hide the built-in presets.

    **After setting, in the menu, Edit -> Preferences -> Interface(Window Management), save the settings as shown in the screenshot, and click OK to finish.**

    ![(Window Management](https://raw.githubusercontent.com/SenlinOS/databox/master/SLOS-GIMPainter-Installation/wmment.jpg)

# License
The Project is under an MIT License. See the LICENSE file for more information.

---

![Vimg](https://raw.githubusercontent.com/SenlinOS/databox/master/video-demo-img.jpg)

# Demo
**For a detailed explanation, please see my Video Demo:**
<br />(Silent / Subtitles)

- Install SLOS-GIMPainter and use demos in GIMP, [Here](https://youtu.be/RocoFDBGqE8).
- Replace the brush shape of SLOS-GIMPainter and Make Texture(+GMIC) in GIMP, [Here](https://youtu.be/G4Qt8RiLn8k).
- How to use SLOS-GIMPainter 060 Effect Lines Brush in GIMP, [Here](https://youtu.be/K6lqyK-rDLU).
- Use SLOS-GIMPainter to Draw Radial Lines in GIMP, [Here](https://youtu.be/lC3awNhu76c).
- Add 15 new brush presets. The video demo for details, [Here](https://youtu.be/NJNWc4V8k4Q).

**Text Description:**

- For Line Art, please check the text description: [Here](https://github.com/SenlinOS/databox/blob/master/For-Line-Art_SLOS-GIMPainter.md).
- Manually save temporary presets, the text+video: [Here](https://github.com/SenlinOS/databox/blob/master/manually-save-temporary-presets.md).

**Other Tips:**

- GNU/Linux(X11) software becomes tracing paper, video: [Here](https://youtu.be/ArHPMmIMsq8).

- How to make perspective lines in GIMP, video: [Here](https://youtu.be/gIp5I0fXdlM).

