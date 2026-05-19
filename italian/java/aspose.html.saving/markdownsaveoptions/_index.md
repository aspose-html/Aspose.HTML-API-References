---
title: "Classe MarkdownSaveOptions"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.saving.MarkdownSaveOptions. Rappresenta le opzioni di salvataggio Markdown. Ad esempio è possibile impostare lo stile di formattazione markdown utilizzando opzioni compatibili predefinite per GitLab Flavored Markdown e configurare la gestione delle risorse. Consulta ulteriori informazioni nell'articolo"
type: docs

url: /it/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Rappresenta le opzioni di salvataggio Markdown. Ad esempio, è possibile impostare lo stile di formattazione markdown, utilizzare opzioni predefinite compatibili con GitLab Flavored Markdown e configurare la gestione delle risorse. Per ulteriori informazioni consultare [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Inizializza una nuova istanza della classe `MarkdownSaveOptions`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Restituisce un insieme di opzioni compatibili con la documentazione Markdown predefinita. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Restituisce un insieme di opzioni compatibili con GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Ottiene un oggetto [`ResourceHandlingOptions`](../resourcehandlingoptions/) che viene utilizzato per la configurazione della gestione delle risorse. |

## Osservazioni

Puoi trovare esempi completi e file di dati su [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Prepara un percorso per il salvataggio del file convertito
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Prepara il codice HTML e salvalo nel file
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Crea un'istanza di SaveOptions e imposta la regola: 
      // - solo gli elementi <a> e <p> saranno convertiti in Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Chiama il metodo ConvertHTML per convertire l'HTML in Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### Vedi anche

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
