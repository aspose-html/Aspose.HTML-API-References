---
title: "Interfaccia IBlob"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.io.IBlob. Un oggetto Blob si riferisce a una sequenza di byte e ha un attributo size che è il numero totale di byte nella sequenza e un attributo type che è una String codificata ASCII in minuscolo che rappresenta il tipo media della sequenza di byte."
type: docs

url: /it/java/com.aspose.html.io/iblob/
---
## IBlob interface

Un oggetto Blob si riferisce a una sequenza di byte e possiede un attributo size che è il numero totale di byte nella sequenza, e un attributo type, che è una stringa codificata ASCII in minuscolo che rappresenta il tipo media della sequenza di byte.

```java
public interface IBlob
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) Restituisce la dimensione della sequenza di byte in numero di byte. Al recupero, gli user agent conformi devono restituire il numero totale di byte che possono essere letti da un oggetto FileReader o FileReaderSync, o 0 se il Blob non ha byte da leggere. |
| [getType](../../com.aspose.html.io/iblob/type/) La String codificata ASCII in minuscolo che rappresenta il tipo media del Blob. Al recupero, gli user agent devono restituire il tipo di un Blob come una String codificata ASCII in minuscolo, in modo che quando viene convertita in una sequenza di byte, sia un tipo MIME analizzabile, o la String vuota – 0 byte – se il tipo non può essere determinato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | Restituisce un nuovo oggetto Blob con byte che vanno dal parametro opzionale start fino, ma non includendo, il parametro opzionale end, e con un attributo type il cui valore è quello del parametro opzionale contentType. |

### Vedi anche

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
