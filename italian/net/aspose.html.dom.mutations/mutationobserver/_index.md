---
title: Class MutationObserver
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Mutations.MutationObserver classe. AMutationObserver Loggetto può essere utilizzato per osservare le mutazioni dellalbero diNode .
type: docs
weight: 970
url: /it/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

A`MutationObserver` L'oggetto può essere utilizzato per osservare le mutazioni dell'albero di[`Node`](../../aspose.html.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Costruisce un oggetto MutationObserver e imposta il suo[`MutationCallback`](../mutationcallback/) richiamare. Il callback viene richiamato con un elenco di oggetti MutationRecord come primo argomento e l'oggetto MutationObserver costruito come secondo argomento. Viene richiamato dopo che i nodi si sono registrati con il!:Observe(Node, IMutationObserverInit) metodo, sono mutati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | Impedisce all'osservatore di osservare eventuali mutazioni. Fino a quando non viene utilizzato nuovamente il metodo Observ(), il callback dell'osservatore non verrà richiamato. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Indica all'agente utente di osservare un determinato target (un nodo) e di segnalare eventuali mutazioni in base ai criteri forniti dalle opzioni (un oggetto). L'argomento options consente di impostare le opzioni di osservazione delle mutazioni tramite i membri dell'oggetto. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Indica all'agente utente di osservare un determinato target (un nodo) e di segnalare eventuali mutazioni in base ai criteri forniti dalle opzioni (un oggetto). L'argomento options consente di impostare le opzioni di osservazione delle mutazioni tramite i membri dell'oggetto. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | Il metodo restituisce una copia della coda dei record e quindi svuota la coda dei record. |

### Guarda anche

* class [DOMObject](../../aspose.html.dom/domobject/)
* spazio dei nomi [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* assemblea [Aspose.HTML](../../)


