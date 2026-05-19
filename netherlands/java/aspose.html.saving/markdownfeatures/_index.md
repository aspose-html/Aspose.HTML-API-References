---
title: "MarkdownFeatures enum"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.MarkdownFeatures enum. Een MarkdownFeatures‑vlagset is een verzameling van nul of meer van de volgende vlaggen die worden gebruikt om elementen te selecteren die naar markdown worden geconverteerd."
type: docs

url: /nl/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

Een `MarkdownFeatures` vlagset is een verzameling van nul of meer van de volgende vlaggen, die worden gebruikt om elementen te selecteren die naar markdown worden geconverteerd.

```java
[Flags]
public enum MarkdownFeatures
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| InlineHTML | `1` | Deze vlag schakelt het inline plaatsen van HTML‑elementen in. Als deze vlag is ingesteld, worden blok‑niveau‑elementen (zoals `div`) waarvan de `markdown`‑attribuutwaarde gelijk is aan `inline` in de resulterende markdown ingevoegd. |
| AutomaticParagraph | `2` | Deze vlag schakelt de conversie van `paragraph`‑elementen in. De inhoud van dergelijke elementen wordt op afzonderlijke regels geplaatst, zodat markdown‑handlers het zullen omwikkelen. |
| Header | `4` | Deze vlag schakelt de conversie van `header`‑elementen in. |
| Blockquote | `8` | Deze vlag schakelt de conversie van `blockquote`‑elementen in. |
| List | `10` | Deze vlag schakelt de conversie van `list`‑elementen in. |
| CodeBlock | `20` | Deze vlag schakelt de conversie van codeblokken in. Een codeblok bestaat uit 2 elementen `pre` en `code`, de inhoud van zo’n constructie wordt verwerkt "as is". |
| HorizontalRule | `40` | Deze vlag schakelt de conversie van `horizontal rules` in. |
| Link | `80` | Deze vlag schakelt de conversie van `a`‑elementen in. |
| Emphasis | `100` | Deze vlag schakelt de conversie van `emphasis`-elementen in. |
| InlineCode | `200` | Deze vlag schakelt de conversie van `code`-elementen in. |
| Image | `400` | Deze vlag schakelt de conversie van `img`-elementen in. |
| LineBreak | `800` | Deze vlag schakelt de conversie van `br`-elementen in. |
| Video | `1000` | Deze vlag schakelt de conversie van `video`-elementen in. |
| Table | `2000` | Deze vlag schakelt de conversie van `table`-elementen in. |
| TaskList | `4000` | Deze vlag schakelt de conversie van takenlijsten in. Een takenlijst bestaat uit een `input`-element, dat het eerste kind van een `list`-element moet zijn en waarvan de `type`-attribuutwaarde gelijk moet zijn aan `checkbox`. |
| Strikethrough | `8000` | Deze vlag schakelt de conversie van `del`-elementen in. |
| Strong | `10000` | Deze vlag schakelt de conversie van `strong`-elementen in. |

### Zie ook

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
