---
title: Class MutationRecord
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Mutations.MutationRecord klas. Een MutationRecord vertegenwoordigt een individuele DOMmutatie. Het is het object waaraan wordt doorgegevenMutationObserver SMutationCallback .
type: docs
weight: 990
url: /nl/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Een MutationRecord vertegenwoordigt een individuele DOM-mutatie. Het is het object waaraan wordt doorgegeven[`MutationObserver`](../mutationobserver/) S[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | Retourneert de toegevoegde knooppunten. |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | Retourneert de lokale naam van het gewijzigde attribuut, en anders null. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | Retourneert de naamruimte van het gewijzigde attribuut, en anders null. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | Retourneert het volgende broertje van de toegevoegde of verwijderde knooppunten, of null. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | De geretourneerde waarde is afhankelijk van het type. Voor "attributen" is dit de waarde van het gewijzigde attribuut vóór de wijziging. Voor "characterData" zijn dit de gegevens van het gewijzigde knooppunt vóór de wijziging. Voor "childList" is dit null. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | Retourneert het vorige broertje van de toegevoegde of verwijderde knooppunten, of null. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | Retourneert de verwijderde knooppunten. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | Retourneert het knooppunt waarop de mutatie betrekking heeft, afhankelijk van het type. Voor "attributen" is dit het element waarvan het attribuut is gewijzigd. Voor "characterData" is dit het CharacterData-knooppunt. Voor "childList" is dit het knooppunt waarvan de kinderen zijn gewijzigd. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | Retourneert "attributen" als het een attribuutmutatie was, "characterData" als het een mutatie was naar een CharacterData-knooppunt en "childList" als het een mutatie was naar de boom van knooppunten. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |

### Zie ook

* class [DOMObject](../../aspose.html.dom/domobject/)
* naamruimte [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* montage [Aspose.HTML](../../)


