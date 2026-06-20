---
title: "IStyleSheet.Media"
second_title: "Aspose.HTML for Java API 参考"
description: "IStyleSheet 属性。StyleSheet 接口的 media 属性指定样式信息的目标媒体。它是只读的类数组 MediaList 对象，可通过 deleteMedium 删除并通过 appendMedium 添加。"
type: docs

url: /zh/java/com.aspose.html.dom.css/istylesheet/media/
---
## IStyleSheet.Media property

[`StyleSheet`](../) 接口的 media 属性指定样式信息的目标媒体。它是只读的、类数组的 [`MediaList`](../../imedialist/) 对象，可通过 deleteMedium() 删除并通过 appendMedium() 添加。

```java
public IMediaList Media { get; }
```

### Property Value

media 属性必须返回与 CSS 样式表关联的 [`MediaList`](../../imedialist/) 对象。

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-media](https://drafts.csswg.org/cssom/#dom-stylesheet-media) – The CSSOM definition.

### 另请参见

* interface [IMediaList](../../imedialist/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
