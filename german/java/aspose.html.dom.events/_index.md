---
title: "com.aspose.html.dom.events"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Das Paket com.aspose.html.dom.events stellt Objekte für alle DOM‑Aktualisierungsereignisse bereit. Es umfasst die Abonnierung spezifischer kontextueller Informationsbeobachtungen, die mit dem Ereignis verbunden sind, sowie die Erstellung benutzerdefinierter Ereignisse."
type: docs

url: /de/java/com.aspose.html.dom.events/
---
Das **com.aspose.html.dom.events**-Paket stellt Objekte für alle DOM‑Aktualisierungs‑Ereignisse bereit. Es umfasst die Abonnierung von spezifischen kontextbezogenen Informationsbeobachtungen, die mit einem Ereignis verknüpft sind, sowie die Erstellung benutzerdefinierter Ereignisse.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [CustomEvent](./customevent/) | Ereignisse, die das CustomEvent-Interface verwenden, können zum Übertragen benutzerdefinierter Daten genutzt werden. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Das DocumentLoadErrorEvent tritt auf, wenn die angeforderte Ressource nicht verfügbar ist. |
| [DOMEventHandler](./domeventhandler/) | Stellt einen generischen Callback‑Delegate für die Behandlung von Document Object Model (DOM)-Ereignissen dar. |
| [ErrorEvent](./errorevent/) | Das ErrorEvent liefert kontextbezogene Informationen über einen Fehler, der zur Laufzeit aufgetreten ist. |
| [Event](./event/) | Das wird verwendet, um kontextbezogene Informationen über ein Ereignis an den Handler zu liefern, der das Ereignis verarbeitet. |
| [FocusEvent](./focusevent/) | Das FocusEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Fokusereignissen verbunden sind. |
| [InputEvent](./inputevent/) | Eingabeereignisse werden als Benachrichtigungen gesendet, wann immer das DOM aktualisiert wird. |
| [KeyboardEvent](./keyboardevent/) | Das KeyboardEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Tastaturgeräten verbunden sind. Jedes Keyboard-Ereignis verweist über einen Wert auf eine Taste. Keyboard-Ereignisse werden in der Regel an das Element gerichtet, das den Fokus hat. |
| [MouseEvent](./mouseevent/) | Das MouseEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Mausereignissen verbunden sind. |
| [UIEvent](./uievent/) | Das UIEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Benutzeroberflächenereignissen verbunden sind. |
| [WheelEvent](./wheelevent/) | Das WheelEvent-Interface liefert spezifische kontextbezogene Informationen, die mit Radereignissen verbunden sind. Um eine Instanz des WheelEvent-Interface zu erstellen, verwenden Sie den WheelEvent-Konstruktor und übergeben ein optionales WheelEventInit-Wörterbuch. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Das DocumentEvent-Interface bietet einen Mechanismus, mit dem der Benutzer ein Ereignis eines von der Implementierung unterstützten Typs erstellen kann. Es wird erwartet, dass das DocumentEvent-Interface auf demselben Objekt implementiert wird, das das Document-Interface in einer Implementierung, die das Ereignismodell unterstützt, implementiert. |
| [IEventListener](./ieventlistener/) | Das Interface ist die primäre Methode zur Ereignisbehandlung. Benutzer implementieren das Interface und registrieren ihren Listener mithilfe der Methode. Die Benutzer sollten ihren Listener nach Abschluss der Nutzung wieder entfernen. |
| [IEventTarget](./ieventtarget/) | Das EventTarget-Interface wird von allen Nodes in einer Implementierung, die das DOM-Ereignismodell unterstützt, implementiert. Daher kann dieses Interface durch bindungsspezifische Cast-Methoden auf einer Instanz des Node-Interfaces erhalten werden. Das Interface ermöglicht die Registrierung und Entfernung von Event-Listenern sowie das Senden von Ereignissen an diese. |
