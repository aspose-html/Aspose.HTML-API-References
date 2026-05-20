---
title: "MutationObserver-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.mutations.MutationObserver-klass. Ett objekt kan användas för att observera mutationer i trädet av"
type: docs

url: /sv/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Ett objekt kan användas för att observera mutationer i trädet av [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Skapar ett MutationObserver-objekt och sätter dess [`MutationCallback`](../mutationcallback/) till callback. Callbacken anropas med en lista av MutationRecord-objekt som första argument och det konstruerade MutationObserver-objektet som andra argument. Den anropas efter att noder registrerade med metoden !:Observe(Node, IMutationObserverInit) har muterats. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Stoppar observatören från att observera några mutationer. Tills observe()-metoden används igen kommer observatörens callback inte att anropas. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Instruktioner till användaragenten att observera ett givet mål (en nod) och rapportera eventuella mutationer baserat på kriterierna som ges av alternativ (ett objekt). Argumentet options möjliggör att ställa in mutationsobservationsalternativ via objektmedlemmar. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Instruktioner till användaragenten att observera ett givet mål (en nod) och rapportera eventuella mutationer baserat på kriterierna som ges av alternativ (ett objekt). Argumentet options möjliggör att ställa in mutationsobservationsalternativ via objektmedlemmar. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | Metoden returnerar en kopia av postkön och tömmer sedan postkön. |

### Se även

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
