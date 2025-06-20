---
title: Document.Navigate
second_title: Aspose.HTML for .NET API Reference
description: Document Navigate method. Loads the document at the specified Uniform Resource Locator URL into the current instance replacing the previous content
type: docs
weight: 1010
url: /net/aspose.html.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content.

```csharp
public void Navigate(string address)
```

| Parameter | Type | Description |
| --- | --- | --- |
| address | String | The document address. It will be combined with the current directory path to form an absolute URL. |

### See Also

* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*[Url](../../../aspose.html/url/)*) {#navigate_2}

Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content.

```csharp
public void Navigate(Url url)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | The document URL. |

### See Also

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*string, string*) {#navigate_11}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.

```csharp
public void Navigate(string content, string baseUri)
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
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*string, [Url](../../../aspose.html/url/)*) {#navigate_9}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.

```csharp
public void Navigate(string content, Url baseUri)
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

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream.

```csharp
public void Navigate(Stream content, string baseUri)
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
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.html/url/)*) {#navigate_4}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream.

```csharp
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

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.html.net/requestmessage/)*) {#navigate}

Loads the document based on specified request object, replacing the previous content.

```csharp
public void Navigate(RequestMessage request)
```

| Parameter | Type | Description |
| --- | --- | --- |
| request | RequestMessage | The request object that is used to load document content. |

### See Also

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content.

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| address | String | The document address. It will be combined with the current directory path to form an absolute URL. |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |

### See Also

* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*[Url](../../../aspose.html/url/), CancellationToken*) {#navigate_3}

Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content.

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | The document URL. |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |

### See Also

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The document content. |
| baseUri | String | The base URI to resolve relative resources. It will be combined with the current directory path to form an absolute URL. |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |
| ArgumentNullException | `baseUri` is `null`. |

### See Also

* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*string, [Url](../../../aspose.html/url/), CancellationToken*) {#navigate_10}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The document content. |
| baseUri | Url | The base URI to resolve relative resources. |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |
| ArgumentNullException | `baseUri` is `null`. |

### See Also

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream.

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | Stream | The document content. |
| baseUri | String | The base URI to resolve relative resources. It will be combined with the current directory path to form an absolute URL. |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |
| ArgumentNullException | `baseUri` is `null`. |

### See Also

* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.html/url/), CancellationToken*) {#navigate_5}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content. Document loading starts from the current position in the stream.

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | Stream | The document content. |
| baseUri | Url | The base URI to resolve relative resources. |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |
| ArgumentNullException | `baseUri` is `null`. |

### See Also

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.html.net/requestmessage/), CancellationToken*) {#navigate_1}

Loads the document based on specified request object, replacing the previous content.

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| request | RequestMessage | The request object that is used to load document content. |
| cancellationToken | CancellationToken | The cancellation token. |

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | Operation was cancelled. |

### See Also

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
