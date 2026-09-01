---
title: "Node.CloneNode"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Node method. Il metodo cloneNode dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato. Il suo parametro controlla se anche il sottoalbero contenuto in un nodo viene clonato o meno."
type: docs

url: /it/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Il metodo cloneNode() dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato questo metodo. Il suo parametro controlla se il sottoalbero contenuto in un nodo viene anche clonato o meno.

Clonare un nodo copia tutti i suoi attributi e i loro valori, inclusi i listener intrinseci (inline). Non copia i listener di eventi aggiunti usando [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) o quelli assegnati alle proprietà dell'elemento (ad es., node.onclick = someFunction). Inoltre, per un elemento [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/), l'immagine dipinta non viene copiata.

```java
public Node CloneNode()
```

### Valore di ritorno

Il nuovo [`Node`](../) clonato. Il nodo clonato non ha genitore e non fa parte del documento, finché non viene aggiunto a un altro nodo che fa parte del documento, usando [`Node.appendChild()`](../appendchild/) o un metodo simile.

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

Il metodo cloneNode() dell'interfaccia Node restituisce un duplicato del nodo su cui è stato chiamato questo metodo. Il suo parametro controlla se il sottoalbero contenuto in un nodo viene anche clonato o meno.

Clonare un nodo copia tutti i suoi attributi e i loro valori, inclusi i listener intrinseci (inline). Non copia i listener di eventi aggiunti usando [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) o quelli assegnati alle proprietà dell'elemento (ad es., node.onclick = someFunction). Inoltre, per un elemento [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) l'immagine dipinta non viene copiata.

```java
public Node CloneNode(bool deep)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deep | Boolean | Se true, allora il nodo e tutto il suo sottoalbero, incluso il testo che può trovarsi nei nodi figlio [`Text`](../../text/), vengono anche copiati. |

### Valore di ritorno

Il nuovo [Node](T:com.aspose.html.dom.Node) clonato. Il nodo clonato non ha genitore e non fa parte del documento, finché non viene aggiunto a un altro nodo che fa parte del documento, usando [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) o un metodo simile.

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
