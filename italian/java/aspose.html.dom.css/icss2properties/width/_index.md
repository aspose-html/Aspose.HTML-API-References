---
title: "ICSS2Properties.Width"
second_title: "Aspose.HTML per Java Riferimento API"
description: "ICSS2Properties property. Questa proprietà specifica la larghezza del contenuto delle caselle generate da elementi block-level e replaced."
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Questa proprietà specifica la [larghezza del contenuto](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) delle caselle generate da elementi block-level e [replaced](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) elements.

Questa proprietà non si applica agli elementi non sostituiti di tipo [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) elementi. La larghezza delle scatole di un elemento inline non sostituito è quella del contenuto renderizzato al loro interno (prima di qualsiasi offset relativo dei figli). Ricorda che le scatole inline fluiscono nei [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box). La larghezza dei line boxes è determinata dal loro [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block), ma può essere ridotta dalla presenza di [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats).

La larghezza della scatola di un elemento sostituito è [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) e può essere scalata dall'agente utente se il valore di questa proprietà è diverso da 'auto'.

I valori hanno i seguenti significati:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Specifica una larghezza fissa.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Specifica una larghezza percentuale. La percentuale è calcolata rispetto alla larghezza del [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) della scatola generata. auto - La larghezza dipende dai valori di altre proprietà. Vedi le sezioni seguenti. Nota: i valori negativi per ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) sono illegali.

```java
public String Width { get; set; }
```

### Valore di ritorno

proprietà width

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
