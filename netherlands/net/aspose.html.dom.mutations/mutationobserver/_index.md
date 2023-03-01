---
title: Class MutationObserver
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Mutations.MutationObserver klas. EENMutationObserver object kan worden gebruikt om mutaties in de boom van waar te nemenNode .
type: docs
weight: 970
url: /nl/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

EEN`MutationObserver` object kan worden gebruikt om mutaties in de boom van waar te nemen[`Node`](../../aspose.html.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Construeert een MutationObserver-object en stelt het in[`MutationCallback`](../mutationcallback/) terugbellen. De callback wordt aangeroepen met een lijst van MutationRecord-objecten als eerste argument en het geconstrueerde MutationObserver-object als tweede argument. Het wordt aangeroepen nadat knooppunten zijn geregistreerd bij de!:Observe(Node, IMutationObserverInit) methode, zijn gemuteerd. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | Zorgt ervoor dat de waarnemer geen mutaties waarneemt. Totdat de methode observer() opnieuw wordt gebruikt, wordt de callback van de waarnemer niet aangeroepen. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Instrueert de user-agent om een bepaald doel (een knooppunt) te observeren en eventuele mutaties te rapporteren op basis van de criteria gegeven door opties (een object). Met het argument opties kunnen observatie-opties voor mutaties worden ingesteld via objectleden. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Instrueert de user-agent om een bepaald doel (een knooppunt) te observeren en eventuele mutaties te rapporteren op basis van de criteria gegeven door opties (een object). Met het argument opties kunnen observatie-opties voor mutaties worden ingesteld via objectleden. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | De methode retourneert een kopie van de recordwachtrij en leegt vervolgens de recordwachtrij. |

### Zie ook

* class [DOMObject](../../aspose.html.dom/domobject/)
* naamruimte [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* montage [Aspose.HTML](../../)


