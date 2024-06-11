---
title: to_data_url method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 410
url: /python-net/aspose.html/htmlcanvaselement/to_data_url/
is_root: false
---

## to_data_url {#}

returns a data URI containing a representation of the image in the format specified by the type parameter (defaults to PNG). 
The returned image is in a resolution of 96 dpi.


### Returns 


A DOMString containing the requested data URI.


```python
def to_data_url(self):
    ...
```




## to_data_url {#str}

returns a data URI containing a representation of the image in the format specified by the type parameter (defaults to PNG). 
The returned image is in a resolution of 96 dpi.


### Returns 


A DOMString containing the requested data URI.


```python
def to_data_url(self, type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | str | A string indicating the image format. The default format type is image/png. |


## to_data_url {#str-float}

returns a data URI containing a representation of the image in the format specified by the type parameter (defaults to PNG). 
The returned image is in a resolution of 96 dpi.


### Returns 


A DOMString containing the requested data URI.


```python
def to_data_url(self, type, encoder_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | str | A string indicating the image format. The default format type is image/png. |
| encoder_options | float | A Number between 0 and 1 indicating image quality if the requested type is image/jpeg or image/webp. |



### See Also
* module [`aspose.html`](../../)
* class [`HTMLCanvasElement`](/html/python-net/aspose.html/htmlcanvaselement)
