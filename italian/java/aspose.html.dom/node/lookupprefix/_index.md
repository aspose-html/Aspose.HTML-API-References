---
title: "Node.LookupPrefix"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Node. Il metodo lookupPrefix dell'interfaccia Node restituisce una String contenente il prefisso per un determinato URI di pacchetto, se presente, altrimenti null. Quando sono possibili più prefissi, viene restituito il primo prefisso"
type: docs

url: /it/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

Il metodo lookupPrefix() dell'interfaccia Node restituisce una String contenente il prefisso per un dato URI del package, se presente, e null se non presente. Quando sono possibili più prefissi, viene restituito il primo prefisso.

```java
public String LookupPrefix(String packageURI)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| packageURI | String | Una String contenente il pacchetto per cui cercare il prefisso. |

### Valore di ritorno

Una String contenente il prefisso corrispondente, o null se non ne è stato trovato alcuno. Se il pacchetto è null, o la String è vuota, lookupPrefix() restituisce null.

Se il nodo è un [`DocumentType`](../../documenttype/) o un [`DocumentFragment`](../../documentfragment/), lookupPrefix() restituisce sempre null.

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
