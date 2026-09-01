---
title: "MarkdownFeatures Aufzählung"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.MarkdownFeatures Aufzählung. Ein MarkdownFeatures‑Flag‑Set ist eine Menge von null oder mehr der folgenden Flags, die verwendet werden, um in Markdown konvertierte Elemente auszuwählen."
type: docs

url: /de/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

Ein `MarkdownFeatures` Flag‑Set ist eine Menge von null oder mehr der folgenden Flags, die verwendet werden, um in Markdown konvertierte Elemente auszuwählen.

```java
[Flags]
public enum MarkdownFeatures
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| InlineHTML | `1` | Dieses Flag aktiviert das Inline‑Einbetten von HTML‑Elementen. Wenn dieses Flag gesetzt ist, werden Block‑Elemente (wie `div`), deren `markdown`‑Attributwert `inline` ist, in das resultierende Markdown eingefügt. |
| AutomaticParagraph | `2` | Dieses Flag aktiviert die Konvertierung von `paragraph`‑Elementen. Der Inhalt solcher Elemente wird in separate Zeilen gesetzt, sodass Markdown‑Handler ihn umbrechen. |
| Header | `4` | Dieses Flag aktiviert die Konvertierung von `header`‑Elementen. |
| Blockquote | `8` | Dieses Flag aktiviert die Konvertierung von `blockquote`‑Elementen. |
| List | `10` | Dieses Flag aktiviert die Konvertierung von `list`‑Elementen. |
| CodeBlock | `20` | Dieses Flag aktiviert die Konvertierung von Code‑Blöcken. Ein Code‑Block besteht aus den beiden Elementen `pre` und `code`; der Inhalt einer solchen Konstruktion wird "as is" verarbeitet. |
| HorizontalRule | `40` | Dieses Flag aktiviert die Konvertierung von `horizontal rules`. |
| Link | `80` | Dieses Flag aktiviert die Konvertierung von `a`‑Elementen. |
| Emphasis | `100` | Dieses Flag aktiviert die Konvertierung von `emphasis`-Elementen. |
| InlineCode | `200` | Dieses Flag aktiviert die Konvertierung von `code`-Elementen. |
| Image | `400` | Dieses Flag aktiviert die Konvertierung von `img`-Elementen. |
| LineBreak | `800` | Dieses Flag aktiviert die Konvertierung von `br`-Elementen. |
| Video | `1000` | Dieses Flag aktiviert die Konvertierung von `video`-Elementen. |
| Table | `2000` | Dieses Flag aktiviert die Konvertierung von `table`-Elementen. |
| TaskList | `4000` | Dieses Flag aktiviert die Konvertierung von Aufgabenlisten. Eine Aufgabenliste besteht aus einem `input`-Element, das das erste Kind eines `list`-Elements sein muss und dessen `type`-Attributwert `checkbox` sein sollte. |
| Strikethrough | `8000` | Dieses Flag aktiviert die Konvertierung von `del`-Elementen. |
| Strong | `10000` | Dieses Flag aktiviert die Konvertierung von `strong`-Elementen. |

### Siehe auch

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
