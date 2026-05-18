---
title: "FontMatcher 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.fonts.FontMatcher 类。此类允许您控制字体匹配算法的某些部分。"
type: docs

url: /zh/java/com.aspose.html.rendering.fonts/fontmatcher/
---
## FontMatcher class

此类允许您控制字体匹配算法的某些部分。

```java
public abstract class FontMatcher
```

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [MatchFontFallback](../../com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/)(FontMatchingProperties, uint) | 如果在字体查找文件夹中未找到合适的字体，则调用此方法。它应基于 *fontMatchingProperties* 返回能够渲染 *charCode* 的真字体类型，如果没有可用的此类字体，则返回 `null`。 |

### 另请参阅

* package [com.aspose.html.rendering.fonts](../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../)
