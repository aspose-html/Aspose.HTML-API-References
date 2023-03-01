---
title: Class OutputStream
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.IO.OutputStream classe. Un flusso surrogato esegue il wrapping del flusso di output reale e ne controlla laccesso. OutputStream contiene dati URI che descrivono la posizione del flusso di output.
type: docs
weight: 3750
url: /it/net/aspose.html.io/outputstream/
---
## OutputStream class

Un flusso surrogato esegue il wrapping del flusso di output reale e ne controlla l'accesso. `OutputStream` contiene dati URI che descrivono la posizione del flusso di output.

```csharp
public class OutputStream : Stream
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | Inizializza una nuova istanza di`OutputStream` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | Ottiene un valore che indica se il flusso di output sottoposto a wrapping supporta la lettura. |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | Ottiene un valore che indica se il flusso di output sottoposto a wrapping supporta la ricerca. |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | Ottiene un valore che indica se il flusso di output sottoposto a wrapping supporta la scrittura. |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | Ottiene la lunghezza in byte del flusso di output avvolto. |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | Ottiene o imposta la posizione all'interno del flusso di output avvolto. |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | Ottiene l'URI della posizione del flusso. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | Chiude il flusso di output avvolto e il flusso corrente. |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | Cancella tutti i buffer per il flusso di output avvolto e fa sì che tutti i dati memorizzati nel buffer vengano scritti nel dispositivo sottostante. |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | Legge una sequenza di byte dal flusso di output avvolto e fa avanzare la posizione all'interno del flusso del numero di byte letti. |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | Imposta la posizione all'interno del flusso di output avvolto. |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | Imposta la lunghezza del flusso di output avvolto. |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | Scrive una sequenza di byte nel flusso output avvolto e fa avanzare la posizione corrente all'interno di questo flusso del numero di byte scritti. |

### Guarda anche

* spazio dei nomi [Aspose.Html.IO](../../aspose.html.io/)
* assemblea [Aspose.HTML](../../)


