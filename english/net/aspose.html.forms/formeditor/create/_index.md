---
title: FormEditor.Create
second_title: Aspose.HTML for .NET API Reference
description: FormEditor Create method. Creates a new FormEditor based on HTMLFormElement
type: docs
weight: 10
url: /net/aspose.html.forms/formeditor/create/
---
## Create(*[HTMLFormElement](../../../aspose.html/htmlformelement/)*) {#create_2}

Creates a new [`FormEditor`](../) based on [`HTMLFormElement`](../../../aspose.html/htmlformelement/).

```csharp
public static FormEditor Create(HTMLFormElement form)
```

| Parameter | Type | Description |
| --- | --- | --- |
| form | HTMLFormElement | The html form element |

### Return Value

Return a new instance of the [`FormEditor`](../) class

### See Also

* class [HTMLFormElement](../../../aspose.html/htmlformelement/)
* class [FormEditor](../)
* namespace [Aspose.Html.Forms](../../../aspose.html.forms/)
* assembly [Aspose.HTML](../../../)

---

## Create(*[HTMLDocument](../../../aspose.html/htmldocument/), int*) {#create}

Creates a new [`FormEditor`](../) based on [`HTMLFormElement`](../../../aspose.html/htmlformelement/) selected from the [`Forms`](../../../aspose.html/htmldocument/forms/) collection by index.

```csharp
public static FormEditor Create(HTMLDocument document, int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | The document. |
| index | Int32 | The index inside the forms collection. |

### Return Value

Return a new instance of the [`FormEditor`](../) class

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | The exception is occured if index out of the range. |

### See Also

* class [HTMLDocument](../../../aspose.html/htmldocument/)
* class [FormEditor](../)
* namespace [Aspose.Html.Forms](../../../aspose.html.forms/)
* assembly [Aspose.HTML](../../../)

---

## Create(*[HTMLDocument](../../../aspose.html/htmldocument/), string*) {#create_1}

Creates a new [`FormEditor`](../) based on [`HTMLFormElement`](../../../aspose.html/htmlformelement/) selected from the document by id.

```csharp
public static FormEditor Create(HTMLDocument document, string id)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | The document. |
| id | String | The identifier. |

### Return Value

Return a new instance of the [`FormEditor`](../) class

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | The exception is occured if there is no element by specified Id or element is not a form type. |

### See Also

* class [HTMLDocument](../../../aspose.html/htmldocument/)
* class [FormEditor](../)
* namespace [Aspose.Html.Forms](../../../aspose.html.forms/)
* assembly [Aspose.HTML](../../../)
