---
title: "MutationRecord klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.mutations.MutationRecord klasse. Een MutationRecord vertegenwoordigt een individuele DOM‑mutatie. Het is het object dat wordt doorgegeven aan MutationObservers MutationCallback"
type: docs

url: /nl/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Een MutationRecord vertegenwoordigt een individuele DOM‑mutatie. Het is het object dat wordt doorgegeven aan [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Retourneer de toegevoegde knooppunten. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Retourneert de lokale naam van het gewijzigde attribuut, en anders null. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Retourneert het pakket van het gewijzigde attribuut, en anders null. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Retourneer de volgende sibling van de toegevoegde of verwijderde knooppunten, of null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) De retourwaarde hangt af van het type. Voor "attributes" is het de waarde van het gewijzigde attribuut vóór de wijziging. Voor "characterData" zijn het de gegevens van het gewijzigde knooppunt vóór de wijziging. Voor "childList" is het null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Retourneert de vorige sibling van de toegevoegde of verwijderde knooppunten, of null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Retourneer de verwijderde knooppunten. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Retourneert het knooppunt dat door de mutatie is beïnvloed, afhankelijk van het type. Voor "attributes" is het het element waarvan het attribuut is gewijzigd. Voor "characterData" is het het CharacterData‑knooppunt. Voor "childList" is het het knooppunt waarvan de kinderen zijn gewijzigd. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Retourneert "attributes" als het een attribuutmutatie was, "characterData" als het een mutatie van een CharacterData‑knooppunt was en "childList" als het een mutatie van de knooppombomen was. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |

### Zie ook

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
