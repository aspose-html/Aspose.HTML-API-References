---
title: "Interfaccia ICSSValueList"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.dom.css.ICSSValueList. L'interfaccia CSSValueList deriva dall'interfaccia CSSValue e fornisce l'astrazione di una collezione ordinata di valori CSS."
type: docs

url: /it/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

L'interfaccia CSSValueList deriva dall'interfaccia [`CSSValue`](../cssvalue/) e fornisce l'astrazione di una collezione ordinata di valori CSS.

Alcune proprietà consentono una lista vuota nella loro sintassi. In tal caso, queste proprietà assumono l'identificatore none. Quindi, una lista vuota significa che la proprietà ha il valore none.

Gli elementi nella CSSValueList sono accessibili tramite un indice intero, a partire da 0.

```java
public interface ICSSValueList
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Questo metodo è usato per recuperare un CSSValue tramite indice ordinal. L'ordine in questa collezione rappresenta l'ordine dei valori nella proprietà di stile CSS. Se l'indice è maggiore o uguale al numero di valori nella lista, restituisce null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) La proprietà di sola lettura length dell'interfaccia CSSValueList rappresenta il numero di CSSValue nella lista. L'intervallo di valori validi degli indici è da 0 a length-1 inclusi. |

## Osservazioni

Questa interfaccia faceva parte di un tentativo di creare un CSS Object Model tipizzato. Tale tentativo è stato abbandonato e la maggior parte dei browser non lo implementa.

Per raggiungere il tuo scopo, puoi usare:

il [CSS Object Model](https://drafts.csswg.org/cssom/) non tipizzato, ampiamente supportato, o il moderno [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), meno supportato e considerato sperimentale.

### Vedi anche

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
