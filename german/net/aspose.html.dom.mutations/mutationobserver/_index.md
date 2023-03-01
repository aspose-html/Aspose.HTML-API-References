---
title: Class MutationObserver
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Mutations.MutationObserver klas. AMutationObserver Objekt kann verwendet werden um Mutationen im Baum von zu beobachtenNode .
type: docs
weight: 970
url: /de/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

A`MutationObserver` Objekt kann verwendet werden, um Mutationen im Baum von zu beobachten[`Node`](../../aspose.html.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Konstruiert ein MutationObserver-Objekt und setzt dessen[`MutationCallback`](../mutationcallback/) Zurückrufen. Der Rückruf wird mit einer Liste von MutationRecord-Objekten als erstem Argument und dem konstruierten MutationObserver-Objekt als zweitem Argument aufgerufen. Es wird aufgerufen, nachdem sich Knoten bei der registriert haben!:Observe(Node, IMutationObserverInit) Methode, sind mutiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | Verhindert, dass Beobachter Mutationen beobachten. Bis die Methode Observe() erneut verwendet wird, wird der Rückruf des Beobachters nicht aufgerufen. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Weist den Benutzeragenten an, ein bestimmtes Ziel (einen Knoten) zu beobachten und alle Mutationen basierend auf den durch Optionen (ein Objekt) angegebenen Kriterien zu melden. Das Options-Argument ermöglicht das Festlegen von Mutationsbeobachtungsoptionen über Objektmitglieder. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Weist den Benutzeragenten an, ein bestimmtes Ziel (einen Knoten) zu beobachten und alle Mutationen basierend auf den durch Optionen (ein Objekt) angegebenen Kriterien zu melden. Das Options-Argument ermöglicht das Festlegen von Mutationsbeobachtungsoptionen über Objektmitglieder. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | Die Methode gibt eine Kopie der Datensatzwarteschlange zurück und leert dann die Datensatzwarteschlange. |

### Siehe auch

* class [DOMObject](../../aspose.html.dom/domobject/)
* namensraum [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* Montage [Aspose.HTML](../../)


