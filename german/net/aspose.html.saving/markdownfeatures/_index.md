---
title: Enum MarkdownFeatures
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Saving.MarkdownFeatures opsomming. AMarkdownFeatures FlagSet ist ein Satz von null oder mehr der folgenden Flags die verwendet werden um Elemente auszuwählen die in Markdown konvertiert werden.
type: docs
weight: 4620
url: /de/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

A`MarkdownFeatures` Flag-Set ist ein Satz von null oder mehr der folgenden Flags, die verwendet werden, um Elemente auszuwählen, die in Markdown konvertiert werden.

```csharp
[Flags]
public enum MarkdownFeatures
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| InlineHTML | `1` | Dieses Flag aktiviert das Inlining von HTML-Elementen. Wenn dieses Flag gesetzt ist, werden Elemente auf Blockebene (wie z`div` ) wessen`Abschlag` Attributwert gleich`im Einklang` wird in den resultierenden Abschlag eingefügt. |
| AutomaticParagraph | `2` | Dieses Flag ermöglicht die Konvertierung von`Absatz` Elemente. Der Inhalt solcher Elemente wird in separaten Zeilen platziert, sodass Markdown-Handler ihn umbrechen. |
| Header | `4` | Dieses Flag ermöglicht die Konvertierung von`Header` Elemente. |
| Blockquote | `8` | Dieses Flag ermöglicht die Konvertierung von`Blockzitat` Elemente. |
| List | `10` | Dieses Flag ermöglicht die Konvertierung von`Liste` Elemente. |
| CodeBlock | `20` | Dieses Flag aktiviert die Konvertierung von Codeblöcken. Codeblock besteht aus 2 Elementen`Vor` Und`Code` , Inhalt einer solchen Konstruktion sind Prozesse "wie sie sind". |
| HorizontalRule | `40` | Dieses Flag ermöglicht die Konvertierung von`horizontale Regeln` . |
| Link | `80` | Dieses Flag ermöglicht die Konvertierung von`A` Elemente. |
| Emphasis | `100` | Dieses Flag ermöglicht die Konvertierung von`Schwerpunkt` Elemente. |
| InlineCode | `200` | Dieses Flag ermöglicht die Konvertierung von`Code` Elemente. |
| Image | `400` | Dieses Flag ermöglicht die Konvertierung von`Bild` Elemente. |
| LineBreak | `800` | Dieses Flag ermöglicht die Konvertierung von`Br` Elemente. |
| Video | `1000` | Dieses Flag ermöglicht die Konvertierung von`Video` Elemente. |
| Table | `2000` | Dieses Flag ermöglicht die Konvertierung von`Tisch` Elemente. |
| TaskList | `4000` | Dieses Flag aktiviert die Konvertierung von Aufgabenlisten. Aufgabenliste besteht aus`Eingang` -Element, das das erste Kind von sein muss`Liste` Element und dessen`Typ` Attributwert sollte gleich sein`Kontrollkästchen` . |
| Strikethrough | `8000` | Dieses Flag ermöglicht die Konvertierung von`lösch` Elemente. |
| Strong | `10000` | Dieses Flag ermöglicht die Konvertierung von`stark` Elemente. |

### Siehe auch

* namensraum [Aspose.Html.Saving](../../aspose.html.saving/)
* Montage [Aspose.HTML](../../)


