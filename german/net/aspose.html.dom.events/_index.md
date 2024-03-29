---
title: Aspose.Html.Dom.Events
second_title: Aspose.HTML für .NET-API-Referenz
description: Die Aspose.Html.Dom.Events Namespace bietet Objekte für alle Ereignisse im Zusammenhang mit der DOMAktualisierung. Es umfasst das Abonnement für spezifische kontextbezogene Informationsbeobachtungen  die mit Ereignissen verbunden sind sowie die Erstellung benutzerdefinierter Ereignisse.
type: docs
weight: 80
url: /de/net/aspose.html.dom.events/
---
Die **Aspose.Html.Dom.Events** Namespace bietet Objekte für alle Ereignisse im Zusammenhang mit der DOM-Aktualisierung. Es umfasst das Abonnement für spezifische kontextbezogene Informationsbeobachtungen , die mit Ereignissen verbunden sind, sowie die Erstellung benutzerdefinierter Ereignisse.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [CustomEvent](./customevent/) | Ereignisse, die die CustomEvent-Schnittstelle verwenden, können verwendet werden, um benutzerdefinierte Daten zu übertragen. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | Die[`DocumentLoadErrorEvent`](../aspose.html.dom.events/documentloaderrorevent/) tritt auf, wenn die angeforderte Ressource nicht verfügbar ist. |
| [DOMEventHandler](./domeventhandler/) | Stellt den Rückruf für die Ereignisbehandlung dar. |
| [ErrorEvent](./errorevent/) | Die[`ErrorEvent`](../aspose.html.dom.events/errorevent/) liefert kontextbezogene Informationen zu Fehlern, die während der Laufzeit aufgetreten sind. |
| [Event](./event/) | Die[`Event`](../aspose.html.dom.events/event/) wird verwendet, um dem Handler, der das Ereignis verarbeitet, Kontextinformationen zu einem Ereignis bereitzustellen. |
| [FocusEvent](./focusevent/) | Die FocusEvent-Schnittstelle bietet spezifische kontextbezogene Informationen zu Focus-Ereignissen. |
| [InputEvent](./inputevent/) | Eingabeereignisse werden als Benachrichtigungen gesendet, wenn das DOM aktualisiert wird. |
| [KeyboardEvent](./keyboardevent/) | Die KeyboardEvent-Schnittstelle stellt spezifische Kontextinformationen bereit, die Tastaturgeräten zugeordnet sind. Jedes Tastaturereignis verweist mit einem Wert auf eine Taste. Tastaturereignisse werden normalerweise an das Element gerichtet, das den Fokus hat. |
| [MouseEvent](./mouseevent/) | Die MouseEvent-Schnittstelle stellt spezifische Kontextinformationen zu Mausereignissen bereit. |
| [UIEvent](./uievent/) | Die UIEvent-Schnittstelle stellt spezifische Kontextinformationen bereit, die mit Ereignissen der Benutzeroberfläche verknüpft sind. |
| [WheelEvent](./wheelevent/) | Die WheelEvent-Schnittstelle stellt spezifische Kontextinformationen bereit, die Radereignissen zugeordnet sind. Um eine Instanz der WheelEvent-Schnittstelle zu erstellen, verwenden Sie den WheelEvent-Konstruktor und übergeben ein optionales WheelEventInit-Wörterbuch. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Die[`IDocumentEvent`](../aspose.html.dom.events/idocumentevent/) Schnittstelle bietet einen Mechanismus, mit dem der Benutzer eine erstellen kann[`Event`](../aspose.html.dom.events/event/) eines Typs, der von der Implementierung unterstützt wird. |
| [IEventListener](./ieventlistener/) | Die[`IEventListener`](../aspose.html.dom.events/ieventlistener/)Schnittstelle ist die primäre Methode zur Behandlung von Ereignissen. Benutzer implementieren die[`IEventListener`](../aspose.html.dom.events/ieventlistener/) Schnittstelle und registrieren Sie ihren Listener auf einer[`EventTarget`](../aspose.html.dom/eventtarget/) Verwendung der[`AddEventListener`](../aspose.html.dom/eventtarget/addeventlistener/) method. Die Benutzer sollten auch ihre entfernen[`IEventListener`](../aspose.html.dom.events/ieventlistener/) von seinem[`EventTarget`](../aspose.html.dom/eventtarget/) nachdem sie die Verwendung des Listeners abgeschlossen haben. |
| [IEventTarget](./ieventtarget/) | Die[`EventTarget`](../aspose.html.dom/eventtarget/) -Schnittstelle wird von allen Knoten in einer Implementierung implementiert, die das DOM-Ereignismodell unterstützt. Daher kann diese Schnittstelle durch Verwendung bindungsspezifischer Casting-Methoden auf einer Instanz der Knotenschnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von Ereignis-Listenern ein[`EventTarget`](../aspose.html.dom/eventtarget/) und Versand von Ereignissen dazu[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |


