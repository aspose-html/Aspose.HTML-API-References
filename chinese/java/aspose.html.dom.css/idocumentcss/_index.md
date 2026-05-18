---
title: "IDocumentCSS 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.IDocumentCSS 接口。此接口表示具有 CSS 视图的文档。"
type: docs

url: /zh/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

此接口表示具有 CSS 视图的文档。

getOverrideStyle 方法提供了一种机制，使 DOM 作者能够在不修改文档显式链接的样式表或样式表中元素的内联样式的情况下，立即更改元素的样式。该样式表在层叠算法中位于作者样式表之后，称为覆盖样式表。覆盖样式表优先于作者样式表。\"!important\" 声明仍然优先于普通声明。覆盖、作者和用户样式表都可能包含 \"!important\" 声明。用户的 \"!important\" 规则优先于覆盖和作者的 \"!important\" 规则，而覆盖的 \"!important\" 规则优先于作者的 \"!important\" 规则。

预期可以通过对 Document 接口实例使用特定绑定的强制转换方法来获取 DocumentCSS 接口的实例。

另请参阅 [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)。

```java
public interface IDocumentCSS : IDocumentStyle
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | 此方法用于检索指定元素和指定伪元素的覆盖样式声明。 |

### 另请参阅

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
