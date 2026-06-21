---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà ICSS2Properties. I valori per questa proprietà hanno i seguenti significati"
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

I valori per questa proprietà hanno i seguenti significati:

normal - L'elemento non apre un livello aggiuntivo di incorporamento rispetto all'algoritmo bidirezionale. Per gli elementi inline, il riordino implicito funziona attraverso i confini degli elementi. embed - Se l'elemento è inline, questo valore apre un livello aggiuntivo di incorporamento rispetto all'algoritmo bidirezionale. La direzione di questo livello è fornita dalla proprietà ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction). All'interno dell'elemento, il riordino è effettuato implicitamente. Ciò corrisponde all'aggiunta di un LRE (U+202A; per 'direction: ltr') o RLE (U+202B; per 'direction: rtl') all'inizio dell'elemento e di un PDF (U+202C) alla fine dell'elemento. bidi-override - Se l'elemento è inline o è un elemento a blocco che contiene solo elementi inline, questo crea un override. Ciò significa che all'interno dell'elemento, il riordino avviene strettamente in sequenza secondo la proprietà ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction); la parte implicita dell'algoritmo bidirezionale è ignorata. Ciò corrisponde all'aggiunta di un LRO (U+202D; per 'direction: ltr') o RLO (U+202E; per 'direction: rtl') all'inizio dell'elemento e di un PDF (U+202C) alla fine dell'elemento.

```java
public String UnicodeBidi { get; set; }
```

### Valore di ritorno

proprietà unicode-bidi

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
