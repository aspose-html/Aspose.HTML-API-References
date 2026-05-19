---
title: "Node.Normalize"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Node. Inserisce tutti i nodi Text nella profondità completa del sotto-albero sotto questo Node, inclusi i nodi attributo, in una forma normale in cui solo la struttura, ad esempio elementi, commenti, istruzioni di elaborazione, sezioni CDATA e riferimenti a entità, separa i nodi Text, cioè non ci sono né nodi Text adiacenti né nodi Text vuoti. Questo può essere usato per garantire che la vista DOM di un documento sia la stessa di quella che si otterrebbe se fosse salvato e ricaricato, ed è utile quando operazioni come le ricerche XPointer che dipendono da una particolare struttura dell'albero del documento devono essere utilizzate. Se il parametro normalize-characters dell'oggetto DOMConfiguration collegato a Node.ownerDocument è true, questo metodo normalizzerà anche completamente i caratteri dei nodi Text."
type: docs

url: /it/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

Inserisce tutti i nodi [`Text`](../../text/) nella profondità completa del sotto-albero sotto questo Node, inclusi i nodi attributo, in una forma "normale" in cui solo la struttura (ad esempio [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), e [`entity references`](../../entityreference/)) separa i nodi [`Text`](../../text/), cioè non ci sono né nodi Text adiacenti né nodi Text vuoti. Questo può essere usato per garantire che la vista DOM di un documento sia la stessa di quella che si otterrebbe se fosse salvato e ricaricato, ed è utile quando operazioni (come le ricerche XPointer [XPointer]) che dipendono da una particolare struttura dell'albero del documento devono essere utilizzate. Se il parametro "normalize-characters" del [`DOMConfiguration`](../../../com.aspose.html/configuration/) oggetto collegato al [`Node.ownerDocument`](../ownerdocument/) è true, questo metodo normalizzerà anche completamente i caratteri dei nodi Text.

```java
public void Normalize()
```

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
