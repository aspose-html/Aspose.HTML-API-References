---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.HTML for Java API 参考"
description: "FontMatcher 方法。此方法在字体查找文件夹中未找到合适的字体时调用。它应根据 fontMatchingProperties 返回可渲染 charCode 的 TrueType 字体，如果没有可用的字体则返回 `null`。"
type: docs

url: /zh/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

如果在字体查找文件夹中未找到合适的字体，则会调用此方法。它应基于 *fontMatchingProperties* 返回能够渲染 *charCode* 的真字体类型，若不存在此类字体则返回 `null`。

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | 匹配字体的属性。 |
| charCode | UInt32 | 使用匹配字体渲染的字符代码。 |

### 返回值

包含字体数据的字节数组或 `null`。

### 另请参见

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
