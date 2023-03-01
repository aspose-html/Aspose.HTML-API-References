---
title: Interface IMediaList
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Css.IMediaList interfaccia. Linterfaccia MediaList fornisce lastrazione di una raccolta ordinata di media senza definire o limitare il modo in cui questa raccolta viene implementata. Una lista vuota è uguale a una lista che contiene il mezzo all.
type: docs
weight: 580
url: /it/net/aspose.html.dom.css/imedialist/
---
## IMediaList interface

L'interfaccia MediaList fornisce l'astrazione di una raccolta ordinata di media, senza definire o limitare il modo in cui questa raccolta viene implementata. Una lista vuota è uguale a una lista che contiene il mezzo "all".

```csharp
public interface IMediaList : IEnumerable<string>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Item](../../aspose.html.dom.css/imedialist/item/) { get; } | Restituisce l'indice nell'elenco. Se index è maggiore o uguale al numero di media nell'elenco, restituisce null. L'indice multimediale. |
| [Length](../../aspose.html.dom.css/imedialist/length/) { get; } | Il numero di supporti nell'elenco. L'intervallo di supporti validi va da 0 a length-1 incluso. |
| [MediaText](../../aspose.html.dom.css/imedialist/mediatext/) { get; } | La rappresentazione testuale analizzabile dell'elenco multimediale. Questo è un elenco di contenuti multimediali separati da virgole. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AppendMedium](../../aspose.html.dom.css/imedialist/appendmedium/)(string) | Aggiunge il mezzo newMedium alla fine dell'elenco. Se il nuovo mezzo è già utilizzato, viene prima rimosso. |
| [DeleteMedium](../../aspose.html.dom.css/imedialist/deletemedium/)(string) | Elimina dall'elenco il supporto indicato da oldMedium. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assemblea [Aspose.HTML](../../)


