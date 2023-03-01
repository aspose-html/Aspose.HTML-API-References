---
title: Class FormEditor
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Forms.FormEditor 班级. 这个类代表编辑器HTMLFormElement这为 .net 开发人员创建了一种更简单的方法来编辑 html 表单
type: docs
weight: 2930
url: /zh/net/aspose.html.forms/formeditor/
---
## FormEditor class

这个类代表编辑器[`HTMLFormElement`](../../aspose.html/htmlformelement/)这为 .net 开发人员创建了一种更简单的方法来编辑 html 表单。

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | 服务器端表单处理程序。请参阅 HTML 4.01. 中的 action 属性定义 |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | 窗体中的窗体控件个数。 |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | 原来的[`HTMLFormElement`](../../aspose.html/htmlformelement/)与当前实例关联的`FormEditor`. |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | 按指定索引返回元素。 (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP 方法 [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) 用于提交表单。参见 HTML 4.01. 中的方法属性定义 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | 创建一个新的`FormEditor`基于[`HTMLFormElement`](../../aspose.html/htmlformelement/). |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | 创建一个新的`FormEditor`基于[`HTMLFormElement`](../../aspose.html/htmlformelement/)选自[`Forms`](../../aspose.html/htmldocument/forms/)按索引收集。 |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | 创建一个新的`FormEditor`基于[`HTMLFormElement`](../../aspose.html/htmlformelement/)通过 id. 从文档中选择 |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | 创建一个新的[`HTMLFormElement`](../../aspose.html/htmlformelement/)并将其与`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/)是在脱离文档状态下创建的；为了将其附加到文档中，请选择适当的位置和使用[`AppendChild`](../../aspose.html.dom/node/appendchild/)方法. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | 创建一个新的[`HTMLElement`](../../aspose.html/htmlelement/)并将其添加到表单的末尾。 |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | 创建一个新的[`InputElement`](../inputelement/)并将其添加到表单的末尾。 |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | 创建一个新的[`InputElement`](../inputelement/)并将其添加到表单的末尾。 |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | 释放非托管和托管资源。 |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | 此方法使用指定的值填充整个表单。 |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | 按指定索引返回元素。 |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | 按指定名称返回元素。 |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | 获取枚举器。 |

### 也可以看看

* class [FormElement](../formelement/)
* 命名空间 [Aspose.Html.Forms](../../aspose.html.forms/)
* 部件 [Aspose.HTML](../../)


