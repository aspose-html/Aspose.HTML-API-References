---
title: "Document.Navigate"
second_title: "Aspose.HTML for Java API 参考"
description: "Document method. 将指定的统一资源定位符（URL）处的文档加载到当前实例中，替换之前的内容。"
type: docs

url: /zh/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

将位于指定统一资源定位符（URL）的文档加载到当前实例中，替换先前的内容。

```java
public void Navigate(String address)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 地址 | String | 文档地址。它将与当前目录路径组合形成绝对 URL。 |

### 另请参见

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

将位于指定统一资源定位符（URL）的文档加载到当前实例中，替换先前的内容。

```java
public void Navigate(Url url)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 文档 URL。 |

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

从指定内容加载文档，并使用 baseUri 解析相对资源，替换先前的内容。

```java
public void Navigate(String content, String baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 文档内容。 |
| baseUri | String | 用于解析相对资源的基础 URI。它将与当前目录路径组合形成绝对 URL。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参见

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

从指定内容加载文档，并使用 baseUri 解析相对资源，替换先前的内容。

```java
public void Navigate(String content, Url baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 文档内容。 |
| baseUri | Url | 用于解析相对资源的基础 URI。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

从指定内容加载文档，并使用 baseUri 解析相对资源，替换先前的内容。文档加载从流中的当前位置开始。

```java
public void Navigate(Stream content, String baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | 流 | 文档内容。 |
| baseUri | String | 用于解析相对资源的基础 URI。它将与当前目录路径组合形成绝对 URL。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参见

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

从指定内容加载文档，并使用 baseUri 解析相对资源，替换先前的内容。文档加载从流中的当前位置开始。

```java
public void Navigate(Stream content, Url baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | 流 | 文档内容。 |
| baseUri | Url | 用于解析相对资源的基础 URI。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参见

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

根据指定的请求对象加载文档，替换之前的内容。

```java
public void Navigate(RequestMessage request)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 请求 | RequestMessage | 用于加载文档内容的请求对象。 |

### 另请参见

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
