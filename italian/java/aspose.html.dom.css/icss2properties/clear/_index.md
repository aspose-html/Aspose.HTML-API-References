---
title: "ICSS2Properties.Clear"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà ICSS2Properties. Questa proprietà indica quali lati delle caselle di un elemento non possono essere adiacenti a una casella flottante precedente. Potrebbe accadere che l'elemento stesso abbia discendenti flottanti; la proprietà clear non ha effetto su di essi"
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Questa proprietà indica quali lati della/e casella/e di un elemento non possono essere adiacenti a una casella flottante precedente. (Potrebbe accadere che l'elemento stesso abbia discendenti flottanti; la proprietà 'clear' non ha effetto su di essi.)

Questa proprietà può essere specificata solo per elementi di tipo blocco (inclusi i float). Per le caselle compatte e run-in, questa proprietà si applica alla casella di blocco finale a cui appartiene la casella compatta o run-in.

I valori hanno i seguenti significati quando applicati a caselle di blocco non flottanti:

left - Il margine superiore della casella generata è aumentato sufficientemente perché il bordo superiore sia al di sotto del bordo esterno inferiore di tutte le caselle flottanti a sinistra generate da elementi precedenti nel documento sorgente. right - Il margine superiore della casella generata è aumentato sufficientemente perché il bordo superiore sia al di sotto del bordo esterno inferiore di tutte le caselle flottanti a destra generate da elementi precedenti nel documento sorgente. both - La casella generata è spostata al di sotto di tutte le caselle flottanti degli elementi precedenti nel documento sorgente. none - Nessuna restrizione sulla posizione della casella rispetto ai float.

```java
public String Clear { get; set; }
```

### Valore di ritorno

proprietà clear

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
