---
title: "PageLayoutOptions Enum"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.PageLayoutOptions enum. Specificeert vlaggen die samen met andere PageSetup-opties de afmetingen en lay-outs van pagina's bepalen. Deze vlaggen kunnen volgens hun beschrijvingen worden gecombineerd."
type: docs

url: /nl/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Specificeert vlaggen die samen met andere PageSetup-opties de afmetingen en lay-outs van pagina's bepalen. Deze vlaggen kunnen volgens hun beschrijvingen worden gecombineerd.

```java
[Flags]
public enum PageLayoutOptions
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Standaardwaarde die aangeeft dat de PageLayoutOptions de afmetingen en lay-outs van pagina's niet zullen beïnvloeden. |
| FitToContentWidth | `1` | Deze vlag geeft aan dat de breedte van de pagina's wordt bepaald door de grootte van de inhoud zelf, niet door de opgegeven paginabreedte. De breedte van de inhoud wordt afzonderlijk voor elke pagina berekend. |
| UseWidestPage | `2` | Wanneer gecombineerd met FitToContentWidth geeft dit aan dat de breedte van elke pagina gelijk zal zijn en gelijk zal zijn aan de breedste inhoudsgrootte van alle pagina's. |
| FitToWidestContentWidth | `3` | Deze vlag geeft aan dat de breedte van de pagina wordt bepaald door de grootte van de inhoud zelf, niet door de opgegeven paginabreedte. De breedte van elke pagina zal gelijk zijn en gelijk aan de breedste inhoudsgrootte van alle pagina's. |
| FitToContentHeight | `10` | Deze vlag geeft aan dat de hoogte van de pagina wordt bepaald door de grootte van de inhoud zelf, niet door de opgegeven paginahoogte. De volledige inhoud van het document wordt op één enkele pagina geplaatst als deze vlag is opgegeven. |
| ScaleToPageWidth | `100` | Deze vlag geeft aan dat de inhoud van het document wordt geschaald om op de pagina te passen waar het verschil tussen de beschikbare paginabreedte en de overlappende inhoud het grootst is. Deze botsen met de FitToContentWidth-vlag en als beide vlaggen zijn opgegeven, zal alleen ScaleToPageWidth effect hebben. |
| ScaleToPageHeight | `1000` | Deze vlag geeft aan dat de inhoud van het document wordt geschaald om te passen bij de hoogte van de eerste pagina. Deze botsen met de FitToContentHeight-vlag en als beide vlaggen zijn opgegeven, zal alleen ScaleToPageHeight effect hebben. De volledige documentinhoud wordt uitsluitend op één enkele pagina geplaatst. |

### Zie ook

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
