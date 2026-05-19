---
title: "MutationObserver Classe"
second_title: "Riferimento API Aspose.HTML per Java"
description: "com.aspose.html.dom.mutations.MutationObserver class. Un oggetto può essere usato per osservare le mutazioni dell'albero di"
type: docs

url: /it/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Un oggetto può essere usato per osservare le mutazioni dell'albero di [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Costruisce un oggetto MutationObserver e imposta il suo [`MutationCallback`](../mutationcallback/) al callback. Il callback viene invocato con un elenco di oggetti MutationRecord come primo argomento e l'oggetto MutationObserver costruito come secondo argomento. Viene invocato dopo che i nodi registrati con il metodo !:Observe(Node, IMutationObserverInit) sono mutati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Interrompe l'osservatore dal osservare qualsiasi mutazione. Finché il metodo observe() non viene usato di nuovo, il callback dell'osservatore non verrà invocato. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Istruisce l'agente utente a osservare un determinato target (un nodo) e a segnalare eventuali mutazioni in base ai criteri forniti dalle opzioni (un oggetto). L'argomento options consente di impostare le opzioni di osservazione delle mutazioni tramite i membri dell'oggetto. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Istruisce l'agente utente a osservare un determinato target (un nodo) e a segnalare eventuali mutazioni in base ai criteri forniti dalle opzioni (un oggetto). L'argomento options consente di impostare le opzioni di osservazione delle mutazioni tramite i membri dell'oggetto. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | Il metodo restituisce una copia della coda dei record e poi svuota la coda dei record. |

### Vedi anche

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
