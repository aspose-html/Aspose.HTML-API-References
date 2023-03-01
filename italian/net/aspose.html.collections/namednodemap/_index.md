---
title: Class NamedNodeMap
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Collections.NamedNodeMap classe. Rappresenta raccolte di attributi a cui è possibile accedere per nome.
type: docs
weight: 40
url: /it/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

Rappresenta raccolte di attributi a cui è possibile accedere per nome.

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | Restituisce l'indice-esimo elemento nella mappa. Se index è maggiore o uguale al numero di nodi in questa mappa, restituisce null. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | Il numero di nodi in questa mappa. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | Restituisce un enumeratore che scorre la raccolta. |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | Recupera un nodo specificato per nome. |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | Recupera un nodo specificato dal nome locale e dall'URI dello spazio dei nomi. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | Rimuove un nodo specificato per nome. |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | Rimuove un nodo specificato dal nome locale e dall'URI dello spazio dei nomi. |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | Aggiunge un nodo usando il suo attributo nodeName. Se un nodo con quel nome è già presente in questa mappa, viene sostituito da quello nuovo. Sostituire un nodo da solo non ha alcun effetto. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | Aggiunge un nodo utilizzando il relativo namespaceURI e localName. Se un nodo con quell'URI dello spazio dei nomi e quel nome locale è già presente in questa mappa, viene sostituito da quello nuovo. Sostituire un nodo da solo non ha alcun effetto. |

### Guarda anche

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* spazio dei nomi [Aspose.Html.Collections](../../aspose.html.collections/)
* assemblea [Aspose.HTML](../../)


