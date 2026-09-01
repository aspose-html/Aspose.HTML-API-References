---
title: "Color 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.drawing.Color 类。Color 类允许您以 Red-Green-Blue RGB 值、Hue-Saturation-Luminosity HSL 值、Hue-Saturation-Value HSV 值、Hue-Whiteness-Blackness HWB 值、lightness-A-B LAB 值、Luminance-Chroma-Hue LCH 值、Cyan-Magenta-Yellow-Key CMYK 值、Natural colors NCOL 值或颜色名称来指定颜色。还提供 Alpha 通道以指示透明度。"
type: docs

url: /zh/java/com.aspose.html.drawing/color/
---
## Color class

Color 类允许您以红绿蓝 (RGB) 值、色相-饱和度-亮度 (HSL) 值、色相-饱和度-值 (HSV) 值、色相-白度-黑度 (HWB) 值、亮度-A-B (LAB) 值、亮度-色度-色相 (LCH) 值、青品红-黄-键 (CMYK) 值、自然颜色 (NCOL) 值，或使用颜色名称来指定颜色。Alpha 通道也可用于指示透明度。

```java
public class Color
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Color](color/#constructor)() | 初始化 `Color` 类的新实例。默认颜色为黑色。 |
| [Color](color/#constructor_1)(byte, byte, byte) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-255 范围内。 |
| [Color](color/#constructor_5)(float, float, float) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-1 范围内。 |
| [Color](color/#constructor_3)(int, int, int) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-255 范围内。 |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-255 范围内。 |
| [Color](color/#constructor_6)(float, float, float, float) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-1 范围内。 |
| [Color](color/#constructor_4)(int, int, int, int) | 初始化 `Color` 类的新实例。所有颜色分量必须在 0-255 范围内。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) 表示颜色的 Alpha 分量。 |
| [getBlue](../../com.aspose.html.drawing/color/blue/) 表示颜色的蓝色分量。 |
| [getGreen](../../com.aspose.html.drawing/color/green/) 表示颜色的绿色分量。 |
| [getRed](../../com.aspose.html.drawing/color/red/) 表示颜色的红色分量 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | 返回具有指定青色、品红、黄色、关键（黑色）值的新 Color。 |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | 返回具有指定青色、品红、黄色、关键（黑色）和 Alpha 值的新 Color。 |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | 返回具有指定灰度值的新 Color。 |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | 返回具有指定色相、饱和度、饱和度值的新 Color。 |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | 返回具有指定色相、饱和度、饱和度和 Alpha 值的新 Color。 |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | 返回具有指定色相、饱和度、值的新 Color。 |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | 返回具有指定色相、饱和度、值和 Alpha 的新 Color。 |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | 返回具有指定色相、白度、黑度值的新 Color。 |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | 返回具有指定色相、白度、黑度值的新 Color。 |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | 返回具有指定 ARGB 值的新 Color。 |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | 返回具有指定亮度、A、B 值的新 Color。 |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | 返回一个具有请求的亮度、A、B、alpha 值的新 Color。 |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | 返回一个具有请求的亮度、色度、色相值的新 Color。 |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | 返回一个具有请求的亮度、色度、色相、alpha 值的新 Color。 |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | 返回一个针对 OKLAB 模型、具有请求的亮度、A、B 值的新 Color。 |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | 返回一个针对 OKLAB 模型、具有请求的亮度、A、B、alpha 值的新 Color。 |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | 返回一个针对 OKLAB 模型、具有请求的亮度、色度、色相值的新 Color。 |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | 返回一个针对 OKLAB 模型、具有请求的亮度、色度、色相、alpha 值的新 Color。 |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | 返回一个具有请求的 ged、green、blue 值的新 Color。所有颜色分量必须在 0-255 范围内。 |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | 返回一个具有请求的 ged、green、blue 值的新 Color。所有颜色分量必须在 0-1 范围内。 |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | 返回一个具有请求的 ged、green、blue 值的新 Color。所有颜色分量必须在 0-255 范围内。 |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | 返回一个具有请求的 ged、green、blue、alpha 值的新 Color。所有颜色分量必须在 0-255 范围内。 |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | 返回一个具有请求的 ged、green、blue、alpha 值的新 Color。所有颜色分量必须在 0-1 范围内。 |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | 返回一个具有请求的 ged、green、blue、alpha 值的新 Color。所有颜色分量必须在 0-255 范围内。 |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | 解析包含 CSS 颜色的 String 并返回一个新 Color。 |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | 返回具有指定 ARGB 值的新 Color。 |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | 创建一个 Color 的副本，其亮度与 delta 值之和。 |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | 返回指定颜色模型格式的颜色分量。 |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | 确定指定的 `Color` 是否等于此实例。 |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | 返回一个位于色轮相对侧的原始颜色的新颜色。 |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | 返回哈希码。 |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | 返回 Color 的色相。 |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | 返回 Color 的亮度。 |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | 返回 Color 的饱和度。 |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | 将 Color 的 ARGB 分量编码为 int。 |
| [toName](../../com.aspose.html.drawing/color/toname/)() | 如果颜色匹配 CSS 命名颜色列表中的颜色，则返回该颜色的名称；否则返回空 String。 |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | 返回使用颜色字母和数字指定与颜色距离（百分比）的自然颜色 (NCol) 指定颜色。 |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | 返回使用十六进制表示的颜色，格式为：#RRGGBBAA。 |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | 返回一个包含 RGBA 颜色的 String，格式为：rgba(R, G, B, A)。 |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | 返回使用十六进制颜色表示的值，格式为：#RRGGBB。 |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | 返回一个字符串，包含通过 rgb(R, G, B) 指定的 RGB 颜色。 |
| [toString](../../com.aspose.html.drawing/color/toString/)() | 返回一个字符串，由 RGBA 组件值组成。 |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | 将颜色的 ARGB 组件编码为无符号整数。 |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | 创建颜色的副本，并使用指定的 alpha 组件。 |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | 创建颜色的副本，并使用指定的色相（Hue）。 |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | 创建颜色的副本，并使用指定的亮度（luminosity）。 |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | 创建颜色的副本，并使用指定的饱和度（saturation）。 |

### 另请参见

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
