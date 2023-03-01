---
title: Class KeyboardEvent
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Events.KeyboardEvent klass. KeyboardEventgränssnittet tillhandahåller specifik kontextuell information associerad med tangentbordsenheter. Varje tangentbordshändelse refererar till en nyckel som använder ett värde. Tangentbordshändelser är vanligtvis riktade mot det element som har fokus.
type: docs
weight: 830
url: /sv/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent-gränssnittet tillhandahåller specifik kontextuell information associerad med tangentbordsenheter. Varje tangentbordshändelse refererar till en nyckel som använder ett värde. Tangentbordshändelser är vanligtvis riktade mot det element som har fokus.

```csharp
public class KeyboardEvent : UIEvent
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | Initierar en ny instans av`KeyboardEvent` class. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initierar en ny instans av`KeyboardEvent` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | true om tangenten Alt (alternativ) (eller "Alternativ") var aktiv. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Används för att indikera om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet sant, annars är värdet false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Används för att indikera om en händelse kan förhindras eller inte. Om standardåtgärden kan förhindras är värdet sant, annars är värdet false. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | Koden innehåller en sträng som identifierar den fysiska nyckel som trycks ned. Värdet påverkas inte av den aktuella tangentbordslayouten eller modifieringsläget, så en viss tangent kommer alltid att returnera samma värde. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | true om kontroll- (kontroll)-nyckelmodifieraren var aktiv. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Används för att indikera[`IEventTarget`](../ieventtarget/) vars[`IEventListener`](../ieventlistener/) s bearbetas för närvarande. Detta är särskilt användbart under fångst och bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan det annullerbara attributvärdet är sant, och annars false. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Anger viss detaljinformation om händelsen, beroende på typen av händelse. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Används för att indikera vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | true om nyckelhändelsen inträffar som en del av en kompositionssession, dvs efter en kompositionsstarthändelse och före motsvarande kompositionssluthändelse. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera värdet som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | Tangenten håller nyckelvärdet för den nedtryckta tangenten. Om värdet har en utskriven representation MÅSTE det vara en icke-tom Unicode-teckensträng som överensstämmer med algoritmen för att bestämma nyckelvärdet som definieras i denna specifikation. Om värdet är en kontrollnyckel som inte har någon utskriven representation, MÅSTE det vara ett av nyckelvärdena som definieras i nyckelvärdena som bestäms av algoritmen för att bestämma nyckelvärdet. Implementeringar som inte kan identifiera en nyckel MÅSTE använda nyckelvärdet Unidentified. |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | Platsattributet innehåller en indikation på den logiska platsen för nyckeln på enheten. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | true om meta (Meta)-nyckelmodifieraren var aktiv. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | sant om tangenten har tryckts in på ett ihållande sätt. Att hålla nere en tangent MÅSTE resultera i att händelsernas tangentnedtryckning upprepas, före inmatning, inmatning i denna ordning, med en hastighet som bestäms av systemkonfigurationen. För mobila enheter som har långa tangenttryckningar, MÅSTE den första tangenthändelsen med ett upprepningsattributvärde på sant fungera som en indikation på en lång tangenttryckning. Hur lång tid som knappen MÅSTE tryckas ned för att börja upprepa är konfigurationsberoende. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | true om skift- (Shift)-tangentens modifierare var aktiv. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Används för att indikera[`IEventTarget`](../ieventtarget/) som händelsen ursprungligen skickades till. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Används för att ange tidpunkten (i millisekunder i förhållande till epok) då händelsen skapades. På grund av det faktum att vissa system kanske inte tillhandahåller denna information, kanske värdet av timeStamp inte är tillgängligt för alla händelser. När inte tillgängligt , kommer ett värde på 0 att returneras. Exempel på epoktid är tidpunkten för systemets start eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägeskänsligt). Namnet måste vara ett XML-namn. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | View-attributet identifierar fönstret från vilket händelsen genererades. Det oinitierade värdet för detta attribut MÅSTE vara null. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Den[`InitEvent`](../event/initevent/) metod används för att initiera värdet av en[`Event`](../event/) skapad genom [`IDocumentEvent`](../idocumentevent/) gränssnitt. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas,[`PreventDefault`](../event/preventdefault/) metod används för att indikera att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt vidtas av implementeringen som ett resultat av händelsen inte kommer att inträffa. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar händelsen från att nå alla händelseavlyssnare som är registrerade efter den aktuella och när den skickas i ett träd förhindras även händelsen från att nå andra objekt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Den[`StopPropagation`](../event/stoppropagation/) metod används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Den aktiverade nyckeln kom från den vänstra nyckelplatsen (när det finns mer än en möjlig plats för denna nyckel). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Tangentaktiveringen har sitt ursprung på det numeriska tangentbordet eller med en virtuell tangent som motsvarar det numeriska tangentbordet (när det finns mer än en möjlig plats för denna tangent). Observera att NumLock-nyckeln alltid ska kodas med platsen DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Nyckelaktiveringen kom från rätt nyckelplats (när det finns mer än en möjlig plats för denna nyckel). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Nyckelaktiveringen FÅR INTE särskiljas som den vänstra eller högra versionen av nyckeln och (förutom NumLock-tangenten) härrörde inte från det numeriska tangentbordet (eller härrörde inte från en virtuell tangent som motsvarar det numeriska tangentbordet). |

### Se även

* class [UIEvent](../uievent/)
* namnutrymme [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* hopsättning [Aspose.HTML](../../)


