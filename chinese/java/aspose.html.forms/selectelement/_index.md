---
title: "SelectElement 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.forms.SelectElement 类。SelectElement 表示一个与 HTMLSelectElement 关联的包装器。"
type: docs

url: /zh/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

SelectElement 表示与 HTMLSelectElement 关联的包装器。

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) 获取元素的类型。 |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | 表示输入元素的 Id 属性。 |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | 表示输入元素的 name 属性。 |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) 返回选项列表 |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) 返回已选择选项的列表 |
| [getType](../../com.aspose.html.forms/selectelement/type/) 此表单控件的类型。当 multiple 属性为 `true` 时为字符串 "select-multiple"，当为 `false` 时为字符串 "select-one"。 |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | 获取时，必须返回选项列表中按树顺序的第一个其 selectedness 设置为 true 的 option 元素的值（如果存在）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | 此方法允许通过索引选择多个选项。 |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | 此方法允许通过值选择多个选项。 |

### 另请参阅

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
