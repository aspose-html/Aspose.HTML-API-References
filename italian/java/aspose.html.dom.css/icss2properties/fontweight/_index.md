---
title: "ICSS2Properties.FontWeight"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà ICSS2Properties. La proprietà font-weight specifica lo spessore del carattere. I valori hanno i seguenti significati"
type: docs

url: /it/java/com.aspose.html.dom.css/icss2properties/fontweight/
---
## ICSS2Properties.FontWeight property

La proprietà 'font-weight' specifica lo spessore del carattere. I valori hanno i seguenti significati:

100 a 900 - Questi valori formano una sequenza ordinata, dove ogni numero indica uno spessore almeno così scuro come il suo predecessore. normal - Stesso di '400'. bold - Stesso di '700'. bolder - Specifica il prossimo spessore assegnato a un carattere più scuro di quello ereditato. Se non esiste tale spessore, si ottiene semplicemente il valore numerico più scuro successivo (e il carattere rimane invariato), a meno che il valore ereditato fosse '900', nel qual caso lo spessore risultante è anch'esso '900'. lighter - Specifica il prossimo spessore assegnato a un carattere più chiaro di quello ereditato. Se non esiste tale spessore, si ottiene semplicemente il valore numerico più chiaro successivo (e il carattere rimane invariato), a meno che il valore ereditato fosse '100', nel qual caso lo spessore risultante è anch'esso '100'.

```java
public String FontWeight { get; set; }
```

### Valore di ritorno

proprietà font-weight

### Vedi anche

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
