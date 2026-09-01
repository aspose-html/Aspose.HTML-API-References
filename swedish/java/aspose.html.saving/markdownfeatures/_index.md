---
title: "MarkdownFeatures-enum"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.MarkdownFeatures-enum. En MarkdownFeatures-flagguppsättning är en samling av noll eller fler av följande flaggor som används för att välja element som konverteras till markdown."
type: docs

url: /sv/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

En `MarkdownFeatures`‑flagguppsättning är en samling av noll eller fler av följande flaggor, som används för att välja element som konverteras till markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| InlineHTML | `1` | Denna flagga möjliggör inline‑placering av HTML‑element. Om flaggan är satt kommer blocknivåelement (såsom `div`) vars `markdown`‑attributvärde är `inline` att infogas i den resulterande markdownen. |
| AutomaticParagraph | `2` | Denna flagga möjliggör konvertering av `paragraph`‑element. Innehållet i sådana element placeras på separata rader, så markdown‑hanterare kommer att radbryta det. |
| Header | `4` | Denna flagga möjliggör konvertering av `header`‑element. |
| Blockquote | `8` | Denna flagga möjliggör konvertering av `blockquote`‑element. |
| List | `10` | Denna flagga möjliggör konvertering av `list`‑element. |
| CodeBlock | `20` | Denna flagga möjliggör konvertering av kodblock. Ett kodblock består av två element `pre` och `code`, innehållet i en sådan konstruktion behandlas "as is". |
| HorizontalRule | `40` | Denna flagga möjliggör konvertering av `horizontal rules`. |
| Link | `80` | Denna flagga möjliggör konvertering av `a`‑element. |
| Emphasis | `100` | Denna flagga möjliggör konvertering av `emphasis`-element. |
| InlineCode | `200` | Denna flagga möjliggör konvertering av `code`-element. |
| Image | `400` | Denna flagga möjliggör konvertering av `img`-element. |
| LineBreak | `800` | Denna flagga möjliggör konvertering av `br`-element. |
| Video | `1000` | Denna flagga möjliggör konvertering av `video`-element. |
| Table | `2000` | Denna flagga möjliggör konvertering av `table`-element. |
| TaskList | `4000` | Denna flagga möjliggör konvertering av uppgiftslistor. En uppgiftslista består av `input`-element, som måste vara det första barnet till `list`-elementet och vars `type`-attributvärde ska vara `checkbox`. |
| Strikethrough | `8000` | Denna flagga möjliggör konvertering av `del`-element. |
| Strong | `10000` | Denna flagga möjliggör konvertering av `strong`-element. |

### Se även

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
