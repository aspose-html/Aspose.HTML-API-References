---
title: "IWindow.Btoa"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo IWindow. Prende i dati di input sotto forma di una Unicode String contenente solo caratteri nell'intervallo U0000 a U00FF, ciascuno rappresentante un byte binario con valori 0x00 a 0xFF rispettivamente, e lo converte nella sua rappresentazione base64 che restituisce."
type: docs

url: /it/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Accetta i dati di input, sotto forma di stringa Unicode contenente solo caratteri nell'intervallo U+0000 a U+00FF, ciascuno rappresentante un byte binario con valori da 0x00 a 0xFF rispettivamente, e li converte nella loro rappresentazione base64, che restituisce.

```java
public String Btoa(String data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | String | La Unicode String contenente solo caratteri nell'intervallo U+0000‑U+00FF. |

### Valore di ritorno

La stringa base64.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Lancia un'eccezione DOMException "InvalidCharacterError" se la String di input contiene caratteri fuori dall'intervallo. |

### Vedi anche

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
