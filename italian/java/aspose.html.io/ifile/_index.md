---
title: "Interfaccia IFile"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.io.IFile. Un oggetto File è un oggetto Blob con un attributo name che è una String; può essere creato all'interno dell'applicazione web tramite un costruttore o è un riferimento a una sequenza di byte da un file del file system del sistema operativo sottostante."
type: docs

url: /it/java/com.aspose.html.io/ifile/
---
## IFile interface

Un oggetto File è un oggetto Blob con un attributo name, che è una stringa; può essere creato all'interno dell'applicazione web tramite un costruttore, oppure è un riferimento a una sequenza di byte da un file del file system sottostante (OS).

```java
public interface IFile : IBlob
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) La data dell'ultima modifica del file. Al recupero, se gli user agent possono rendere disponibile questa informazione, questo deve restituire un valore long long impostato al momento in cui il file è stato modificato, espresso in millisecondi dal Unix Epoch. |
| [getName](../../com.aspose.html.io/ifile/name/) Il nome del file. Al recupero, questo deve restituire il nome del file come una String. |

### Vedi anche

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
