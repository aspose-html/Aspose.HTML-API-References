---
title: "ICSS2Properties.VerticalAlign"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà ICSS2Properties. Questa proprietà influisce sul posizionamento verticale all'interno di una line box delle caselle generate da un elemento inline-level. I valori seguenti hanno significato solo rispetto a un elemento inline-level genitore o a un elemento block-level genitore se quell'elemento genera caselle inline anonime; non hanno effetto se non esiste tale genitore."
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Questa proprietà influisce sul posizionamento verticale all'interno di una line box delle caselle generate da un elemento inline-level. I valori seguenti hanno significato solo rispetto a un elemento inline-level genitore, o a un elemento block-level genitore, se quell'elemento genera [caselle inline anonime](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous); non hanno effetto se non esiste tale genitore.

Nota. I valori di questa proprietà hanno significati leggermente diversi nel contesto delle tabelle. Si prega di consultare la sezione sugli [algoritmi di altezza delle tabelle](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) per i dettagli. baseline - Allinea la linea di base della casella con la linea di base della casella genitore. Se la casella non ha una linea di base, allinea il fondo della casella con la linea di base del genitore. middle - Allinea il punto medio verticale della casella con la linea di base della casella genitore più metà dell'x-height del genitore. sub - Abbassa la linea di base della casella alla posizione corretta per i pedici della casella del genitore. (Questo valore non influisce sulla dimensione del carattere del testo dell'elemento.) super - Alza la linea di base della casella alla posizione corretta per i apici della casella del genitore. (Questo valore non influisce sulla dimensione del carattere del testo dell'elemento.) text-top - Allinea la parte superiore della casella con la parte superiore del carattere dell'elemento genitore. text-bottom - Allinea la parte inferiore della casella con la parte inferiore del carattere dell'elemento genitore. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Alza (valore positivo) o abbassa (valore negativo) la casella di questa distanza (una percentuale del valore di ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height)). Il valore '0%' significa lo stesso di 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Alza (valore positivo) o abbassa (valore negativo) la casella di questa distanza. Il valore '0cm' significa lo stesso di 'baseline'. top - Allinea la parte superiore della casella con la parte superiore della line box. bottom - Allinea la parte inferiore della casella con la parte inferiore della line box.

```java
public String VerticalAlign { get; set; }
```

### Valore di ritorno

proprietà vertical-align

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
