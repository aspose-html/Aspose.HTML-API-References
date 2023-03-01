---
title: FontMatcher.MatchFontFallback
second_title: Aspose.HTML for .NET API 参考
description: FontMatcher 方法. 如果在字体查找文件夹中找不到合适的字体则调用此方法 它应该根据fontMatchingProperties可以渲染charCode 或者无效的如果这种字体不可用.
type: docs
weight: 10
url: /zh/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

如果在字体查找文件夹中找不到合适的字体，则调用此方法。 它应该根据*fontMatchingProperties*可以渲染*charCode*， 或者`无效的`如果这种字体不可用.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | 匹配字体的属性。 |
| charCode | UInt32 | 将使用匹配字体呈现的字符代码。 |

### 返回值

包含字体数据的字节数组或`无效的`.

### 也可以看看

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* 命名空间 [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* 部件 [Aspose.HTML](../../../)


