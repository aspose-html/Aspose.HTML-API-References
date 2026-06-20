---
title: "ITrueTypeFont 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.drawing.ITrueTypeFont 接口。声明用于操作 TrueType 字体的方法。"
type: docs

url: /zh/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

声明用于处理 TrueType 字体的方法。

```java
public interface ITrueTypeFont
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) 返回字体数据的大小（字节）。 |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) 获取字体族的名称。 |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) 这应该是 "FamilyName" 和 "SubFamilyName" 的组合。例外情况：如果 "SubFamilyName" 中指示字体为 "Regular"，则仅使用 "FamilyName" 中的族名。对于 Microsoft 平台的 CFF OpenType 字体，上述完整字体名称的定义还有一个例外：此时完整字体名称字符串必须与 CFF Name INDEX 中的 PostScript FontName 完全相同。 |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) 字体子族名称用于区分同一字体族中的字体。它通常表示样式（斜体、倾斜）和粗细（轻、粗、黑等）。如果字体在粗细或样式上没有特别区别（例如中等粗细、非斜体且 fsSelection 位 6 为 1），则应在此位置存储字符串 "Regular"。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | 返回上升高度，单位为点。 |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | 打开包含字体数据的流。调用方负责释放该流。 |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | 返回下降深度，单位为点。 |

### 另请参见

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
