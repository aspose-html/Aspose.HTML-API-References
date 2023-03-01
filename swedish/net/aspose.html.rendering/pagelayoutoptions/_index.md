---
title: Enum PageLayoutOptions
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Rendering.PageLayoutOptions uppräkning. Anger flaggor som tillsammans med andra PageSetupalternativ bestämmer storlek och layout på sidor. Dessa flaggor kan kombineras enligt deras beskrivningar.
type: docs
weight: 4380
url: /sv/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Anger flaggor som tillsammans med andra PageSetup-alternativ bestämmer storlek och layout på sidor. Dessa flaggor kan kombineras enligt deras beskrivningar.

```csharp
[Flags]
public enum PageLayoutOptions
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Standardvärde som anger att PageLayoutOptions inte kommer att påverka sidornas storlekar och layouter. |
| FitToContentWidth | `1` | Den här flaggan indikerar att sidornas bredd bestäms utifrån själva innehållsstorleken, inte från den angivna sidbredden. Innehållets bredd beräknas individuellt för varje sida. |
| UseWidestPage | `2` | I kombination medFitToContentWidth indikerar att bredden på varje sida kommer att vara densamma och kommer att vara lika med den bredaste innehållsstorleken bland alla sidor. |
| FitToWidestContentWidth | `3` | Den här flaggan anger att sidans bredd bestäms utifrån själva innehållsstorleken, inte från den angivna sidbredden. Bredden på varje sida kommer att vara densamma och kommer att vara lika med den bredaste innehållsstorleken bland alla sidor. |
| FitToContentHeight | `10` | Den här flaggan indikerar att sidans höjd bestäms utifrån själva innehållsstorleken, inte från den angivna sidhöjden. Allt dokumentinnehåll kommer att finnas på en enda sida om denna flagga anges. |
| ScaleToPageWidth | `100` | Den här flaggan indikerar att innehållet i dokumentet kommer att skalas för att passa den sida där skillnaden mellan den tillgängliga sidbredden och det överlappande innehållet är störst. Den kolliderar medFitToContentWidth flagga och om endast båda flaggorna angesScaleToPageWidth kommer att träda i kraft. |
| ScaleToPageHeight | `1000` | Denna flagga indikerar att innehållet i dokumentet kommer att skalas för att passa höjden på den första sidan. Den kolliderar medFitToContentHeight flagga och om endast båda flaggorna angesScaleToPageHeight kommer att träda i kraft. Allt dokumentinnehåll kommer endast att placeras på en enda sida. |

### Se även

* namnutrymme [Aspose.Html.Rendering](../../aspose.html.rendering/)
* hopsättning [Aspose.HTML](../../)


