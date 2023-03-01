---
title: IXPathEvaluator.CreateNSResolver
second_title: Aspose.HTML per riferimento API .NET
description: IXPathEvaluator metodo. Adatta qualsiasi nodo DOM per risolvere gli spazi dei nomi in modo che unespressione XPath possa essere facilmente valutata rispetto al contesto del nodo in cui è apparsa allinterno del documento. Questo adattatore funziona come il metodo DOM Level 3lookupNamespaceURI sui nodi nel risolvere il namespaceURI da un dato prefisso utilizzando le informazioni correnti disponibili nella gerarchia del nodo al momento viene chiamato lookupNamespaceURI risolvendo anche correttamente il prefisso xml implicito.
type: docs
weight: 20
url: /it/net/aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Adatta qualsiasi nodo DOM per risolvere gli spazi dei nomi in modo che un'espressione XPath possa essere facilmente valutata rispetto al contesto del nodo in cui è apparsa all'interno del documento. Questo adattatore funziona come il metodo DOM Level 3`lookupNamespaceURI` sui nodi nel risolvere il namespaceURI da un dato prefisso utilizzando le informazioni correnti disponibili nella gerarchia del nodo al momento viene chiamato lookupNamespaceURI, risolvendo anche correttamente il prefisso xml implicito.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeResolver | Node | Il nodo da utilizzare come contesto per la risoluzione dello spazio dei nomi. |

### Valore di ritorno

[`IXPathNSResolver`](../../ixpathnsresolver/) che risolve gli spazi dei nomi rispetto alle definizioni nell'ambito di un nodo specificato.

### Guarda anche

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* spazio dei nomi [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* assemblea [Aspose.HTML](../../../)


