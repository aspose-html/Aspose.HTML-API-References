---
title: "IEventListener Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.events.IEventListener interface. Die Schnittstelle ist die primäre Methode zur Behandlung von Ereignissen. Benutzer implementieren die Schnittstelle und registrieren ihren Listener mithilfe der Methode. Die Benutzer sollten ihn auch entfernen, nachdem sie die Verwendung des Listeners abgeschlossen haben."
type: docs

url: /de/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Das Interface ist die primäre Methode zur Ereignisbehandlung. Benutzer implementieren das Interface und registrieren ihren Listener mithilfe der Methode. Die Benutzer sollten ihren Listener nach Abschluss der Nutzung wieder entfernen.

```java
public interface IEventListener
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Diese Methode wird aufgerufen, wann immer ein Ereignis des Typs auftritt, für den die Schnittstelle registriert wurde. |

## Hinweise

Wenn ein Node mit der cloneNode-Methode kopiert wird, werden die an den Quell-Node angehängten Event Listener nicht an den kopierten Node angehängt. Wenn der Benutzer möchte, dass dieselben Event Listener zum neu erstellten Kopie hinzugefügt werden, muss er sie manuell hinzufügen.

### Siehe auch

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
