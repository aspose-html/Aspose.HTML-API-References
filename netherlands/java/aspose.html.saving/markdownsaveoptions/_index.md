---
title: "MarkdownSaveOptions Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.MarkdownSaveOptions class. Vertegenwoordigt Markdown‑opslaanopties. Bijvoorbeeld je kunt de markdown‑opmaakstijl instellen, vooraf gedefinieerde GitLab Flavored Markdown‑compatibele opties gebruiken en de verwerking van bronnen configureren. Zie meer info in het artikel"
type: docs

url: /nl/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Stelt Markdown-opslagopties voor. Bijvoorbeeld, je kunt de markdown-opmaakstijl instellen, vooraf gedefinieerde GitLab Flavored Markdown-compatibele opties gebruiken en de verwerking van bronnen configureren. Raadpleeg meer info in [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Initialiseert een nieuwe instantie van de `MarkdownSaveOptions` class. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Retourneert een set opties die compatibel zijn met de standaard Markdown‑documentatie. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Retourneert een set opties die compatibel zijn met GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Haalt een [`ResourceHandlingOptions`](../resourcehandlingoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van bronnen. |

## Opmerkingen

Je kunt volledige voorbeelden en gegevensbestanden vinden op [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Bereid een pad voor om het geconverteerde bestand op te slaan 
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Bereid HTML‑code voor en sla deze op in het bestand
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Maak een instantie van SaveOptions aan en stel de regel in: 
      // - alleen <a>- en <p>-elementen worden geconverteerd naar Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Roep de ConvertHTML‑methode aan om de HTML naar Markdown te converteren.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### Zie ook

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
