---
title: Enum MarkdownFeatures
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Saving.MarkdownFeatures enum. AMarkdownFeatures set di flag è un insieme di zero o più dei seguenti flag utilizzati per selezionare gli elementi convertiti in markdown.
type: docs
weight: 4620
url: /it/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

A`MarkdownFeatures` set di flag è un insieme di zero o più dei seguenti flag, utilizzati per selezionare gli elementi convertiti in markdown.

```csharp
[Flags]
public enum MarkdownFeatures
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| InlineHTML | `1` | Questo flag abilita l'incorporamento degli elementi HTML. Se questo flag è impostato, gli elementi a livello di blocco (come`div` ) di chi`ribasso` il valore dell'attributo è uguale`in linea` verrà inserito nel markdown risultante. |
| AutomaticParagraph | `2` | Questo flag abilita la conversione di`paragrafo` elementi. Il contenuto di tali elementi verrà posizionato su righe separate, quindi i gestori di markdown lo avvolgeranno. |
| Header | `4` | Questo flag abilita la conversione di`intestazione` elementi. |
| Blockquote | `8` | Questo flag abilita la conversione di`blockquote` elementi. |
| List | `10` | Questo flag abilita la conversione di`elenco` elementi. |
| CodeBlock | `20` | Questo flag abilita la conversione dei blocchi di codice. Il blocco di codice è composto da 2 elementi`pre` E`codice` , il contenuto di tale costruzione è il processo "così com'è". |
| HorizontalRule | `40` | Questo flag abilita la conversione di`regole orizzontali` . |
| Link | `80` | Questo flag abilita la conversione di`UN` elementi. |
| Emphasis | `100` | Questo flag abilita la conversione di`enfasi` elementi. |
| InlineCode | `200` | Questo flag abilita la conversione di`codice` elementi. |
| Image | `400` | Questo flag abilita la conversione di`imm` elementi. |
| LineBreak | `800` | Questo flag abilita la conversione di`fratello` elementi. |
| Video | `1000` | Questo flag abilita la conversione di`video` elementi. |
| Table | `2000` | Questo flag abilita la conversione di`tavolo` elementi. |
| TaskList | `4000` | Questo flag abilita la conversione degli elenchi di attività. L'elenco delle attività è composto da`ingresso` elemento, che deve essere il primo figlio di`elenco` elemento e di chi`tipo` il valore dell'attributo deve essere uguale`casella di controllo` . |
| Strikethrough | `8000` | Questo flag abilita la conversione di`del` elementi. |
| Strong | `10000` | Questo flag abilita la conversione di`forte` elementi. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Saving](../../aspose.html.saving/)
* assemblea [Aspose.HTML](../../)


