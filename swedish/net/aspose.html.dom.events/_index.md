---
title: Aspose.Html.Dom.Events
second_title: Aspose.HTML för .NET API Referens
description: Den Aspose.Html.Dom.Events namnutrymme tillhandahåller objekt för alla händelserelaterade DOMuppdateringar. Det inkluderar prenumeration på specifik kontextuell informationsobservation associerad med händelsen såväl som anpassad händelsekonstruktion.
type: docs
weight: 80
url: /sv/net/aspose.html.dom.events/
---
Den **Aspose.Html.Dom.Events** namnutrymme tillhandahåller objekt för alla händelserelaterade DOM-uppdateringar. Det inkluderar prenumeration på specifik kontextuell informationsobservation associerad med händelsen såväl som anpassad händelsekonstruktion.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [CustomEvent](./customevent/) | Händelser som använder CustomEvent-gränssnittet kan användas för att överföra anpassade data. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Den[`DocumentLoadErrorEvent`](../aspose.html.dom.events/documentloaderrorevent/) inträffar när den begärda resursen inte är tillgänglig. |
| [DOMEventHandler](./domeventhandler/) | Representerar callback för händelsehantering. |
| [ErrorEvent](./errorevent/) | Den[`ErrorEvent`](../aspose.html.dom.events/errorevent/) ger kontextuell information om ett fel som uppstod under körning. |
| [Event](./event/) | Den[`Event`](../aspose.html.dom.events/event/) används för att tillhandahålla kontextuell information om en händelse till hanteraren som bearbetar händelsen. |
| [FocusEvent](./focusevent/) | FocusEvent-gränssnittet tillhandahåller specifik kontextuell information associerad med Focus-händelser. |
| [InputEvent](./inputevent/) | Indatahändelser skickas som aviseringar när DOM uppdateras. |
| [KeyboardEvent](./keyboardevent/) | KeyboardEvent-gränssnittet tillhandahåller specifik kontextuell information associerad med tangentbordsenheter. Varje tangentbordshändelse refererar till en nyckel som använder ett värde. Tangentbordshändelser är vanligtvis riktade mot det element som har fokus. |
| [MouseEvent](./mouseevent/) | MouseEvent-gränssnittet tillhandahåller specifik kontextuell information associerad med Mouse-händelser. |
| [UIEvent](./uievent/) | UIEvent-gränssnittet tillhandahåller specifik kontextuell information associerad med användargränssnittshändelser. |
| [WheelEvent](./wheelevent/) | WheelEvent-gränssnittet tillhandahåller specifik kontextuell information associerad med hjulhändelser. För att skapa en instans av WheelEvent-gränssnittet använder du WheelEvent-konstruktorn och skickar en valfri WheelEventInit-ordbok. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Den[`IDocumentEvent`](../aspose.html.dom.events/idocumentevent/) gränssnitt tillhandahåller en mekanism genom vilken användaren kan skapa en[`Event`](../aspose.html.dom.events/event/) av en typ som stöds av implementeringen. |
| [IEventListener](./ieventlistener/) | Den[`IEventListener`](../aspose.html.dom.events/ieventlistener/)gränssnittet är den primära metoden för att hantera händelser. Användare implementerar[`IEventListener`](../aspose.html.dom.events/ieventlistener/) gränssnitt och registrera sin lyssnare på en[`EventTarget`](../aspose.html.dom/eventtarget/) använda[`AddEventListener`](../aspose.html.dom/eventtarget/addeventlistener/) method. Användarna bör också ta bort sina[`IEventListener`](../aspose.html.dom.events/ieventlistener/) från dess[`EventTarget`](../aspose.html.dom/eventtarget/) efter att de har slutfört använda lyssnaren. |
| [IEventTarget](./ieventtarget/) | Den[`EventTarget`](../aspose.html.dom/eventtarget/) gränssnitt implementeras av alla noder i en implementering som stöder DOM-händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika castingmetoder på en instans av nodgränssnittet. Gränssnittet tillåter registrering och borttagning av händelseavlyssnare på en[`EventTarget`](../aspose.html.dom/eventtarget/) och sändning av händelser till det[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |


