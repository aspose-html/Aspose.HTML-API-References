---
title: ICSS2Properties.WhiteSpace
second_title: Aspose.HTML for Java API Reference
description: ICSS2Properties property. This property declares how whitespace inside the element is handled. Values have the following meanings
type: docs

url: /java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

This property declares how [whitespace](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace) inside the element is handled. Values have the following meanings:

normal - This value directs user agents to collapse sequences of whitespace, and break lines as necessary to fill line boxes. Additional line breaks may be created by occurrences of "\A" in generated content (e.g., for the BR element in HTML).pre - This value prevents user agents from collapsing sequences of whitespace. Lines are only broken at newlines in the source, or at occurrences of "\A" in generated content.nowrap - This value collapses whitespace as for 'normal', but suppresses line breaks within text except for those created by "\A" in generated content (e.g., for the BR element in HTML).

```java
public String WhiteSpace { get; set; }
```

### Return Value

white-space property

### See Also

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
