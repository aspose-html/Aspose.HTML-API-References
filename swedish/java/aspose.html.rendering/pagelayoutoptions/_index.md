---
title: "PageLayoutOptions enum"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.PageLayoutOptions enum. Anger flaggor som tillsammans med andra PageSetup-alternativ bestämmer storlekar och layouter för sidor. Dessa flaggor kan kombineras enligt deras beskrivningar"
type: docs

url: /sv/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Anger flaggor som tillsammans med andra PageSetup‑alternativ bestämmer sidors storlekar och layouter. Dessa flaggor kan kombineras enligt deras beskrivningar.

```java
[Flags]
public enum PageLayoutOptions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Standardvärde som indikerar att PageLayoutOptions inte kommer att påverka storlekar och layouter för sidor. |
| FitToContentWidth | `1` | Denna flagga indikerar att sidbredden bestäms av innehållsstorleken själv, inte av den angivna sidbredden. Bredden på innehållet beräknas individuellt för varje sida. |
| UseWidestPage | `2` | När den kombineras med FitToContentWidth indikerar den att bredden på varje sida blir densamma och lika med den bredaste innehållsstorleken bland alla sidor. |
| FitToWidestContentWidth | `3` | Denna flagga indikerar att sidbredden bestäms av innehållsstorleken själv, inte av den angivna sidbredden. Bredden på varje sida blir densamma och lika med den bredaste innehållsstorleken bland alla sidor. |
| FitToContentHeight | `10` | Denna flagga indikerar att sidhöjden bestäms av innehållsstorleken själv, inte av den angivna sidhöjden. Allt dokumentinnehåll kommer att placeras på en enda sida om denna flagga anges. |
| ScaleToPageWidth | `100` | Denna flagga indikerar att dokumentets innehåll skalas för att passa sidan där skillnaden mellan tillgänglig sidbredd och överlappande innehåll är störst. Den kolliderar med flaggan FitToContentWidth och om båda flaggorna anges kommer endast ScaleToPageWidth att ha effekt. |
| ScaleToPageHeight | `1000` | Denna flagga indikerar att dokumentets innehåll skalas för att passa höjden på den första sidan. Den kolliderar med flaggan FitToContentHeight och om båda flaggorna anges kommer endast ScaleToPageHeight att ha effekt. Allt dokumentinnehåll kommer endast att placeras på en enda sida. |

### Se även

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
