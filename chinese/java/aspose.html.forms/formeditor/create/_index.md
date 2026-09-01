---
title: "FormEditor.Create"
second_title: "Aspose.HTML for Java API 参考"
description: "FormEditor 方法。基于 HTMLFormElement 创建一个新的 FormEditor"
type: docs

url: /zh/java/com.aspose.html.forms/formeditor/create/
---
## Create(HTMLFormElement) {#create_2}

创建一个基于 [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/) 的新 [`FormEditor`](../)。

```java
public static FormEditor Create(HTMLFormElement form)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 表单 | HTMLFormElement | HTML 表单元素 |

### 返回值

返回 [`FormEditor`](../) 类的新实例

### 另请参见

* class [HTMLFormElement](../../../com.aspose.html/htmlformelement/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)

---

## Create(HTMLDocument, int) {#create}

创建一个基于从 [`Forms`](../../../com.aspose.html/htmldocument/forms/) 集合中按索引选择的 [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/) 的新 [`FormEditor`](../)。

```java
public static FormEditor Create(HTMLDocument document, int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | HTMLDocument | 文档。 |
| index | Int32 | 表单集合中的索引 |

### 返回值

返回 [`FormEditor`](../) 类的新实例

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 如果索引超出范围，将抛出异常。 |

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)

---

## Create(HTMLDocument, String) {#create_1}

创建一个基于通过 id 从文档中选择的 [`HTMLFormElement`](../../../com.aspose.html/htmlformelement/) 的新 [`FormEditor`](../)。

```java
public static FormEditor Create(HTMLDocument document, String id)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | HTMLDocument | 文档。 |
| id | String | 标识符。 |

### 返回值

返回 [`FormEditor`](../) 类的新实例

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 如果不存在指定 Id 的元素或元素不是表单类型，将抛出异常。 |

### 另请参见

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [FormEditor](../)
* package [com.aspose.html.forms](../../../com.aspose.html.forms/)
* package [Aspose.HTML](../../../)
