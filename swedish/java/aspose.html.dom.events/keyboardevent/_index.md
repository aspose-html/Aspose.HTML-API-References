---
title: "KeyboardEvent-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.KeyboardEvent-klass. KeyboardEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med tangentbordsenheter. Varje tangentbordshändelse refererar till en tangent med ett värde. Tangentbordshändelser riktas vanligtvis mot det element som har fokus."
type: docs

url: /sv/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

Den KeyboardEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med tangentbordsenheter. Varje tangentbords­händelse refererar till en tangent med ett värde. Tangentbords­händelser riktas vanligtvis mot elementet som har fokus.

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
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true om Alt‑tangent (alternativ) (eller "Option")‑modifieraren var aktiv. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Används för att ange om ett händelse är ett bubblande händelse. Om händelsen kan bubbla är värdet sant, annars falskt. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Används för att ange om en händelse kan ha sin standardåtgärd förhindrad. Om standardåtgärden kan förhindras är värdet sant, annars falskt. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) Koden innehåller en sträng som identifierar den fysiska tangent som trycks ned. Värdet påverkas inte av det aktuella tangentbordslayouten eller modifierartillståndet, så en viss tangent kommer alltid att returnera samma värde. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true om Control‑tangent (control)‑modifieraren var aktiv. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returnerar sant om preventDefault() anropades medan det avbrytbara attributets värde är sant, annars falskt. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Anger viss detaljerad information om händelsen, beroende på händelsetypen. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true om tangentborde­händelsen inträffar som en del av en kompositionssession, d.v.s. efter en compositionstart‑händelse och före motsvarande compositionend‑händelse. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Attributet isTrusted måste returnera det värde som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) Nyckeln innehåller nyckelvärdet för den tryckta tangenten. Om värdet har en utskriven representation MÅSTE det vara en icke‑tom Unicode‑teckensträng som följer algoritmen för att bestämma nyckelvärdet som definieras i denna specifikation. Om värdet är en kontrolltangent utan utskriven representation MÅSTE det vara ett av nyckelvärdena som definieras i nyckelvärdesuppsättningen, enligt algoritmen för att bestämma nyckelvärdet. Implementationer som inte kan identifiera en tangent MÅSTE använda nyckelvärdet Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) Platsattributet innehåller en indikation på den logiska placeringen av tangenten på enheten. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true om meta‑tangent (Meta)‑modifieraren var aktiv. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true om tangenten har hållits ned under en längre tid. Att hålla ner en tangent MÅSTE resultera i att händelserna keydown, beforeinput, input upprepas i den ordningen, med en hastighet som bestäms av systemkonfigurationen. För mobila enheter som har lång‑tangenttryck‑beteende måste den första tangent‑händelsen med repeat‑attributvärdet true fungera som en indikation på ett långtangenttryck. Den tid som tangenten MÅSTE hållas ned för att börja upprepa beror på konfigurationen. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true om shift‑tangent (Shift)‑modifieraren var aktiv. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Används för att ange [`IEventTarget`](../ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Används för att ange tiden (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML-namn. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view‑attributet identifierar det fönster från vilket händelsen genererades. Det oinitierade värdet för detta attribut MÅSTE vara null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metoden [`InitEvent`](../event/initevent/) används för att initiera värdet för ett [`Event`](../event/) som skapats via [`IDocumentEvent`](../idocumentevent/)‑gränssnittet. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas används metoden [`PreventDefault`](../event/preventdefault/) för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementeringen som ett resultat av händelsen inte kommer att ske. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att händelsen når några händelselyssnare som registrerats efter den aktuella och när den skickas i ett träd förhindrar den även att händelsen når andra objekt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../event/stoppropagation/) används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | Den aktiverade tangenten härstammar från den vänstra tangentplatsen (när det finns mer än en möjlig plats för denna tangent). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | Tangentaktiveringen härstammar från det numeriska tangentbordet eller med en virtuell tangent som motsvarar det numeriska tangentbordet (när det finns mer än en möjlig plats för denna tangent). Observera att NumLock-tangenten alltid bör kodas med en plats av DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | Tangentaktiveringen härstammar från den högra tangentplatsen (när det finns mer än en möjlig plats för denna tangent). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | Tangentaktiveringen FÅR INTE särskiljas som den vänstra eller högra versionen av tangenten, och (förutom NumLock-tangenten) härstammade inte från det numeriska tangentbordet (eller från en virtuell tangent som motsvarar det numeriska tangentbordet). |

### Se även

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
