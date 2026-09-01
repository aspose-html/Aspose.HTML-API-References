---
title: "ICSS2Properties.Display"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSS2Properties 属性。此属性的取值具有以下含义"
type: docs

url: /zh/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

此属性的取值具有以下含义：

block - 此取值使元素生成一个主块盒子。inline - 此取值使元素生成一个或多个内联盒子。list-item - 此取值使元素（例如 HTML 中的 LI）生成一个主块盒子和一个列表项内联盒子。有关列表的信息和列表格式示例，请参阅 [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists) 部分。marker - 此取值声明在盒子之前或之后的 [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) 为标记。该取值应仅与附加在块级元素上的 [:before and :after pseudo-elements](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) 一起使用。在其他情况下，此取值被解释为 “inline”。更多信息请参阅 [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) 部分。none - 此取值使元素在 [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) 中不生成任何盒子（即元素对布局没有影响）。后代元素也不生成任何盒子；通过在后代上设置 ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) 属性无法覆盖此行为。请注意，display 为 “none” 并不会创建一个不可见的盒子，而是根本不创建盒子。CSS 包含机制，使元素能够在格式结构中生成影响布局但自身不可见的盒子。详情请参阅 [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) 部分。run-in and compact - 这些取值根据上下文创建块盒子或内联盒子。属性根据其最终状态（内联级或块级）应用于 run-in 和 compact 盒子。例如，['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) 属性仅在盒子成为块盒子时适用。table、inline-table、table-row-group、[table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column)、table-column-group、table-header-group、table-footer-group、table-row、table-cell 和 table-caption - 这些取值使元素表现得像表格元素（受 [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html) 章节中描述的限制约束）。

```java
public String Display { get; set; }
```

### 返回值

display 属性

### 另请参见

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
