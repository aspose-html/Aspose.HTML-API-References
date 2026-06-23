---
title: "IWindow.Opener"
second_title: "Aspose.HTML för Java API-referens"
description: "IWindow egenskap. Opener-IDL-attributet på Window-objektet vid läsning måste returnera WindowProxy-objektet för den bläddringskontext från vilken den aktuella bläddringskontexten skapades (dess opener-bläddringskontext) om det finns en, om den fortfarande är tillgänglig och om den aktuella bläddringskontexten inte har avstått sin opener; annars måste den returnera null. Vid skrivning, om det nya värdet är null måste den aktuella bläddringskontexten avstå sin opener; om det nya värdet är något annat måste användaragenten anropa den interna metoden [[DefineOwnProperty]] på Window-objektet och skicka egenskapsnamnet \"opener\" som nyckel samt egenskapsbeskrivaren { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } där value är det nya värdet."
type: docs

url: /sv/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Opener-IDL-attributet på Window-objektet, vid läsning, måste returnera WindowProxy-objektet för den bläddringskontext från vilken den aktuella bläddringskontexten skapades (dess opener-bläddringskontext), om det finns en, om den fortfarande är tillgänglig och om den aktuella bläddringskontexten inte har avstått sin opener; annars måste den returnera null. Vid skrivning, om det nya värdet är null måste den aktuella bläddringskontexten avstå sin opener; om det nya värdet är något annat måste användaragenten anropa den interna metoden [[DefineOwnProperty]] på Window-objektet, skicka egenskapsnamnet "opener" som nyckel och egenskapsbeskrivaren { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } som egenskapsbeskrivare, där value är det nya värdet.

```java
public IWindow Opener { get; }
```

### Property Value

Openern.

### Se även

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
