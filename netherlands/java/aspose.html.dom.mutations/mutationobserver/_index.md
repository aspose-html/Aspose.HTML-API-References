---
title: "MutationObserver klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.mutations.MutationObserver klasse. Een object kan worden gebruikt om mutaties in de boom van te observeren"
type: docs

url: /nl/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Een object kan worden gebruikt om mutaties in de boom van [`.`](../../com.aspose.html.dom/node/) te observeren.

```java
public class MutationObserver : DOMObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Construeert een MutationObserver‑object en stelt zijn [`MutationCallback`](../mutationcallback/) in op callback. De callback wordt aangeroepen met een lijst van MutationRecord‑objecten als eerste argument en het geconstrueerde MutationObserver‑object als tweede argument. Hij wordt aangeroepen nadat knooppunten die zijn geregistreerd met de !:Observe(Node, IMutationObserverInit)-methode, zijn gemuteerd. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Stopt de waarnemer met het observeren van mutaties. Totdat de observe()-methode opnieuw wordt gebruikt, zal de callback van de waarnemer niet worden aangeroepen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Instrueert de user agent om een opgegeven doel (een knooppunt) te observeren en eventuele mutaties te rapporteren op basis van de criteria die door opties (een object) worden gegeven. Het opties‑argument maakt het mogelijk mutatie‑observatie‑opties in te stellen via objectleden. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Instrueert de user agent om een opgegeven doel (een knooppunt) te observeren en eventuele mutaties te rapporteren op basis van de criteria die door opties (een object) worden gegeven. Het opties‑argument maakt het mogelijk mutatie‑observatie‑opties in te stellen via objectleden. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | De methode retourneert een kopie van de record‑wachtrij en maakt vervolgens de record‑wachtrij leeg. |

### Zie ook

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
