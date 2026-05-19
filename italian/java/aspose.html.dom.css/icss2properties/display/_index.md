---
title: "ICSS2Properties.Display"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Proprietà ICSS2Properties. I valori di questa proprietà hanno i seguenti significati"
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

I valori di questa proprietà hanno i seguenti significati:

block - Questo valore fa sì che un elemento generi una casella di blocco principale. inline - Questo valore fa sì che un elemento generi una o più caselle inline. list-item - Questo valore fa sì che un elemento (ad es., LI in HTML) generi una casella di blocco principale e una casella inline di tipo list-item. Per informazioni sulle liste e esempi di formattazione delle liste, consultare la sezione su [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists). marker - Questo valore dichiara [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) prima o dopo una casella come marcatore. Questo valore dovrebbe essere usato solo con [:before e :after pseudo-elements](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) collegati a elementi block-level. In altri casi, questo valore è interpretato come 'inline'. Consultare la sezione su [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) per ulteriori informazioni. none - Questo valore fa sì che un elemento non generi caselle nella [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (cioè, l'elemento non ha effetto sul layout). Anche gli elementi discendenti non generano caselle; questo comportamento non può essere sovrascritto impostando la proprietà ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) sui discendenti. Si noti che un display 'none' non crea una casella invisibile; non crea alcuna casella. CSS include meccanismi che consentono a un elemento di generare caselle nella struttura di formattazione che influenzano la formattazione ma non sono visibili. Consultare la sezione su [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) per i dettagli. run-in and compact - Questi valori creano caselle block o inline, a seconda del contesto. Le proprietà si applicano a caselle run-in e compact in base al loro stato finale (inline-level o block-level). Per esempio, la proprietà ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) si applica solo se la casella diventa una casella block. table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell e table-caption - Questi valori fanno sì che un elemento si comporti come un elemento tabella (soggetto a restrizioni descritte nel capitolo su [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Valore di ritorno

proprietà display

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
