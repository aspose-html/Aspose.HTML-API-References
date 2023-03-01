---
title: Enum PageLayoutOptions
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.PageLayoutOptions enum. Specifica i flag che insieme ad altre opzioni di PageSetup determinano le dimensioni e il layout delle pagine. Questi flag possono essere combinati insieme in base alle loro descrizioni.
type: docs
weight: 4380
url: /it/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Specifica i flag che insieme ad altre opzioni di PageSetup determinano le dimensioni e il layout delle pagine. Questi flag possono essere combinati insieme in base alle loro descrizioni.

```csharp
[Flags]
public enum PageLayoutOptions
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Valore predefinito che indica che PageLayoutOptions non influirà sulle dimensioni e sui layout delle pagine. |
| FitToContentWidth | `1` | Questo flag indica che la larghezza delle pagine è determinata dalla dimensione del contenuto stesso, non dalla larghezza della pagina specificata. La larghezza del contenuto viene calcolata individualmente per ogni pagina. |
| UseWidestPage | `2` | Quando combinato conFitToContentWidth indica che la larghezza di ogni pagina sarà la stessa e sarà uguale alla dimensione del contenuto più ampia tra tutte le pagine. |
| FitToWidestContentWidth | `3` | Questo flag indica che la larghezza della pagina è determinata dalla dimensione del contenuto stesso, non dalla larghezza della pagina specificata. La larghezza di ogni pagina sarà la stessa e sarà uguale alla dimensione del contenuto più ampia tra tutte le pagine. |
| FitToContentHeight | `10` | Questo flag indica che l'altezza della pagina è determinata dalla dimensione del contenuto stesso, non dall'altezza della pagina specificata. Se questo flag è specificato, tutto il contenuto dei documenti sarà posizionato sulla singola pagina. |
| ScaleToPageWidth | `100` | Questo flag indica che il contenuto del documento verrà ridimensionato per adattarsi alla pagina in cui la differenza tra la larghezza della pagina disponibile e il contenuto sovrapposto è maggiore. Si scontra conFitToContentWidth flag e solo se entrambi i flag sono specificatiScaleToPageWidth avrà effetto. |
| ScaleToPageHeight | `1000` | Questo flag indica che il contenuto del documento verrà ridimensionato per adattarsi all'altezza della prima pagina. Si scontra conFitToContentHeight flag e solo se entrambi i flag sono specificatiScaleToPageHeight avrà effetto. Tutto il contenuto del documento verrà posizionato solo sulla singola pagina. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assemblea [Aspose.HTML](../../)


