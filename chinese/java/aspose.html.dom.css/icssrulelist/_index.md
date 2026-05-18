---
title: "ICSSRuleList 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSRuleList 接口。CSSRuleList 表示只读 CSSRule 对象的有序集合"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

CSSRuleList 表示只读 [`CSSRule`](../icssrule/) 对象的有序集合。

虽然 CSSRuleList 对象是只读的，且不能直接修改，但它被视为实时对象，因为其内容可以随时间变化。

要编辑由 [`CSSRule`](../icssrule/) 对象返回的底层规则，请使用 CSSStyleSheet.insertRule() 和 CSSStyleSheet.deleteRule()，它们是 [`CSSStyleSheet`](../icssstylesheet/) 的方法。

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) 用于通过 item() 方法检索 CSS 规则 (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList)。此集合中的顺序代表 CSS 样式表中规则的顺序。如果索引大于或等于列表中的规则数，则返回 null。 |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) `CSSRuleList` 接口的 length 属性返回列表中 [`CSSRule`](../icssrule/) 对象的数量。 |

### 另请参阅

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
