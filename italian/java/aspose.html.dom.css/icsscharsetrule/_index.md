---
title: "Interfaccia ICSSCharsetRule"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.dom.css.ICSSCharsetRule. L'interfaccia CSSCharsetRule rappresenta una regola charset in un foglio di stile CSS. Il valore dell'attributo encoding non influisce sulla codifica dei dati testuali negli oggetti DOM; questa codifica è sempre UTF-16. Dopo il caricamento di un foglio di stile, il valore dell'attributo encoding è quello trovato nella regola charset. Se nel documento originale non c'era alcun charset, non viene creata alcuna CSSCharsetRule. Il valore dell'attributo encoding può anche essere usato come suggerimento per la codifica utilizzata nella serializzazione del foglio di stile."
type: docs

url: /it/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

L'interfaccia CSSCharsetRule rappresenta una regola @charset in un foglio di stile CSS. Il valore dell'attributo encoding non influisce sulla codifica dei dati di testo negli oggetti DOM; questa codifica è sempre UTF-16. Dopo il caricamento di un foglio di stile, il valore dell'attributo encoding corrisponde al valore trovato nella regola @charset. Se non era presente alcun @charset nel documento originale, non viene creata alcuna CSSCharsetRule. Il valore dell'attributo encoding può anche essere usato come suggerimento per la codifica utilizzata durante la serializzazione del foglio di stile.

```java
public interface ICSSCharsetRule : ICSSRule
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### Vedi anche

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
