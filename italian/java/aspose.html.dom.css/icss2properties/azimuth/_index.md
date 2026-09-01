---
title: "ICSS2Properties.Azimuth"
second_title: "Aspose.HTML per Java Riferimento API"
description: "ICSS2Properties property. L'audio spaziale è una proprietà stilistica importante per la presentazione uditiva. Fornisce un modo naturale per distinguere diverse voci, poiché nella vita reale le persone raramente si trovano tutte nello stesso punto di una stanza."
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

L'audio spaziale è una proprietà stilistica importante per la presentazione uditiva. Fornisce un modo naturale per distinguere diverse voci, come nella vita reale (le persone raramente si trovano tutte nello stesso punto di una stanza).

```java
public String Azimuth { get; set; }
```

### Valore di ritorno

La proprietà azimuth

### Property Value

I valori hanno i seguenti significati:

angle - La posizione è descritta in termini di angolo nell'intervallo da '-360deg' a '360deg'. Il valore '0deg' indica direttamente davanti al centro del palco sonoro. '90deg' è a destra, '180deg' dietro, e '270deg' (oppure, in modo equivalente e più comodo, '-90deg') a sinistra.

left-side - Identico a '270deg'. Con 'behind', '270deg'.

far-left - Identico a '300deg'. Con 'behind', '240deg'.

left - Identico a '320deg'. Con 'behind', '220deg'.

center-left - Identico a '340deg'. Con 'behind', '200deg'.

center - Identico a '0deg'. Con 'behind', '180deg'.

center-right - Identico a '20deg'. Con 'behind', '160deg'.

right - Identico a '40deg'. Con 'behind', '140deg'.

far-right - Identico a '60deg'. Con 'behind', '120deg'.

right-side - Identico a '90deg'. Con 'behind', '90deg'.

leftwards - Sposta il suono verso sinistra, rispetto all'angolo corrente. Più precisamente, sottrae 20 gradi. L'aritmetica è eseguita modulo 360 gradi. Nota che 'leftwards' è più accuratamente descritto come \"girato in senso antiorario\", poiché sottrae sempre 20 gradi, anche se l'azimuth ereditato è già dietro l'ascoltatore (in tal caso il suono sembra effettivamente spostarsi verso destra).

rightwards - Sposta il suono verso destra, rispetto all'angolo corrente. Più precisamente, aggiunge 20 gradi. Vedi 'leftwards' per l'aritmetica.

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
