---
title: "Classe MutationRecord"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.mutations.MutationRecord class. Un MutationRecord rappresenta una singola mutazione del DOM. È l'oggetto che viene passato al MutationCallback dei MutationObserver."
type: docs

url: /it/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Un MutationRecord rappresenta una singola mutazione del DOM. È l'oggetto che viene passato al [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```java
public class MutationRecord : DOMObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) Restituisce i nodi aggiunti. |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) Restituisce il nome locale dell'attributo modificato, altrimenti null. |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) Restituisce il pacchetto dell'attributo modificato, altrimenti null. |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) Restituisce il fratello successivo dei nodi aggiunti o rimossi, o null. |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) Il valore restituito dipende dal tipo. Per "attributes", è il valore dell'attributo modificato prima della modifica. Per "characterData", sono i dati del nodo modificato prima della modifica. Per "childList", è null. |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) Restituisce il fratello precedente dei nodi aggiunti o rimossi, o null. |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) Restituisce i nodi rimossi. |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) Restituisce il nodo interessato dalla mutazione, a seconda del tipo. Per "attributes", è l'elemento il cui attributo è cambiato. Per "characterData", è il nodo CharacterData. Per "childList", è il nodo i cui figli sono cambiati. |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) Restituisce "attributes" se era una mutazione di attributo, "characterData" se era una mutazione di un nodo CharacterData e "childList" se era una mutazione dell'albero dei nodi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |

### Vedi anche

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
