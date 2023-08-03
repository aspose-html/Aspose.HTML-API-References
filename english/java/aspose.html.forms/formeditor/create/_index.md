---
title: FormEditor.Create
second_title: Aspose.HTML for Java API Reference
description: FormEditor method. Creates a new FormEditor based on HTMLFormElement
type: docs
weight: 10
url: /net/com.aspose.html.forms/formeditor/create/
---
## Create(HTMLFormElement) {#create_2}

Creates a new [`FormEditor`](../) based on [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/).

```java
public static FormEditor Create(HTMLFormElement form)
```

| Parameter | Type | Description |
| --- | --- | --- |
| form | HTMLFormElement | The html form element |

### Return Value

Return a new instance of the [`FormEditor`](../) class

### See Also

* class [HTMLFormElement](../../../com.aspose.html/htmlformelement/)
* class [FormEditor](../)
* package [com.aspose.html.Forms](../../formeditor/)
* package [Aspose.HTML](../../../)

---

## Create(HTMLDocument, int) {#create}

Creates a new [`FormEditor`](../) based on [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/) selected from the [`Forms`](../../../com.aspose.html/htmldocument/forms/) collection by index.

```java
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
| [dOMException](../../../com.aspose.html.dom/domexception/) | The exception is occured if index out of the range. |

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [FormEditor](../)
* package [com.aspose.html.Forms](../../formeditor/)
* package [Aspose.HTML](../../../)

---

## Create(HTMLDocument, String) {#create_1}

Creates a new [`FormEditor`](../) based on [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/) selected from the document by id.

```java
public static FormEditor Create(HTMLDocument document, String id)
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
| [dOMException](../../../com.aspose.html.dom/domexception/) | The exception is occured if there is no element by specified Id or element is not a form type. |

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [FormEditor](../)
* package [com.aspose.html.Forms](../../formeditor/)
* package [Aspose.HTML](../../../)
