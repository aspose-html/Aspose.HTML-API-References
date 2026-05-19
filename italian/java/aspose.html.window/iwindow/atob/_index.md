---
title: "IWindow.Atob"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo IWindow. Prende i dati di input sotto forma di una Unicode String contenente dati binari codificati in base64, li decodifica e restituisce una String composta da caratteri nell'intervallo U0000‑U00FF, ciascuno rappresentante un byte binario con valori 0x00‑0xFF rispettivamente, corrispondenti a quei dati binari."
type: docs

url: /it/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Accetta i dati di input, sotto forma di stringa Unicode contenente dati binari codificati in base64, li decodifica e restituisce una stringa composta da caratteri nell'intervallo U+0000 a U+00FF, ciascuno dei quali rappresenta un byte binario con valori da 0x00 a 0xFF rispettivamente, corrispondenti a quei dati binari.

```java
public String Atob(String data)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | String | La Unicode String contenente dati binari codificati in base64 |

### Valore di ritorno

La String composta da caratteri nell'intervallo U+0000‑U+00FF

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Genera un'eccezione "InvalidCharacterError" DOMException se la String di input non è un dato base64 valido. |

### Vedi anche

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
