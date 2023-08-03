---
title: Document.Navigate
second_title: Aspose.HTML for Java API Reference
description: Document method. Loads the document at the specified Uniform Resource Locator URL into the current instance replacing the previous content
type: docs
weight: 1010
url: /net/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content.

```java
public void Navigate(String address)
```

| Parameter | Type | Description |
| --- | --- | --- |
| address | String | The document address. It will be combined with the current directory path to form an absolute URL. |

### See Also

* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content.

```java
public void Navigate(Url url)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | The document URL. |

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.

```java
public void Navigate(String content, String baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The document content. |
| baseUri | String | The base URI to resolve relative resources. It will be combined with the current directory path to form an absolute URL. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### See Also

* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.

```java
public void Navigate(String content, Url baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The document content. |
| baseUri | Url | The base URI to resolve relative resources. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream.

```java
public void Navigate(Stream content, String baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | Stream | The document content. |
| baseUri | String | The base URI to resolve relative resources. It will be combined with the current directory path to form an absolute URL. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### See Also

* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream.

```java
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | Stream | The document content. |
| baseUri | Url | The base URI to resolve relative resources. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Loads the document based on specified request object, replacing the previous content.

```java
public void Navigate(RequestMessage request)
```

| Parameter | Type | Description |
| --- | --- | --- |
| request | RequestMessage | The request object that is used to load document content. |

### See Also

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)
