---
title: "ITrueTypeFont.FullFontName"
second_title: "Aspose.HTML for Java API 参考"
description: "ITrueTypeFont 属性。它应当是 FamilyName 和 SubFamilyName 的组合。如果 SubFamilyName 指示字体为 Regular，则仅使用 FamilyName 中包含的族名。对于 Microsoft 平台的 CFF OpenType 字体，有一个例外：此情况下 Full font name 字符串必须与 CFF Name INDEX 中的 PostScript FontName 完全相同。"
type: docs

url: /zh/java/com.aspose.html.drawing/itruetypefont/fullfontname/
---
## ITrueTypeFont.FullFontName property

这应该是 "FamilyName" 和 "SubFamilyName" 的组合。例外：如果字体在 "SubFamilyName" 中标记为 "Regular"，则仅使用 "FamilyName" 中包含的族名。对于 Microsoft 平台的 CFF OpenType 字体，上述 Full font name 定义还有一个例外：在这种情况下，Full font name 字符串必须与 CFF Name INDEX 中的 PostScript FontName 完全相同。

```java
public String FullFontName { get; }
```

### 返回值

字体的全名

### 另请参见

* interface [ITrueTypeFont](../)
* package [com.aspose.html.drawing](../../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../../)
