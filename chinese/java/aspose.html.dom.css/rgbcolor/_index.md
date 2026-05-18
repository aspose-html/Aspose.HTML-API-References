---
title: "RGBColor 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.RGBColor 类。RGBColor 接口用于表示任何 RGB 颜色值。此接口反映底层样式属性中的值。因此，对 CSSPrimitiveValue 对象所做的修改会修改样式属性。"
type: docs

url: /zh/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

RGBColor 接口用于表示任何 RGB 颜色值。该接口反映底层样式属性中的值。因此，对 CSSPrimitiveValue 对象所做的修改会修改样式属性。

指定的 RGB 颜色不会被裁剪（即使数值超出 0-255 或 0%-100% 范围）。计算得到的 RGB 颜色会根据设备进行裁剪。

即使样式表的颜色值只能是整数，该整数的内部存储是浮点数，并且可以在指定样式或计算样式中作为浮点数使用。

颜色百分比值始终可以转换为数字，反之亦然。

```java
public class RGBColor : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) 获取此 Color 结构的 alpha 分量值。 |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) 获取此 Color 结构的 blue 分量值。 |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) 获取此 Color 结构的 green 分量值。 |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) 获取此 Color 结构的 red 分量值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | 转换为本机颜色对象。 |

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### 另请参阅

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
