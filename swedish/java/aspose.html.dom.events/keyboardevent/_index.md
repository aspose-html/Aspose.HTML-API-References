---
title: "KeyboardEvent-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.KeyboardEvent-klass. KeyboardEvent‑gränssnittet tillhandahåller specifik kontextuell information som är kopplad till tangentbordsenheter. Varje tangentbordshändelse refererar till en tangent med ett värde. Tangentbordshändelser riktas vanligtvis mot elementet som har fokus."
type: docs

url: /sv/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med tangentbordsenheter. Varje tangentbordshändelse refererar till en tangent med ett värde. Tangentbordshändelser riktas vanligtvis mot det element som har fokus.

```java
public class KeyboardEvent : UIEvent
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Initierar en ny instans av klassen `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) Sant om Alt‑tangenten (alternativ) (eller "Option") var aktiv. Det oinitierade värdet för detta attribut MÅSTE vara falskt. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Används för att ange om ett evenemang är ett bubblande evenemang eller inte. Om evenemanget kan bubbla är värdet sant, annars är värdet falskt. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Används för att ange om ett evenemang kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet sant, annars falskt. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) Koden innehåller en sträng som identifierar den fysiska tangent som trycks ned. Värdet påverkas inte av det aktuella tangentbordslayouten eller modifierartillståndet, så en viss tangent kommer alltid att returnera samma värde. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) Sant om Control‑tangenten (control) var aktiv. Det oinitierade värdet för detta attribut MÅSTE vara falskt. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returnerar sant om preventDefault() anropades medan attributet cancelable är sant, annars falskt. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Anger viss detaljerad information om händelsen, beroende på händelsetyp. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) Sant om tangentbords‑händelsen inträffar som en del av en sammansättningssession, d.v.s. efter en compositionstart‑händelse och före motsvarande compositionend‑händelse. Det oinitierade värdet för detta attribut MÅSTE vara falskt. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Attributet isTrusted måste returnera det värde som det initierades med. När ett händelseobjekt skapas måste attributet initieras till false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) Nyckeln innehåller det tangentvärde som trycktes. Om värdet har en utskriven representation MÅSTE det vara en icke‑tom Unicode‑teckensträng som följer algoritmen för att bestämma tangentvärdet som definieras i denna specifikation. Om värdet är en kontrolltangent utan utskriven representation MÅSTE det vara ett av de tangentvärden som definieras i tangentvärdesuppsättningen, enligt algoritmen för att bestämma tangentvärdet. Implementationer som inte kan identifiera en tangent MÅSTE använda tangentvärdet Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) Plats‑attributet innehåller en indikation på den logiska placeringen av tangenten på enheten. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) Sant om meta‑tangenten (Meta) var aktiv. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) Sant om tangenten har tryckts ned på ett ihållande sätt. Att hålla ner en tangent MÅSTE leda till att händelserna keydown, beforeinput, input upprepas i den ordningen, med en hastighet som bestäms av systemkonfigurationen. För mobila enheter som har långtryckningsbeteende måste den första tangent‑händelsen med repeat‑attributvärdet sant fungera som en indikation på ett långtryck. Den tid som tangenten MÅSTE hållas ned för att börja upprepa är konfigurationsberoende. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) Sant om shift‑tangenten (Shift) var aktiv. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Används för att ange [`IEventTarget`](../ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Används för att ange tidpunkten (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML-namn. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) View‑attributet identifierar det fönster från vilket händelsen genererades. Det oinitierade värdet för detta attribut MÅSTE vara null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metoden [`InitEvent`](../event/initevent/) används för att initiera värdet för en [`Event`](../event/) som skapats genom [`IDocumentEvent`](../idocumentevent/)-gränssnittet. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas används [`PreventDefault`](../event/preventdefault/)-metoden för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att händelsen når några händelselyssnare som registrerats efter den aktuella och, när den sänds i ett träd, förhindrar även att händelsen når andra objekt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../event/stoppropagation/) används för att förhindra vidare spridning av en händelse under händelseflödet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Den aktiverade tangenten härstammar från den vänstra tangentplatsen (när det finns mer än en möjlig plats för denna tangent). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Nyckelaktiveringen härstammar från det numeriska tangentbordet eller med en virtuell tangent motsvarande det numeriska tangentbordet (när det finns mer än en möjlig plats för denna tangent). Observera att NumLock-tangenten alltid bör kodas med en plats av DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Nyckelaktiveringen härstammar från den högra tangentplatsen (när det finns mer än en möjlig plats för denna tangent). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Nyckelaktiveringen FÅR INTE särskiljas som den vänstra eller högra versionen av tangenten, och (förutom NumLock-tangenten) härstammade inte från det numeriska tangentbordet (eller härstammade inte med en virtuell tangent motsvarande det numeriska tangentbordet). |

### Se även

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
