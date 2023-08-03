---
title: SVGSVGElement.SetCurrentTime
second_title: Aspose.HTML for Java API Reference
description: SVGSVGElement method. Adjusts the clock for this SVG document fragment establishing a new current time. If setCurrentTime is called before the document timeline has begun for example by script running in a script element before the documents SVGLoad event is dispatched then the value of seconds in the last invocation of the method gives the time that the document will seek to once the document timeline has begun
type: docs
weight: 230
url: /net/com.aspose.html.dom.svg/svgsvgelement/setcurrenttime/
---
## SVGSVGElement.SetCurrentTime method

Adjusts the clock for this SVG document fragment, establishing a new current time. If setCurrentTime is called before the document timeline has begun (for example, by script running in a ‘script’ element before the document's SVGLoad event is dispatched), then the value of seconds in the last invocation of the method gives the time that the document will seek to once the document timeline has begun.

```java
public void SetCurrentTime(float seconds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| seconds | Single | The new current time in seconds relative to the start time for the current SVG document fragment. |

### See Also

* class [SVGSVGElement](../)
* package [com.aspose.html.Dom.Svg](../../svgsvgelement/)
* package [Aspose.HTML](../../../)
