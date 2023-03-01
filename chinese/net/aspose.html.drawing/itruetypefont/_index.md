---
title: Interface ITrueTypeFont
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Drawing.ITrueTypeFont 界面. 声明使用 TrueType 字体的方法
type: docs
weight: 2760
url: /zh/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

声明使用 TrueType 字体的方法。

```csharp
public interface ITrueTypeFont
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | 以字节为单位返回字体数据的大小 |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | 获取字体系列的名称。 |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | 这应该是“FamilyName”和“SubFamilyName”的组合。例外：如果字体为“Regular”，如“SubFamilyName”中 所示，则仅使用“FamilyName”中包含的姓氏。 上述完整字体名称定义的一个例外是 Microsoft 平台字符串 用于 CFF OpenType 字体：在这种情况下，完整字体名称字符串必须与 CFF 名称索引中的 PostScript FontName 相同。 |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | Font Subfamily 名称区分组中具有相同 Font Family 名称的字体。 这假定用于解决样式（斜体、倾斜）和粗细（浅色、粗体、黑色等）。 粗细或样式没有特别差异的字体（例如，中等粗细、非斜体和 fsSelection 位 6 设置）应在该位置存储字符串“Regular”。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | 返回上升点，以点为单位。 |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | 打开带有字体数据的流。调用者负责处理流。 |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | 返回下降点，以点为单位。 |

### 也可以看看

* 命名空间 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 部件 [Aspose.HTML](../../)


