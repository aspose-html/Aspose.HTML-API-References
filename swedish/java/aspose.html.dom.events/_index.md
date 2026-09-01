---
title: "com.aspose.html.dom.events"
second_title: "Aspose.HTML för Java API-referens"
description: "Paketet com.aspose.html.dom.events tillhandahåller objekt för alla händelser relaterade till DOM‑uppdatering. Det inkluderar prenumeration på specifik kontextuell informationsobservation som är associerad med händelsen samt konstruktion av anpassade händelser."
type: docs

url: /sv/java/com.aspose.html.dom.events/
---
Paketet **com.aspose.html.dom.events** tillhandahåller objekt för alla händelser relaterade till DOM‑uppdateringar. Det inkluderar prenumeration på specifik kontextuell informationsobservation kopplad till händelser samt konstruktion av anpassade händelser.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [CustomEvent](./customevent/) | Händelser som använder CustomEvent‑gränssnittet kan användas för att bära anpassad data. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | DocumentLoadErrorEvent inträffar när den begärda resursen inte är tillgänglig. |
| [DOMEventHandler](./domeventhandler/) | Representerar en generisk återuppringningsdelegat för Document Object Model (DOM)-händelsehantering. |
| [ErrorEvent](./errorevent/) | Den ErrorEvent tillhandahåller kontextuell information om ett fel som inträffade under körning. |
| [Event](./event/) | Den används för att tillhandahålla kontextuell information om en händelse till hanteraren som bearbetar händelsen. |
| [FocusEvent](./focusevent/) | Den FocusEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med Focus‑händelser. |
| [InputEvent](./inputevent/) | Inmatningshändelser skickas som aviseringar när DOM uppdateras. |
| [KeyboardEvent](./keyboardevent/) | Den KeyboardEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med tangentbordsenheter. Varje tangentbords­händelse refererar till en tangent med ett värde. Tangentbords­händelser riktas vanligtvis mot elementet som har fokus. |
| [MouseEvent](./mouseevent/) | Den MouseEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med mus‑händelser. |
| [UIEvent](./uievent/) | Den UIEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med användargränssnittshändelser. |
| [WheelEvent](./wheelevent/) | Den WheelEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med hjulhändelser. För att skapa en instans av WheelEvent‑gränssnittet, använd WheelEvent‑konstruktorn och skicka ett valfritt WheelEventInit‑lexikon. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Den DocumentEvent‑gränssnittet tillhandahåller en mekanism så att användaren kan skapa ett Event av en typ som stöds av implementationen. Det förväntas att DocumentEvent‑gränssnittet implementeras på samma objekt som implementerar Document‑gränssnittet i en implementation som stödjer händelsemodellen. |
| [IEventListener](./ieventlistener/) | Den gränssnittet är den primära metoden för att hantera händelser. Användare implementerar gränssnittet och registrerar sin lyssnare på en med metoden. Användarna bör också ta bort sin från den efter att de har slutfört användningen av lyssnaren. |
| [IEventTarget](./ieventtarget/) | Den EventTarget‑gränssnittet implementeras av alla noder i en implementation som stödjer DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika kastningsmetoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av Event‑lyssnare på en och sändning av händelser till den. |
