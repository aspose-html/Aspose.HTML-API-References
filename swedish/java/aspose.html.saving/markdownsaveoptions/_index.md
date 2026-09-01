---
title: "MarkdownSaveOptions-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.MarkdownSaveOptions-klass. Representerar Markdown-sparalternativ. Till exempel kan du ställa in markdown-formateringsstil, använda fördefinierade GitLab Flavored Markdown‑kompatibla alternativ och konfigurera resurshantering. Se mer information i artikeln."
type: docs

url: /sv/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Representerar Markdown-sparalternativ. Till exempel kan du ange markdown-formateringsstil, använda fördefinierade GitLab-flavored-Markdown-kompatibla alternativ och konfigurera resurs‑hantering. Se mer information i [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Initierar en ny instans av klassen `MarkdownSaveOptions`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| statisk [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Returnerar en uppsättning alternativ som är kompatibla med standard‑Markdown‑dokumentationen. |
| statisk [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Returnerar en uppsättning alternativ som är kompatibla med GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Hämtar ett [`ResourceHandlingOptions`](../resourcehandlingoptions/)‑objekt som används för konfiguration av resurshantering. |

## Anmärkningar

Du kan hitta kompletta exempel och datafiler på [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Förbered en sökväg för att spara den konverterade filen
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Förbered HTML-kod och spara den till filen
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Skapa en instans av SaveOptions och ställ in regeln: 
      // - endast <a>- och <p>-element kommer att konverteras till Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Anropa ConvertHTML-metoden för att konvertera HTML till Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### Se även

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
