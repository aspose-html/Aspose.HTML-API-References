---
title: Interface IWindow
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Window.IWindow gränssnitt. Fönsterobjektet representerar ett fönster som innehåller ett DOMdokument.
type: docs
weight: 5850
url: /sv/net/aspose.html.window/iwindow/
---
## IWindow interface

Fönsterobjektet representerar ett fönster som innehåller ett DOM-dokument.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document/) { get; } | Dokumentattributet måste returnera Window-objektets senaste Document-objekt. |
| [FrameElement](../../aspose.html.window/iwindow/frameelement/) { get; } | FrameElement-objektet för ett dokument. |
| [Location](../../aspose.html.window/iwindow/location/) { get; } | Platsattributet för Window-gränssnittet måste returnera Location-objektet för det Window-objektets Document. |
| [Name](../../aspose.html.window/iwindow/name/) { get; set; } | Namnattributet för Window-objektet måste, när det hämtas, returnera det aktuella namnet på webbläsarkontexten och, vid inställning, ställa in namnet på webbläsarkontexten till det nya värdet. |
| [Opener](../../aspose.html.window/iwindow/opener/) { get; } | Opener IDL-attributet på Window-objektet, när det hämtas, måste returnera WindowProxy-objektet för webbläsarkontexten från vilken den aktuella webbläsarkontexten skapades (dess öppnare webbläsarkontext), om det finns en, om den fortfarande är tillgänglig, och om det aktuella webbläsarsammanhanget har inte förnekat sin öppnare; annars måste den returnera null. Vid inställning, om det nya värdet är null måste den aktuella webbläsarkontexten avvisa dess öppnare; om det nya värdet är något annat måste användaragenten anropa den interna metoden [[DefineOwnProperty]] för Window-objektet och skicka egenskapsnamnet "öppnare" som egenskapsnyckeln och egenskapsbeskrivningen { [[Value]]: värde , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } som egenskapsbeskrivning, där värde är det nya värdet. |
| [Parent](../../aspose.html.window/iwindow/parent/) { get; } | Det överordnade IDL-attributet på Window-objektet för ett dokument i en webbläsarkontext b måste returnera WindowProxy-objektet i den överordnade webbläsarkontexten, om det finns ett (dvs. om b är ett underordnat webbläsarkontext), eller WindowProxy-objektet för webbläsaren själva context b, annars (dvs. om det är en webbläsarkontext på toppnivå eller en fristående kapslad webbläsarkontext). |
| [Self](../../aspose.html.window/iwindow/self/) { get; } | Returnerar Window-objektets webbläsarkontexts WindowProxy-objekt. |
| [Top](../../aspose.html.window/iwindow/top/) { get; } | Det översta IDL-attributet på Window-objektet i ett dokument i en webbläsarkontext b måste returnera WindowProxy-objektet i dess webbläsarkontext på toppnivå (som skulle vara dess eget WindowProxy-objekt om det var ett webbläsarkontext på toppnivå), om den har ett eller ett eget WindowProxy-objekt annars (t.ex. om det var en fristående kapslad webbläsarkontext). |
| [Window](../../aspose.html.window/iwindow/window/) { get; } | Returnerar Window-objektets webbläsarkontexts WindowProxy-objekt. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert/)(string) | Visar en modal varning med det givna meddelandet och väntar på att användaren ska avvisa it |
| [Confirm](../../aspose.html.window/iwindow/confirm/)(string) | Visar en modal OK/Avbryt-prompt med det givna meddelandet, väntar på att användaren ska avvisa det och returnerar sant om användaren klickar på OK och falskt om användaren klickar på Avbryt. |
| [Prompt](../../aspose.html.window/iwindow/prompt/)(string, string) | Visar en modal textfältprompt med det givna meddelandet, väntar på att användaren avvisar det och returnerar värdet som användaren angav. Om användaren avbryter prompten, returneras null istället. Om det andra argumentet finns, används det angivna värdet som standard. |

### Se även

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namnutrymme [Aspose.Html.Window](../../aspose.html.window/)
* hopsättning [Aspose.HTML](../../)


