---
title: "ICSSStyleSheet.InsertRule"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSSStyleSheet 方法。CSSStyleSheet.insertRule 方法将在当前样式表中插入一条新的 CSS 规则，但有一些限制。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

CSSStyleSheet.insertRule() 方法在当前样式表中插入一条新的 CSS 规则，但有一些限制。

注意：虽然 insertRule() 仅是 [`CSSStyleSheet`](../) 的方法，但它实际上是将规则插入到 CSSStyleSheet.cssRules —— 它的内部 [`CSSRuleList`](../../icssrulelist/) 中。

```java
public long InsertRule(String rule, int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 规则 | String | 一个包含待插入规则的字符串。插入的规则必须包含的内容取决于其类型： |
| index | Int32 | 一个小于等于 stylesheet.cssRules.length 的正整数，表示新插入规则在 CSSStyleSheet.cssRules 中的位置。默认值为 0。 |

### 返回值

新插入规则在样式表规则列表中的索引。

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### 另请参见

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
