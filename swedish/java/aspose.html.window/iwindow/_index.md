---
title: "IWindow-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.window.IWindow gränssnitt. Window-objektet representerar ett fönster som innehåller ett DOM-dokument"
type: docs

url: /sv/java/com.aspose.html.window/iwindow/
---
## IWindow interface

window-objektet representerar ett fönster som innehåller ett DOM-dokument.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) Dokumentattributet måste returnera Window-objektets senaste Document-objekt. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) frameElement-objektet för ett Document. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Returnerar ett Storage-objekt som låter dig spara nyckel/värde-par i användaragenten. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) location-attributet för Window-gränssnittet måste returnera Location-objektet för det Window-objektets Document. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) opener-IDL-attributet på Window-objektet, vid läsning, måste returnera WindowProxy-objektet för den surfkontext som den aktuella surfkontexten skapades från (dess öppnare surfkontext), om det finns en, om den fortfarande är tillgänglig, och om den aktuella surfkontexten inte har avstått sin öppnare; annars måste den returnera null. Vid skrivning, om det nya värdet är null ska den aktuella surfkontexten avstå sin öppnare; om det nya värdet är något annat ska användaragenten anropa den interna metoden [[DefineOwnProperty]] på Window-objektet, med egenskapsnamnet "opener" som nyckel, och Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } som egenskapsbeskrivning, där value är det nya värdet. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) parent-IDL-attributet på Window-objektet för ett Document i en surfkontext b måste returnera WindowProxy-objektet för den överordnade surfkontexten, om det finns en (dvs. om b är en barn-surfkontext), eller WindowProxy-objektet för surfkontexten b själv, annars (dvs. om det är en toppnivå-surfkontext eller en fristående nästlad surfkontext). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Returnerar Window-objektets surfkontexts WindowProxy-objekt. |
| [getTop](../../com.aspose.html.window/iwindow/top/) top-IDL-attributet på Window-objektet för ett Document i en surfkontext b måste returnera WindowProxy-objektet för dess toppnivå-surfkontext (vilket skulle vara dess eget WindowProxy-objekt om det var en toppnivå-surfkontext), om det har en, eller dess eget WindowProxy-objekt annars (t.ex. om det var en fristående nästlad surfkontext). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Returnerar Window-objektets surfkontexts WindowProxy-objekt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Visar en modal varningsruta med det angivna meddelandet och väntar på att användaren avfärdar den. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Tar emot indata i form av en Unicode-sträng som innehåller base64-kodad binär data, avkodar den och returnerar en sträng bestående av tecken i intervallet U+0000 till U+00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, motsvarande den binära datan. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Tar emot indata i form av en Unicode-sträng som endast innehåller tecken i intervallet U+0000 till U+00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, och konverterar den till dess base64-representation, som den returnerar. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Visar en modal OK/Avbryt-prompt med det angivna meddelandet, väntar på att användaren avfärdar den och returnerar true om användaren klickar på OK och false om användaren klickar på Avbryt. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Returnerar ett nytt MediaQueryList-objekt som sedan kan användas för att avgöra om dokumentet matchar media query-strängen, samt för att övervaka dokumentet för att upptäcka när det matchar (eller slutar matcha) den media queryn. Se CSSOM View Module-specifikationen: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Visar en modal textruta-prompt med det angivna meddelandet, väntar på att användaren avfärdar den och returnerar det värde som användaren skrev in. Om användaren avbryter prompten returneras null istället. Om det andra argumentet finns, används det angivna värdet som standard. |

### Se även

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
