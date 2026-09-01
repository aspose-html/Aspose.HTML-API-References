---
title: "Enum PageLayoutOptions"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.rendering.PageLayoutOptions enum. Specifica i flag che, insieme ad altre opzioni PageSetup, determinano le dimensioni e i layout delle pagine. Questi flag possono essere combinati secondo le loro descrizioni"
type: docs

url: /it/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Specifica i flag che, insieme ad altre opzioni PageSetup, determinano le dimensioni e i layout delle pagine. Questi flag possono essere combinati secondo le loro descrizioni.

```java
[Flags]
public enum PageLayoutOptions
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Valore predefinito che indica che il PageLayoutOptions non influenzerà le dimensioni e i layout delle pagine. |
| FitToContentWidth | `1` | Questo flag indica che la larghezza delle pagine è determinata dalla dimensione del contenuto stesso, non dalla larghezza della pagina specificata. La larghezza del contenuto è calcolata individualmente per ogni pagina. |
| UseWidestPage | `2` | Quando combinato con FitToContentWidth indica che la larghezza di ogni pagina sarà la stessa e sarà pari alla dimensione di contenuto più ampia tra tutte le pagine. |
| FitToWidestContentWidth | `3` | Questo flag indica che la larghezza della pagina è determinata dalla dimensione del contenuto stesso, non dalla larghezza della pagina specificata. La larghezza di ogni pagina sarà la stessa e sarà pari alla dimensione di contenuto più ampia tra tutte le pagine. |
| FitToContentHeight | `10` | Questo flag indica che l'altezza della pagina è determinata dalla dimensione del contenuto stesso, non dall'altezza della pagina specificata. Tutto il contenuto dei documenti sarà collocato su un'unica pagina se questo flag è specificato. |
| ScaleToPageWidth | `100` | Questo flag indica che il contenuto del documento sarà scalato per adattarsi alla pagina dove la differenza tra la larghezza della pagina disponibile e il contenuto sovrapposto è maggiore. È in conflitto con il flag FitToContentWidth e, se entrambi i flag sono specificati, solo ScaleToPageWidth avrà effetto. |
| ScaleToPageHeight | `1000` | Questo flag indica che il contenuto del documento sarà scalato per adattarsi all'altezza della prima pagina. È in conflitto con il flag FitToContentHeight e, se entrambi i flag sono specificati, solo ScaleToPageHeight avrà effetto. Tutto il contenuto del documento sarà posizionato su un'unica pagina. |

### Vedi anche

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
