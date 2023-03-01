---
title: Class PageSetup
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Rendering.PageSetup klass. Representerar ett siduppsättningsobjekt som används för konfigurationsutdata.
type: docs
weight: 4390
url: /sv/net/aspose.html.rendering/pagesetup/
---
## PageSetup class

Representerar ett siduppsättningsobjekt som används för konfigurationsutdata.

```csharp
public class PageSetup
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AdjustToWidestPage](../../aspose.html.rendering/pagesetup/adjusttowidestpage/) { get; set; } | Hämtar eller ställer in flagga som avgör fallet när sidstorleken kommer att justeras till den bredaste sidan i dokumentet. Detta alternativ är tidskrävande så tiden för dokumentbearbetning kan ökas med två gånger. Justering kommer att ske endast om den bredaste sidan i dokumentet är bredare än sidstorleken som fastställts i`PageSetup` . Adjusted sidstorlek kommer att användas för alla sidor i dokumentet. |
| [AnyPage](../../aspose.html.rendering/pagesetup/anypage/) { get; set; } | Hämtar eller ställer in alla sidkonfigurationer i sidsekvensen. |
| [AtPagePriority](../../aspose.html.rendering/pagesetup/atpagepriority/) { get; set; } | Hämtar eller sätter[`AtPagePriority`](../atpagepriority/) som kommer att avgöra ordningen för tillämpning av sidstorleksdeklarationer. Som standard kommer alternativen att åsidosätta css`@sida` regler . |
| [FirstPage](../../aspose.html.rendering/pagesetup/firstpage/) { get; set; } | Hämtar eller ställer in den första sidkonfigurationen. |
| [LeftPage](../../aspose.html.rendering/pagesetup/leftpage/) { get; } | Får konfigurationen Udda sida. |
| [PageLayoutOptions](../../aspose.html.rendering/pagesetup/pagelayoutoptions/) { get; set; } | Hämtar eller ställer in[`PageLayoutOptions`](../pagelayoutoptions/) . Standardvärdet ärNone , kommer alla andra värden att åsidosätta[`AdjustToWidestPage`](./adjusttowidestpage/) beteende. Fungerar endast med HTML-dokument. |
| [RightPage](../../aspose.html.rendering/pagesetup/rightpage/) { get; } | Får jämn sida-konfigurationen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [SetLeftRightPage](../../aspose.html.rendering/pagesetup/setleftrightpage/)(Page, Page) | Ställer in konfigurationen för vänster/höger sida. |

### Se även

* namnutrymme [Aspose.Html.Rendering](../../aspose.html.rendering/)
* hopsättning [Aspose.HTML](../../)


