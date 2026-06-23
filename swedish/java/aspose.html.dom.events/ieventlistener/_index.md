---
title: "IEventListener gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.IEventListener gränssnitt. Gränssnittet är den primära metoden för att hantera händelser. Användare implementerar gränssnittet och registrerar sin lyssnare med hjälp av metoden. Användarna bör också ta bort sin lyssnare från den efter att de har avslutat användningen av lyssnaren."
type: docs

url: /sv/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Den gränssnittet är den primära metoden för att hantera händelser. Användare implementerar gränssnittet och registrerar sin lyssnare på en med metoden. Användarna bör också ta bort sin från den efter att de har slutfört användningen av lyssnaren.

```java
public interface IEventListener
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Denna metod kallas närhelst en händelse av den typ som gränssnittet registrerades för inträffar. |

## Anmärkningar

När en Node kopieras med metoden cloneNode är de Event Listeners som är kopplade till käll‑Node inte kopplade till den kopierade Node. Om användaren vill att samma Event Listeners ska läggas till i den nyskapade kopian måste användaren lägga till dem manuellt.

### Se även

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
