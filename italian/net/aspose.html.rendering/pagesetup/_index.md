---
title: Class PageSetup
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.PageSetup classe. Rappresenta un oggetto di configurazione della pagina utilizzato per il set di pagine di output della configurazione.
type: docs
weight: 4390
url: /it/net/aspose.html.rendering/pagesetup/
---
## PageSetup class

Rappresenta un oggetto di configurazione della pagina utilizzato per il set di pagine di output della configurazione.

```csharp
public class PageSetup
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdjustToWidestPage](../../aspose.html.rendering/pagesetup/adjusttowidestpage/) { get; set; } | Ottiene o imposta il flag che determina il caso in cui le dimensioni della pagina verranno adattate alla pagina più larga del documento. Questa opzione richiede molto tempo, quindi il tempo di elaborazione del documento può essere raddoppiato. La regolazione avverrà solo se la pagina più larga del documento è più larga della dimensione della pagina determinata in`PageSetup` . La dimensione della pagina modificata verrà utilizzata per tutte le pagine del documento. |
| [AnyPage](../../aspose.html.rendering/pagesetup/anypage/) { get; set; } | Ottiene o imposta la configurazione di tutte le pagine nella sequenza di pagine. |
| [AtPagePriority](../../aspose.html.rendering/pagesetup/atpagepriority/) { get; set; } | Ottiene o imposta[`AtPagePriority`](../atpagepriority/) che determinerà l'ordine di applicazione delle dichiarazioni sulle dimensioni della pagina. Per impostazione predefinita, le opzioni sovrascriveranno css`@pagina` regole . |
| [FirstPage](../../aspose.html.rendering/pagesetup/firstpage/) { get; set; } | Ottiene o imposta la configurazione della prima pagina. |
| [LeftPage](../../aspose.html.rendering/pagesetup/leftpage/) { get; } | Ottiene la configurazione della pagina dispari. |
| [PageLayoutOptions](../../aspose.html.rendering/pagesetup/pagelayoutoptions/) { get; set; } | Ottiene o imposta il[`PageLayoutOptions`](../pagelayoutoptions/) . Il valore predefinito èNone , qualsiasi altro valore sovrascriverà il[`AdjustToWidestPage`](./adjusttowidestpage/) comportamento. Funziona solo con documenti HTML. |
| [RightPage](../../aspose.html.rendering/pagesetup/rightpage/) { get; } | Ottiene la configurazione della pagina pari. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SetLeftRightPage](../../aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Imposta la configurazione della pagina sinistra/destra. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assemblea [Aspose.HTML](../../)


