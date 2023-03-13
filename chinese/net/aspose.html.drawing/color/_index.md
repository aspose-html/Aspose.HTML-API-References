---
title: Class Color
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Drawing.Color 班级. 颜色类允许您将颜色指定为 红绿蓝 RGB 值 色调饱和度亮度 HSL 值 色调饱和度值 HSV 值 色调白度黑度 HWB  值 lightnessAB LAB 值 LuminanceChromaHue LCH 值 CyanMagentaYellowKey CMYK 值 Natural colors NCOL 值 或带有颜色名称. Alpha 通道也可用于指示透明度
type: docs
weight: 2640
url: /zh/net/aspose.html.drawing/color/
---
## Color class

颜色类允许您将颜色指定为 红-绿-蓝 (RGB) 值、 色调-饱和度-亮度 (HSL) 值、 色调-饱和度-值 (HSV) 值、 色调-白度-黑度 (HWB) ) 值， lightness-AB (LAB) 值， Luminance-Chroma-Hue (LCH) 值， Cyan-Magenta-Yellow-Key (CMYK) 值， Natural colors (NCOL) 值， 或带有颜色名称. Alpha 通道也可用于指示透明度。

```csharp
public class Color
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Color](color/#constructor)() | 初始化一个新的实例`Color` class. 默认颜色为黑色. |
| [Color](color/#constructor_1)(byte, byte, byte) | 初始化一个新的实例`Color`class. 所有颜色分量必须在 0-255. 范围内 |
| [Color](color/#constructor_5)(float, float, float) | 初始化一个新的实例`Color` class. 所有颜色分量必须在 0-1. 范围内 |
| [Color](color/#constructor_3)(int, int, int) | 初始化一个新的实例`Color`class. 所有颜色分量必须在 0-255. 范围内 |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | 初始化一个新的实例`Color`class. 所有颜色分量必须在 0-255. 范围内 |
| [Color](color/#constructor_6)(float, float, float, float) | 初始化一个新的实例`Color` class. 所有颜色分量必须在 0-1. 范围内 |
| [Color](color/#constructor_4)(int, int, int, int) | 初始化一个新的实例`Color`class. 所有颜色分量必须在 0-255. 范围内 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | 表示颜色的alpha分量。 |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | 代表颜色的蓝色分量。 |
| [Green](../../aspose.html.drawing/color/green/) { get; } | 代表颜色的绿色成分。 |
| [Red](../../aspose.html.drawing/color/red/) { get; } | 代表color 的红色分量 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | 返回具有请求的青色、品红色、黄色、键（黑色）值的新颜色。 |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | 返回具有请求的青色、品红色、黄色、键（黑色）、alpha 值的新颜色。 |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | 返回具有请求的灰度值的新颜色。 |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | 返回具有请求的色调、饱和度、饱和度值的新颜色。 |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | 返回具有请求的色调、饱和度、饱和度、alpha 值的新颜色。 |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | 返回具有请求的色调、饱和度、值的新颜色。 |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | 返回具有请求的色调、饱和度、值、alpha 的新颜色。 |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | 返回具有请求的色调、白度、黑度值的新颜色。 |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | 返回具有请求的色调、白度、黑度值的新颜色。 |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | 返回具有请求的 ARGB 值的新颜色。 |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | 返回具有请求的亮度、A、B 值的新颜色。 |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | 返回具有请求的亮度、A、B、alpha 值的新颜色。 |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | 返回具有请求的亮度、色度、色调值的新颜色。 |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | 返回具有请求的亮度、色度、色调、alpha 值的新颜色。 |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | 返回具有 OKLAB 模型请求的亮度、A、B 值的新颜色。 |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | 返回具有 OKLAB 模型请求的亮度、A、B、alpha 值的新颜色。 |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | 返回具有 OKLAB 模型请求的亮度、色度、色调值的新颜色。 |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | 返回具有 OKLAB 模型请求的亮度、色度、色调、alpha 值的新颜色。 |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | 返回具有请求的 ged、绿色、蓝色值的新颜色。 所有颜色分量必须在 0-255 范围内。 |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | 返回具有请求的 ged、绿色、蓝色值的新颜色。 所有颜色分量必须在 0-1 范围内。 |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | 返回具有请求的 ged、绿色、蓝色值的新颜色。 所有颜色分量必须在 0-255 范围内。 |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | 返回具有请求的 ged、green、blue、alpha 值的新颜色。 所有颜色分量必须在 0-255 范围内。 |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | 返回具有请求的 ged、绿色、蓝色、alpha 值的新颜色。 所有颜色分量必须在 0-1 范围内。 |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | 返回具有请求的 ged、green、blue、alpha 值的新颜色。 所有颜色分量必须在 0-255 范围内。 |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | 解析包含 CSS 颜色的字符串并返回一个新的 Color. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | 返回具有请求的 ARGB 值的新颜色。 |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | 创建颜色的副本及其亮度和增量值的总和。 |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | 以指定颜色模型的格式返回颜色分量。 |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | 判断指定的是否`Color`等于这个实例. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | 返回与原始色轮相反一侧的新颜色。 |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | 返回哈希码。 |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | 返回颜色的色调。 |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | 返回颜色的亮度。 |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | 返回颜色的饱和度。 |
| [ToInt](../../aspose.html.drawing/color/toint/)() | 将颜色 ARGB 分量编码为 int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | 如果颜色与 CSS 命名颜色列表中的颜色匹配，则返回颜色名称，或者返回空字符串。 |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | 返回自然色 (NCol) 指定的颜色，使用带有数字的颜色字母指定与颜色的距离（百分比）。 |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | 返回指定的十六进制颜色：#RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | 返回包含 RGBA 颜色的字符串：rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | 返回指定的十六进制颜色：#RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | 返回包含由以下指定的 RGB 颜色的字符串：rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | 返回由 RGBA 分量值组成的字符串。 |
| [ToUint](../../aspose.html.drawing/color/touint/)() | 将颜色 ARGB 分量编码为无符号整数。 |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | 创建具有指定 alpha 分量的颜色副本。 |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | 创建具有指定色调的颜色副本。 |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | 创建具有指定亮度的颜色副本。 |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | 创建具有指定饱和度的颜色副本。 |

### 也可以看看

* 命名空间 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 部件 [Aspose.HTML](../../)


