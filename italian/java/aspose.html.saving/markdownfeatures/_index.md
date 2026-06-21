---
title: "Enum MarkdownFeatures"
second_title: "Aspose.HTML per Java Riferimento API"
description: "enum com.aspose.html.saving.MarkdownFeatures. Un set di flag MarkdownFeatures è un insieme di zero o più dei seguenti flag che vengono usati per selezionare gli elementi convertiti in markdown"
type: docs

url: /it/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

Un set di flag `MarkdownFeatures` è un insieme di zero o più dei seguenti flag, che vengono usati per selezionare gli elementi convertiti in markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| InlineHTML | `1` | Questo flag abilita l'inserimento in linea degli elementi HTML. Se questo flag è impostato, gli elementi a livello di blocco (come `div`) il cui valore dell'attributo `markdown` è `inline` verranno inseriti nel markdown risultante. |
| AutomaticParagraph | `2` | Questo flag abilita la conversione degli elementi `paragraph`. Il contenuto di tali elementi sarà posizionato su linee separate, così i gestori markdown lo avvolgeranno. |
| Header | `4` | Questo flag abilita la conversione degli elementi `header`. |
| Blockquote | `8` | Questo flag abilita la conversione degli elementi `blockquote`. |
| List | `10` | Questo flag abilita la conversione degli elementi `list`. |
| CodeBlock | `20` | Questo flag abilita la conversione dei blocchi di codice. Un blocco di codice è composto da 2 elementi `pre` e `code`, il contenuto di tale costruzione viene elaborato "as is". |
| HorizontalRule | `40` | Questo flag abilita la conversione delle `horizontal rules`. |
| Link | `80` | Questo flag abilita la conversione degli elementi `a`. |
| Emphasis | `100` | Questa opzione abilita la conversione degli elementi `emphasis`. |
| InlineCode | `200` | Questa opzione abilita la conversione degli elementi `code`. |
| Image | `400` | Questa opzione abilita la conversione degli elementi `img`. |
| LineBreak | `800` | Questa opzione abilita la conversione degli elementi `br`. |
| Video | `1000` | Questa opzione abilita la conversione degli elementi `video`. |
| Table | `2000` | Questa opzione abilita la conversione degli elementi `table`. |
| TaskList | `4000` | Questa opzione abilita la conversione delle liste di attività. Una lista di attività è composta dall'elemento `input`, che deve essere il primo figlio dell'elemento `list` e il cui valore dell'attributo `type` deve essere uguale a `checkbox`. |
| Strikethrough | `8000` | Questa opzione abilita la conversione degli elementi `del`. |
| Strong | `10000` | Questa opzione abilita la conversione degli elementi `strong`. |

### Vedi anche

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
