---
title: "ICSS2Properties.Azimuth"
second_title: "Riferimento API Aspose.HTML per Java"
description: "proprietà ICSS2Properties. L'audio spaziale è una proprietà stilistica importante per la presentazione uditiva. Fornisce un modo naturale per distinguere diverse voci, poiché nella vita reale le persone raramente si trovano tutte nello stesso punto di una stanza."
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

angolo - La posizione è descritta in termini di un angolo nell'intervallo da '-360deg' a '360deg'. Il valore '0deg' indica direttamente davanti al centro del palco sonoro. '90deg' è a destra, '180deg' dietro, e '270deg' (o, in modo equivalente e più comodo, '-90deg') a sinistra.

lato-sinistro - Uguale a '270deg'. Con 'dietro', '270deg'.

estremamente a sinistra - Uguale a '300deg'. Con 'dietro', '240deg'.

sinistra - Uguale a '320deg'. Con 'dietro', '220deg'.

centro-sinistra - Uguale a '340deg'. Con 'dietro', '200deg'.

centro - Uguale a '0deg'. Con 'dietro', '180deg'.

centro-destra - Uguale a '20deg'. Con 'dietro', '160deg'.

destra - Uguale a '40deg'. Con 'dietro', '140deg'.

estremamente a destra - Uguale a '60deg'. Con 'dietro', '120deg'.

lato-destra - Uguale a '90deg'. Con 'dietro', '90deg'.

verso sinistra - Sposta il suono verso sinistra, rispetto all'angolo corrente. Più precisamente, sottrae 20 gradi. L'aritmetica è eseguita modulo 360 gradi. Nota che 'verso sinistra' è più accuratamente descritta come "girata in senso antiorario", poiché sottrae sempre 20 gradi, anche se l'azimuth ereditato è già dietro l'ascoltatore (in tal caso il suono sembra effettivamente spostarsi verso destra).

verso destra - Sposta il suono verso destra, rispetto all'angolo corrente. Più precisamente, aggiunge 20 gradi. Vedi 'verso sinistra' per l'aritmetica.

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
