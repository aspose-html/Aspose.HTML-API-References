---
title: IWindow.Opener
second_title: Aspose.HTML för .NET API Referens
description: IWindow fast egendom. Opener IDLattributet på Windowobjektet när det hämtas måste returnera WindowProxyobjektet för webbläsarkontexten från vilken den aktuella webbläsarkontexten skapades dess öppnare webbläsarkontext om det finns en om den fortfarande är tillgänglig och om det aktuella webbläsarsammanhanget har inte förnekat sin öppnare annars måste den returnera null. Vid inställning om det nya värdet är null måste den aktuella webbläsarkontexten avvisa dess öppnare om det nya värdet är något annat måste användaragenten anropa den interna metoden DefineOwnProperty för Windowobjektet och skicka egenskapsnamnet öppnare som egenskapsnyckeln och egenskapsbeskrivningen  Value värde  Writable true Enumerable true Configurable true  som egenskapsbeskrivning där värde är det nya värdet.
type: docs
weight: 50
url: /sv/net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Opener IDL-attributet på Window-objektet, när det hämtas, måste returnera WindowProxy-objektet för webbläsarkontexten från vilken den aktuella webbläsarkontexten skapades (dess öppnare webbläsarkontext), om det finns en, om den fortfarande är tillgänglig, och om det aktuella webbläsarsammanhanget har inte förnekat sin öppnare; annars måste den returnera null. Vid inställning, om det nya värdet är null måste den aktuella webbläsarkontexten avvisa dess öppnare; om det nya värdet är något annat måste användaragenten anropa den interna metoden [[DefineOwnProperty]] för Window-objektet och skicka egenskapsnamnet "öppnare" som egenskapsnyckeln och egenskapsbeskrivningen { [[Value]]: värde , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } som egenskapsbeskrivning, där värde är det nya värdet.

```csharp
public IWindow Opener { get; }
```

### Fastighetsvärde

Öppnaren.

### Se även

* interface [IWindow](../)
* namnutrymme [Aspose.Html.Window](../../iwindow/)
* hopsättning [Aspose.HTML](../../../)


