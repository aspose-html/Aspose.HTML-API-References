---
title: Interface IMediaList
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Css.IMediaList gränssnitt. MediaListgränssnittet tillhandahåller abstraktionen av en ordnad samling av media utan att definiera eller begränsa hur denna samling implementeras. En tom lista är detsamma som en lista som innehåller mediet all.
type: docs
weight: 580
url: /sv/net/aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList-gränssnittet tillhandahåller abstraktionen av en ordnad samling av media, utan att definiera eller begränsa hur denna samling implementeras. En tom lista är detsamma som en lista som innehåller mediet "all".

```csharp
public interface IMediaList : IEnumerable<string>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.html.dom.css/imedialist/item/) { get; } | Returnerar index i listan. Om index är större än eller lika med antalet media i listan, returnerar detta null. Medieindex. |
| [Length](../../aspose.html.dom.css/imedialist/length/) { get; } | Antalet media i listan. Omfattningen av giltiga media är 0 till längd-1 inklusive. |
| [MediaText](../../aspose.html.dom.css/imedialist/mediatext/) { get; } | Den tolkbara textrepresentationen av medialistan. Detta är en kommaseparerad lista över media. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AppendMedium](../../aspose.html.dom.css/imedialist/appendmedium/)(string) | Lägger till mediet newMedium i slutet av listan. Om det nya mediet redan används tas det först bort. |
| [DeleteMedium](../../aspose.html.dom.css/imedialist/deletemedium/)(string) | Tar bort mediet som indikeras av oldMedium från listan. |

### Se även

* namnutrymme [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* hopsättning [Aspose.HTML](../../)


