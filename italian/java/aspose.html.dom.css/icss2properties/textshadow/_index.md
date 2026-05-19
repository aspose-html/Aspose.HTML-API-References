---
title: "ICSS2Properties.TextShadow"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Proprietà ICSS2Properties. Questa proprietà accetta un elenco separato da virgole di effetti di ombra da applicare al testo dell'elemento. Gli effetti di ombra sono applicati nell'ordine specificato e possono quindi sovrapporsi tra loro, ma non sovrapporranno mai il testo stesso. Gli effetti di ombra non alterano le dimensioni di un box ma possono estendersi oltre i suoi confini. Il livello di impilamento degli effetti di ombra è lo stesso dell'elemento stesso"
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

Questa proprietà accetta un elenco separato da virgole di effetti di ombra da applicare al testo dell'elemento. Gli effetti di ombra sono applicati nell'ordine specificato e possono quindi sovrapporsi tra loro, ma non sovrapporranno mai il testo stesso. Gli effetti di ombra non alterano le dimensioni di un box, ma possono estendersi oltre i suoi confini. Il [livello di impilamento](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) degli effetti di ombra è lo stesso dell'elemento stesso.

Ogni effetto di ombra deve specificare un offset di ombra e può opzionalmente specificare un raggio di sfocatura e un colore di ombra.

Un offset di ombra è specificato con due valori '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' che indicano la distanza dal testo. Il primo valore di lunghezza specifica la distanza orizzontale a destra del testo. Un valore di lunghezza orizzontale negativo posiziona l'ombra a sinistra del testo. Il secondo valore di lunghezza specifica la distanza verticale sotto il testo. Un valore di lunghezza verticale negativo posiziona l'ombra sopra il testo.

Un raggio di sfocatura può opzionalmente essere specificato dopo l'offset di ombra. Il raggio di sfocatura è un valore di lunghezza che indica i confini dell'effetto di sfocatura. L'algoritmo esatto per calcolare l'effetto di sfocatura non è specificato.

Un valore di colore può opzionalmente essere specificato prima o dopo i valori di lunghezza dell'effetto di ombra. Il valore di colore sarà usato come base per l'effetto di ombra. Se non viene specificato alcun colore, verrà usato il valore della proprietà ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) invece.

```java
public String TextShadow { get; set; }
```

### Valore di ritorno

proprietà text-shadow

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
