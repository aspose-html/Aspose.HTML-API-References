---
title: "FormEditor 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.forms.FormEditor 类。此类表示 HTMLFormElement 的编辑器，为 .net 开发人员提供更简便的方式来编辑 HTML 表单"
type: docs

url: /zh/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

此类表示对 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) 的编辑器，为 .net 开发人员提供更简便的方式来编辑 HTML 表单。

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## 属性

| 名称 | 描述 |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) 表单中表单控件的数量。 |
| [getForm](../../com.aspose.html.forms/formeditor/form/) 与当前 `FormEditor` 实例关联的原始 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)。 |
| [getItem](../../com.aspose.html.forms/formeditor/item/) 根据指定索引返回元素。（2 个索引器） |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | 基于 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) 创建一个新的 `FormEditor`。 |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | 基于从 [`Forms`](../../com.aspose.html/htmldocument/forms/) 集合中按索引选取的 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) 创建一个新的 `FormEditor`。 |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | 基于从文档中按 id 选取的 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) 创建一个新的 `FormEditor`。 |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | 创建一个新的 [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)，并将其关联到 `FormEditor`。[`HTMLFormElement`](../../com.aspose.html/htmlformelement/) 在脱离文档的状态下创建；要将其附加到文档，请选择合适的位置并使用 [`AppendChild`](../../com.aspose.html.dom/node/appendchild/) 方法。 |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | 创建一个新的 [`HTMLElement`](../../com.aspose.html/htmlelement/)，并将其添加到表单的末尾。 |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | 创建一个新的 [`InputElement`](../inputelement/)，并将其添加到表单的末尾。 |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | 创建一个新的 [`InputElement`](../inputelement/)，并将其添加到表单的末尾。 |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | 释放非托管和托管资源。 |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | 根据指定索引返回元素。 |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | 根据指定名称返回元素。 |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | 获取枚举器。 |

### 另请参阅

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
