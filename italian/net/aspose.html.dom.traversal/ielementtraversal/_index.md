---
title: Interface IElementTraversal
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Traversal.IElementTraversal interfaccia. Linterfaccia ElementTraversal è un insieme di attributi di sola lettura che consentono a un autore di navigare facilmente tra gli elementi in un documento. Nelle implementazioni conformi di Element Traversal tutti gli oggetti che implementano Element devono implementare anche linterfaccia ElementTraversal.
type: docs
weight: 2480
url: /it/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

L'interfaccia ElementTraversal è un insieme di attributi di sola lettura che consentono a un autore di navigare facilmente tra gli elementi in un documento. Nelle implementazioni conformi di Element Traversal, tutti gli oggetti che implementano Element devono implementare anche l'interfaccia ElementTraversal.

```csharp
public interface IElementTraversal
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Restituisce il numero corrente di nodi elemento che sono figli di questo elemento. 0 se questo elemento non ha nodi figli di nodeType 1. |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Restituisce il primo nodo dell'elemento figlio di questo elemento. null se questo elemento non ha elementi figlio. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Restituisce l'ultimo nodo dell'elemento figlio di questo elemento. null se questo elemento non ha elementi figlio. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Restituisce il successivo nodo dell'elemento di pari livello di questo elemento. null se questo elemento non ha nodi di pari livello che vengono dopo questo nell'albero del documento. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Restituisce il precedente nodo dell'elemento di pari livello di questo elemento. null se questo elemento non ha nodi di pari livello che precedono questo nell'albero del documento. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* assemblea [Aspose.HTML](../../)


