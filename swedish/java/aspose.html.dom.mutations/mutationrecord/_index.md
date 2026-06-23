---
title: "MutationRecord-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.mutations.MutationRecord-klass. En MutationRecord representerar en enskild DOM-mutation. Det är objektet som skickas till MutationObservers MutationCallback."
type: docs

url: /sv/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

En MutationRecord representerar en enskild DOM-mutation. Det är objektet som skickas till [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Returnerar de tillagda noderna. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Returnerar det lokala namnet på det ändrade attributet, annars null. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Returnerar paketet för det ändrade attributet, annars null. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Returnerar nästa syskon till de tillagda eller borttagna noderna, eller null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) Returvärdet beror på typen. För "attributes" är det värdet på det ändrade attributet före ändringen. För "characterData" är det data för den ändrade noden före ändringen. För "childList" är det null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Returnerar föregående syskon till de tillagda eller borttagna noderna, eller null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Returnerar de borttagna noderna. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Returnerar noden som mutationen påverkade, beroende på typen. För "attributes" är det elementet vars attribut ändrades. För "characterData" är det CharacterData-noden. För "childList" är det noden vars barn ändrades. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Returnerar "attributes" om det var en attributmutation, "characterData" om det var en mutation av en CharacterData-nod och "childList" om det var en mutation av nodträdet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |

### Se även

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
