---
title: "IStyleSheet 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.IStyleSheet 接口。StyleSheet 接口是任何类型样式表的抽象基接口。它表示与结构化文档关联的单个样式表。在 HTML 中，StyleSheet 接口表示通过 HTML LINK 元素包含的外部样式表或内联 STYLE 元素。在 XML 中，此接口表示通过样式表处理指令包含的外部样式表。CSS 样式表将进一步实现更专用的 CSSStyleSheet 接口。"
type: docs

url: /zh/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet 接口是任何类型样式表的抽象基接口。它表示与结构化文档关联的单个样式表。在 HTML 中，StyleSheet 接口表示通过 HTML LINK 元素包含的外部样式表或内联 STYLE 元素。在 XML 中，此接口表示通过样式表处理指令包含的外部样式表。CSS 样式表将进一步实现更专用的 [`CSSStyleSheet`](../icssstylesheet/) 接口。

另请参阅 [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface)。

```java
public interface IStyleSheet
```

## 属性

| 名称 | 描述 |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) `StyleSheet` 接口的 href 属性返回样式表的位置。 |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) `StyleSheet` 接口的 media 属性指定样式信息的目标媒体。它是只读的、类数组的 [`MediaList`](../imedialist/) 对象，可通过 deleteMedium() 移除，也可通过 appendMedium() 添加。 |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) 将此样式表与文档关联的节点。对于 HTML，可能是相应的 LINK 或 STYLE 元素。对于 XML，可能是链接的处理指令。对于被其他样式表包含的样式表，此属性的值为 null。 |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) 对于支持样式表包含概念的样式表语言，此属性表示包含该样式表的上级样式表（如果存在）。如果该样式表是顶层样式表，或该语言不支持包含，则此属性的值为 null。 |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) `StyleSheet` 接口的 title 属性返回当前样式表的建议标题。 |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) 这指定了该样式表的语言。样式表语言以内容类型的形式指定（例如 "text/css"）。 |

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### 另请参见

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
