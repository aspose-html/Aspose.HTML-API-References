---
title: OutputStream.Read
second_title: Aspose.HTML per riferimento API .NET
description: OutputStream metodo. Legge una sequenza di byte dal flusso di output avvolto e fa avanzare la posizione allinterno del flusso del numero di byte letti.
type: docs
weight: 100
url: /it/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

Legge una sequenza di byte dal flusso di output avvolto e fa avanzare la posizione all'interno del flusso del numero di byte letti.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | Byte[] | Una matrice di byte. Quando questo metodo viene restituito, il buffer contiene l'array di byte specificato con i valori compresi tra offset e (offset + count - 1) sostituiti da i byte letti dal flusso di output avvolto. |
| offset | Int32 | L'offset di byte in base zero nel buffer in corrispondenza del quale iniziare a memorizzare i dati read dal flusso di output sottoposto a wrapping. |
| count | Int32 | Il numero massimo di byte da leggere dal flusso di output sottoposto a wrapping. |

### Valore di ritorno

Il numero totale di byte letti nel buffer. Questo può essere inferiore al numero di byte richiesti se quel numero di byte non è attualmente disponibile o zero (0) se è stata raggiunta la fine del flusso.

### Guarda anche

* class [OutputStream](../)
* spazio dei nomi [Aspose.Html.IO](../../outputstream/)
* assemblea [Aspose.HTML](../../../)


