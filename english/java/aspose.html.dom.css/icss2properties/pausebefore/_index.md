---
title: ICSS2Properties.PauseBefore
second_title: Aspose.HTML for Java API Reference
description: ICSS2Properties property. These properties specify a pause to be observed before or after speaking an elements content. Values have the following meanings
type: docs
weight: 910
url: /java/com.aspose.html.dom.css/icss2properties/pausebefore/
---
## ICSS2Properties.PauseBefore property

These properties specify a pause to be observed before (or after) speaking an element's content. Values have the following meanings:

'[time](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-time)' - Expresses the pause in absolute time units (seconds and milliseconds).'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Refers to the inverse of the value of the ['speech-rate'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-speech-rate) property. For example, if the speech-rate is 120 words per minute (i.e., a word takes half a second, or 500ms) then a ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) of 100% means a pause of 500 ms and a ['pause-before'](https://www.w3.org/TR/1998/REC-CSS2-19980512/aural.html#propdef-pause-before) of 20% means 100ms.

```java
public String PauseBefore { get; set; }
```

### Return Value

pause-before property

### See Also

* interface [ICSS2Properties](../)
* package [com.aspose.html.Dom.Css](../../icss2properties/)
* package [Aspose.HTML](../../../)
