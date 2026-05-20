---
title: "IEventListener Gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.IEventListener gränssnitt. Gränssnittet är den primära metoden för att hantera händelser. Användare implementerar gränssnittet och registrerar sin lyssnare med hjälp av metoden. Användarna bör också ta bort sina lyssnare från den efter att de har slutfört användningen av lyssnaren"
type: docs

url: /sv/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Gränssnittet är den primära metoden för att hantera händelser. Användare implementerar gränssnittet och registrerar sin lyssnare på ett objekt med metoden. Användarna bör också ta bort sin lyssnare efter att de har slutfört användningen av lyssnaren.

```java
public interface IEventListener
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Denna metod kallas när en händelse av den typ som gränssnittet registrerades för inträffar. |

## Anmärkningar

När en Nod kopieras med metoden cloneNode är Event Listeners som är fästa vid källnoden inte fästa vid den kopierade noden. Om användaren vill att samma Event Listeners ska läggas till i den nysskapade kopian måste användaren lägga till dem manuellt.

### Se även

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
