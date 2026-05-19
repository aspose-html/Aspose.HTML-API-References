---
title: "ICSS2Properties.Clear"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Proprietà ICSS2Properties. Questa proprietà indica quali lati delle box di un elemento non possono essere adiacenti a una box flottante precedente. Potrebbe essere che l'elemento stesso abbia discendenti flottanti la proprietà clear non ha effetto su di essi"
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Questa proprietà indica quali lati della/e box di un elemento non possono essere adiacenti a una box flottante precedente. (Potrebbe essere che l'elemento stesso abbia discendenti flottanti; la proprietà 'clear' non ha effetto su di essi.)

Questa proprietà può essere specificata solo per elementi di tipo blocco (inclusi i float). Per le box compatte e run‑in, questa proprietà si applica alla box blocco finale a cui appartiene la box compatta o run‑in.

I valori hanno i seguenti significati quando applicati a box di blocco non flottanti:

left - Il margine superiore della box generata è aumentato sufficientemente perché il bordo superiore sia al di sotto del bordo esterno inferiore di qualsiasi box flottante a sinistra generata da elementi precedenti nel documento sorgente.right - Il margine superiore della box generata è aumentato sufficientemente perché il bordo superiore sia al di sotto del bordo esterno inferiore di qualsiasi box flottante a destra generata da elementi precedenti nel documento sorgente.both - La box generata è spostata al di sotto di tutte le box flottanti degli elementi precedenti nel documento sorgente..none - Nessuna restrizione sulla posizione della box rispetto ai float.

```java
public String Clear { get; set; }
```

### Valore di ritorno

proprietà clear

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
