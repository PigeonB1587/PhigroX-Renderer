# 使用方法 Alpha0.1.2.1 PhiNova.PhigroX.Renderer
使用命令行窗口，打开程序，并附上参数。**（注意转义）**

```
{
    "chartJsonPath": "",
    "chartImagePath": "",
    "chartMusicPath": "",
    "chartInfo": {
        "name": "Your Name",
        "differently": "AT",
        "difficultyValue": 15,
        "charter": "",
        "composer": "",
        "Illustrator": "",
        "Introduction": "This is a introduction.",
        "PreviewTime": [
            0,
            10
        ],
        "Tips": [
            "This is a tips!"
        ],
        "Tags": []
    },
    "storyboard": {
        "usingShader": false,
        "usingScaleEvent": true,
        "usingPenEvent": true,
        "usingColorEvent": true,
        "usingTextEvent": true
    },
    "uIboard": {
        "usingStoryboardShader": false,
        "comboText": "COMBO",
        "difficultyValueToText": ""
    },
    "settings": {
        "noteSize": 0.2255,
        "background_brightness": 0.5,
        "music_volume": 1,
        "music_speed": 1,
        "MirrorX": false,
        "MirrorY": false,
        "HL": true,
        "debugMode": true
    },
    "rendererSettings": {
        "targetFrameRate": 60,
        "resolutionX": 1080,
        "resolutionY": 720,
        "isFullScreen": false
    }
}
```
其中三个路径可以是绝对路径，也可以是相对路径（需要将谱面资源置于ChartPool中）。

## 关于设置特别说明 ##

name： 谱面名称 （提示：这个渲染高清修复版本不支持显示中文之类的字符）

notesize: Min=0.22, Max=0.286; *

music_speed: Min=0, Max=3.402823E+38 默认为 1，即原速。

targetFrameRate： = -1 不限帧率， = 0 不渲染。

debugMode： 会显示调试信息以及版本信息。

comboText：combo数字底下的小字，也可以改成"Fanmade"或者"AutoPlay"

usingStoryboardShader: shader覆盖故事板

difficultyValueToText： 可以让原有的定数变成这里面的文本。

## 信息 ##
版本： PhiNova.PhigroX.Renderer Alpha0.1.2.1

作者：Ascmor1587



-
-
-
-

###### * 也可以无视这条规则

