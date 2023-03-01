---
title: Enum MarkdownFeatures
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Saving.MarkdownFeatures uppräkning. AMarkdownFeatures flagguppsättning är en uppsättning av noll eller fler av följande flaggor som används för att välja element som konverterats till markdown.
type: docs
weight: 4620
url: /sv/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

A`MarkdownFeatures` flagguppsättning är en uppsättning av noll eller fler av följande flaggor, som används för att välja element som konverterats till markdown.

```csharp
[Flags]
public enum MarkdownFeatures
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| InlineHTML | `1` | Den här flaggan möjliggör inlining av HTML-element. Om denna flagga är inställd än blocknivåelement (som t.ex`div` ) vems`prissänkning` attributvärdet är lika med`i kö` kommer att infogas i den resulterande markdown. |
| AutomaticParagraph | `2` | Denna flagga möjliggör konvertering av`paragraf` element. Innehållet i sådana element kommer att placeras på separata rader, så markdownhanterare kommer att slå in det. |
| Header | `4` | Denna flagga möjliggör konvertering av`rubrik` elements. |
| Blockquote | `8` | Denna flagga möjliggör konvertering av`Block citat` elements. |
| List | `10` | Denna flagga möjliggör konvertering av`lista` elements. |
| CodeBlock | `20` | Denna flagga möjliggör konvertering av kodblock. Kodblocket består av 2 element`pre` och`koda` , innehållet i en sådan konstruktion är processer "som är". |
| HorizontalRule | `40` | Denna flagga möjliggör konvertering av`horisontella regler` . |
| Link | `80` | Denna flagga möjliggör konvertering av`a` elements. |
| Emphasis | `100` | Denna flagga möjliggör konvertering av`betoning` elements. |
| InlineCode | `200` | Denna flagga möjliggör konvertering av`koda` elements. |
| Image | `400` | Denna flagga möjliggör konvertering av`img` elements. |
| LineBreak | `800` | Denna flagga möjliggör konvertering av`br` elements. |
| Video | `1000` | Denna flagga möjliggör konvertering av`video` elements. |
| Table | `2000` | Denna flagga möjliggör konvertering av`tabell` elements. |
| TaskList | `4000` | Denna flagga möjliggör konvertering av uppgiftslistor. Uppgiftslistan består av`inmatning` element, som måste vara det första barnet till`lista` element och vems`typ` attributvärdet ska vara lika`kryssruta` . |
| Strikethrough | `8000` | Denna flagga möjliggör konvertering av`del` elements. |
| Strong | `10000` | Denna flagga möjliggör konvertering av`stark` elements. |

### Se även

* namnutrymme [Aspose.Html.Saving](../../aspose.html.saving/)
* hopsättning [Aspose.HTML](../../)


