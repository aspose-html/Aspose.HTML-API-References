---
title: "Enum MarkdownFeatures"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "enum com.aspose.html.saving.MarkdownFeatures. Un ensemble de drapeaux MarkdownFeatures est un ensemble de zéro ou plusieurs des drapeaux suivants qui sont utilisés pour sélectionner les éléments convertis en markdown"
type: docs

url: /fr/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

Un ensemble de drapeaux `MarkdownFeatures` est un ensemble de zéro ou plusieurs des drapeaux suivants, qui sont utilisés pour sélectionner les éléments convertis en markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| InlineHTML | `1` | Ce drapeau active l'insertion en ligne des éléments HTML. Si ce drapeau est activé, alors les éléments de niveau bloc (comme `div`) dont la valeur de l'attribut `markdown` est égale à `inline` seront insérés dans le markdown résultant. |
| AutomaticParagraph | `2` | Ce drapeau active la conversion des éléments `paragraph`. Le contenu de ces éléments sera placé sur des lignes séparées, de sorte que les gestionnaires markdown l'envelopperont. |
| Header | `4` | Ce drapeau active la conversion des éléments `header`. |
| Blockquote | `8` | Ce drapeau active la conversion des éléments `blockquote`. |
| List | `10` | Ce drapeau active la conversion des éléments `list`. |
| CodeBlock | `20` | Ce drapeau active la conversion des blocs de code. Un bloc de code se compose de 2 éléments `pre` et `code`, le contenu d'une telle construction est traité "tel quel". |
| HorizontalRule | `40` | Ce drapeau active la conversion des `horizontal rules`. |
| Link | `80` | Ce drapeau active la conversion des éléments `a`. |
| Emphasis | `100` | Ce drapeau active la conversion des éléments `emphasis`. |
| InlineCode | `200` | Ce drapeau active la conversion des éléments `code`. |
| Image | `400` | Ce drapeau active la conversion des éléments `img`. |
| LineBreak | `800` | Ce drapeau active la conversion des éléments `br`. |
| Video | `1000` | Ce drapeau active la conversion des éléments `video`. |
| Table | `2000` | Ce drapeau active la conversion des éléments `table`. |
| TaskList | `4000` | Ce drapeau active la conversion des listes de tâches. Une liste de tâches se compose de l'élément `input`, qui doit être le premier enfant de l'élément `list` et dont la valeur de l'attribut `type` doit être égale à `checkbox`. |
| Strikethrough | `8000` | Ce drapeau active la conversion des éléments `del`. |
| Strong | `10000` | Ce drapeau active la conversion des éléments `strong`. |

### Voir aussi

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
