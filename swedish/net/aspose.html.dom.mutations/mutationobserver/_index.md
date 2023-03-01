---
title: Class MutationObserver
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Mutations.MutationObserver klass. AMutationObserver objekt kan användas för att observera mutationer i trädet avNode .
type: docs
weight: 970
url: /sv/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

A`MutationObserver` objekt kan användas för att observera mutationer i trädet av[`Node`](../../aspose.html.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Konstruerar ett MutationObserver-objekt och ställer in dess[`MutationCallback`](../mutationcallback/) att ringa tillbaka. Återuppringningen anropas med en lista med MutationRecord-objekt som första argument och det konstruerade MutationObserver-objektet som andra argument. Det anropas efter noder registrerade med!:Observe(Node, IMutationObserverInit) metod, är muterade. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | Stoppar observatören från att observera några mutationer. Tills metoden observe() används igen kommer observatörens återuppringning inte att anropas. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Instruerar användaragenten att observera ett givet mål (en nod) och rapportera eventuella mutationer baserat på kriterierna som ges av optioner (ett objekt). Alternativargumentet tillåter att ställa in alternativ för mutationsobservation via objektmedlemmar. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Instruerar användaragenten att observera ett givet mål (en nod) och rapportera eventuella mutationer baserat på kriterierna som ges av optioner (ett objekt). Alternativargumentet tillåter att ställa in alternativ för mutationsobservation via objektmedlemmar. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | Metoden returnerar en kopia av postkön och tömmer sedan postkön. |

### Se även

* class [DOMObject](../../aspose.html.dom/domobject/)
* namnutrymme [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* hopsättning [Aspose.HTML](../../)


