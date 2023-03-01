---
title: Class MutationRecord
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Mutations.MutationRecord classe. Un MutationRecord rappresenta una singola mutazione DOM. È loggetto a cui viene passatoMutationObserver SMutationCallback .
type: docs
weight: 990
url: /it/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Un MutationRecord rappresenta una singola mutazione DOM. È l'oggetto a cui viene passato[`MutationObserver`](../mutationobserver/) S[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | Restituisce i nodi aggiunti. |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | Restituisce il nome locale dell'attributo modificato e null in caso contrario. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | Restituisce lo spazio dei nomi dell'attributo modificato e null in caso contrario. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | Restituisce il fratello successivo dei nodi aggiunti o rimossi, oppure null. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | Il valore restituito dipende dal tipo. Per "attributi", è il valore dell'attributo modificato prima della modifica. Per "characterData", è il dato del nodo modificato prima della modifica. Per "childList", è nullo. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | Restituisce il fratello precedente dei nodi aggiunti o rimossi, oppure null. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | Restituisce i nodi rimossi. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | Restituisce il nodo interessato dalla mutazione, a seconda del tipo. Per "attributi", è l'elemento il cui attributo è cambiato. Per "characterData", è il nodo CharacterData. Per "childList", è il nodo i cui figli sono cambiati. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | Restituisce "attributes" se si trattava di una mutazione di attributo, "characterData" se si trattava di una mutazione di un nodo CharacterData e "childList" se si trattava di una mutazione dell'albero dei nodi. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |

### Guarda anche

* class [DOMObject](../../aspose.html.dom/domobject/)
* spazio dei nomi [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* assemblea [Aspose.HTML](../../)


