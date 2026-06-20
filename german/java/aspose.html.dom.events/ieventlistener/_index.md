---
title: "IEventListener Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.events.IEventListener Schnittstelle. Die Schnittstelle ist die primäre Methode zur Ereignisbehandlung. Benutzer implementieren die Schnittstelle und registrieren ihren Listener mithilfe der Methode. Die Benutzer sollten ihren Listener anschließend entfernen, nachdem sie ihn verwendet haben."
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
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Diese Methode wird aufgerufen, sobald ein Ereignis des Typs eintritt, für den die Schnittstelle registriert wurde. |

## Hinweise

Wenn ein Node mit der cloneNode‑Methode kopiert wird, werden die an den Quell‑Node angehängten Event‑Listener nicht an den kopierten Node angehängt. Wenn der Benutzer dieselben Event‑Listener zum neu erstellten Kopie hinzufügen möchte, muss er sie manuell hinzufügen.

### Siehe auch

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
