---
title: Enum PageLayoutOptions
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Rendering.PageLayoutOptions opsomming. Specificeert markeringen die samen met andere PageSetupopties de grootte en layout van paginas bepalen. Deze markeringen kunnen worden gecombineerd volgens hun beschrijvingen.
type: docs
weight: 4380
url: /nl/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

Specificeert markeringen die samen met andere PageSetup-opties de grootte en lay-out van pagina's bepalen. Deze markeringen kunnen worden gecombineerd volgens hun beschrijvingen.

```csharp
[Flags]
public enum PageLayoutOptions
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | Standaardwaarde die aangeeft dat PageLayoutOptions geen invloed heeft op de formaten en lay-outs van pagina's. |
| FitToContentWidth | `1` | Deze vlag geeft aan dat de breedte van de pagina's wordt bepaald op basis van de inhoudsgrootte zelf, niet op basis van de opgegeven paginabreedte. De breedte van de inhoud wordt voor elke pagina afzonderlijk berekend. |
| UseWidestPage | `2` | In combinatie metFitToContentWidth geeft aan dat de breedte van elke pagina hetzelfde zal zijn en gelijk zal zijn aan de breedste inhoudsgrootte van alle pagina's. |
| FitToWidestContentWidth | `3` | Deze vlag geeft aan dat de breedte van de pagina wordt bepaald door de inhoudsgrootte zelf, niet door de opgegeven paginabreedte. De breedte van elke pagina is hetzelfde en is gelijk aan de breedste inhoudsgrootte van alle pagina's. |
| FitToContentHeight | `10` | Deze vlag geeft aan dat de hoogte van de pagina wordt bepaald op basis van de inhoudsgrootte zelf, niet op basis van de opgegeven paginahoogte. Alle inhoud van het document bevindt zich op de enkele pagina als deze vlag is opgegeven. |
| ScaleToPageWidth | `100` | Deze vlag geeft aan dat de inhoud van het document wordt geschaald om te passen op de pagina waar het verschil tussen de beschikbare paginabreedte en de overlappende inhoud het grootst is. Het botst metFitToContentWidth vlag en alleen als beide vlaggen zijn opgegevenScaleToPageWidth zal effect hebben. |
| ScaleToPageHeight | `1000` | Deze vlag geeft aan dat de inhoud van het document wordt geschaald om te passen op de hoogte van de eerste pagina. Het botst metFitToContentHeight vlag en alleen als beide vlaggen zijn opgegevenScaleToPageHeight wordt van kracht. Alle documentinhoud wordt alleen op de enkele pagina geplaatst. |

### Zie ook

* naamruimte [Aspose.Html.Rendering](../../aspose.html.rendering/)
* montage [Aspose.HTML](../../)


