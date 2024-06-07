---
title: navigate method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 360
url: /aspose.html.dom/document/navigate/
is_root: false
---

## navigate {#str}

Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content.



```python
def navigate(self, address):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| address | str | The document address. It will be combined with the current directory path to form an absolute URL. |


## navigate {#aspose.html.Url}

Loads the document at the specified Uniform Resource Locator (URL) into the current instance, replacing the previous content.



```python
def navigate(self, url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| url | [`Url`](/html/python-net/aspose.html/url) | The document URL. |


## navigate {#aspose.html.net.RequestMessage}

Loads the document based on specified request object, replacing the previous content.



```python
def navigate(self, request):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| request | aspose.html.net.RequestMessage | The request object that is used to load document content. |


## navigate {#str-str}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.



```python
def navigate(self, content, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| content | str | The document content. |
| base_uri | str | The base URI to resolve relative resources. It will be combined with the current directory path to form an absolute URL. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | `baseUri` is `null`. |




## navigate {#str-aspose.html.Url}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.



```python
def navigate(self, content, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| content | str | The document content. |
| base_uri | [`Url`](/html/python-net/aspose.html/url) | The base URI to resolve relative resources. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | `baseUri` is `null`. |




## navigate {#io.RawIOBase-str}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.
Document loading starts from the current position in the stream.



```python
def navigate(self, content, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| content | io.RawIOBase | The document content. |
| base_uri | str | The base URI to resolve relative resources. It will be combined with the current directory path to form an absolute URL. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | `baseUri` is `null`. |




## navigate {#io.RawIOBase-aspose.html.Url}

Loads the document from specified content and using baseUri to resolve relative resources, replacing the previous content.
Document loading starts from the current position in the stream.



```python
def navigate(self, content, base_uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| content | io.RawIOBase | The document content. |
| base_uri | [`Url`](/html/python-net/aspose.html/url) | The base URI to resolve relative resources. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | `baseUri` is `null`. |





### See Also
* module [`aspose.html.dom`](../../)
* class [`Document`](/html/python-net/aspose.html.dom/document)
