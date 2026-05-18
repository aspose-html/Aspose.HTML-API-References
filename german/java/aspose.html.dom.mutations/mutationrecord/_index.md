---
title: "MutationRecord Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.mutations.MutationRecord Klasse. Ein MutationRecord stellt eine einzelne DOM-Mutation dar. Es ist das Objekt, das an den MutationCallback von MutationObservers übergeben wird."
type: docs

url: /de/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Ein MutationRecord stellt eine einzelne DOM-Mutation dar. Es ist das Objekt, das an den [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/) übergeben wird.

```java
public class MutationRecord : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Gibt die hinzugefügten Knoten zurück. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Gibt den lokalen Namen des geänderten Attributs zurück, andernfalls null. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Gibt das Paket des geänderten Attributs zurück, andernfalls null. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Gibt das nächste Geschwisterelement der hinzugefügten oder entfernten Knoten zurück, oder null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) Der Rückgabewert hängt vom Typ ab. Für "attributes" ist es der Wert des geänderten Attributs vor der Änderung. Für "characterData" sind es die Daten des geänderten Knotens vor der Änderung. Für "childList" ist er null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Gibt das vorherige Geschwisterelement der hinzugefügten oder entfernten Knoten zurück, oder null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Gibt die entfernten Knoten zurück. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Gibt den Knoten zurück, den die Mutation betroffen hat, abhängig vom Typ. Für "attributes" ist es das Element, dessen Attribut geändert wurde. Für "characterData" ist es der CharacterData‑Knoten. Für "childList" ist es der Knoten, dessen Kinder geändert wurden. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Gibt "attributes" zurück, wenn es sich um eine Attributmutation handelte, "characterData", wenn es eine Mutation an einem CharacterData‑Knoten war, und "childList", wenn es eine Mutation am Knotenbaum war. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
