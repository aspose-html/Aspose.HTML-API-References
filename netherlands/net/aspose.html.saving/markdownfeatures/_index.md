---
title: Enum MarkdownFeatures
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Saving.MarkdownFeatures opsomming. EENMarkdownFeatures vlaggenset is een set van nul of meer van de volgende vlaggen die worden gebruikt om elementen te selecteren die zijn geconverteerd naar prijsverlaging.
type: docs
weight: 4620
url: /nl/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

EEN`MarkdownFeatures` vlaggenset is een set van nul of meer van de volgende vlaggen, die worden gebruikt om elementen te selecteren die zijn geconverteerd naar prijsverlaging.

```csharp
[Flags]
public enum MarkdownFeatures
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| InlineHTML | `1` | Deze vlag maakt inlining van HTML-elementen mogelijk. Als deze vlag is ingesteld, dan worden elementen op blokniveau (zoals`div` ) van wie`korting` attribuutwaarde is gelijk aan`in lijn` wordt ingevoegd in de resulterende prijsverlaging. |
| AutomaticParagraph | `2` | Deze vlag maakt conversie mogelijk van`paragraaf` elementen. De inhoud van dergelijke elementen wordt op afzonderlijke regels geplaatst, dus markdown-handlers zullen deze omwikkelen. |
| Header | `4` | Deze vlag maakt conversie mogelijk van`koptekst` elementen. |
| Blockquote | `8` | Deze vlag maakt conversie mogelijk van`blokcitaat` elementen. |
| List | `10` | Deze vlag maakt conversie mogelijk van`lijst` elementen. |
| CodeBlock | `20` | Deze vlag maakt conversie van codeblokken mogelijk. Codeblok bestaat uit 2 elementen`pre` En`code` , inhoud van een dergelijke constructie is processen "zoals ze zijn". |
| HorizontalRule | `40` | Deze vlag maakt conversie mogelijk van`horizontale regels` . |
| Link | `80` | Deze vlag maakt conversie mogelijk van`A` elementen. |
| Emphasis | `100` | Deze vlag maakt conversie mogelijk van`nadruk` elementen. |
| InlineCode | `200` | Deze vlag maakt conversie mogelijk van`code` elementen. |
| Image | `400` | Deze vlag maakt conversie mogelijk van`img` elementen. |
| LineBreak | `800` | Deze vlag maakt conversie mogelijk van`br` elementen. |
| Video | `1000` | Deze vlag maakt conversie mogelijk van`video` elementen. |
| Table | `2000` | Deze vlag maakt conversie mogelijk van`tafel` elementen. |
| TaskList | `4000` | Deze vlag maakt conversie van takenlijsten mogelijk. Takenlijst bestaat uit`invoer` element, dat het eerste kind moet zijn van`lijst` element en van wie`type` attribuutwaarde moet gelijk zijn`selectievakje` . |
| Strikethrough | `8000` | Deze vlag maakt conversie mogelijk van`del` elementen. |
| Strong | `10000` | Deze vlag maakt conversie mogelijk van`sterk` elementen. |

### Zie ook

* naamruimte [Aspose.Html.Saving](../../aspose.html.saving/)
* montage [Aspose.HTML](../../)


