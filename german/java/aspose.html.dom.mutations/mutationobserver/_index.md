---
title: "MutationObserver Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.mutations.MutationObserver class. Ein Objekt kann verwendet werden, um Mutationen am Baum von"
type: docs

url: /de/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Ein Objekt kann verwendet werden, um Mutationen am Baum von [`.`](../../com.aspose.html.dom/node/) zu beobachten.

```java
public class MutationObserver : DOMObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Konstruiert ein MutationObserver‑Objekt und setzt dessen [`MutationCallback`](../mutationcallback/) als Rückruf. Der Rückruf wird mit einer Liste von MutationRecord‑Objekten als erstem Argument und dem konstruierten MutationObserver‑Objekt als zweitem Argument aufgerufen. Er wird aufgerufen, nachdem Knoten, die mit der !:Observe(Node, IMutationObserverInit)-Methode registriert wurden, mutiert wurden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Stoppt den Beobachter daran, irgendwelche Mutationen zu beobachten. Bis die observe()-Methode erneut verwendet wird, wird der Rückruf des Beobachters nicht aufgerufen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Weist den User-Agent an, ein angegebenes Ziel (einen Knoten) zu beobachten und alle Mutationen basierend auf den durch Optionen (ein Objekt) vorgegebenen Kriterien zu melden. Das Optionsargument ermöglicht das Festlegen von Beobachtungsoptionen für Mutationen über Objektmitglieder. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Weist den User-Agent an, ein angegebenes Ziel (einen Knoten) zu beobachten und alle Mutationen basierend auf den durch Optionen (ein Objekt) vorgegebenen Kriterien zu melden. Das Optionsargument ermöglicht das Festlegen von Beobachtungsoptionen für Mutationen über Objektmitglieder. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | Die Methode gibt eine Kopie der Aufzeichnungswarteschlange zurück und leert anschließend die Aufzeichnungswarteschlange. |

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
