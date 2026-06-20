---
title: "MarkdownSaveOptions Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.MarkdownSaveOptions Klasse. Stellt Markdown‑Speicheroptionen dar. Zum Beispiel können Sie den Markdown‑Formatierungsstil festlegen, vordefinierte, mit GitLab Flavored Markdown kompatible Optionen verwenden und die Ressourcenverwaltung konfigurieren. Weitere Informationen finden Sie im Artikel"
type: docs

url: /de/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Stellt Markdown-Speicheroptionen dar. Zum Beispiel können Sie den Markdown-Formatierungsstil festlegen, vordefinierte, mit GitLab Flavored Markdown kompatible Optionen verwenden und die Ressourcenverarbeitung konfigurieren. Weitere Informationen finden Sie im [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Initialisiert eine neue Instanz der `MarkdownSaveOptions`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Gibt ein Optionsset zurück, das mit der Standard‑Markdown‑Dokumentation kompatibel ist. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Gibt ein Optionsset zurück, das mit GitLab Flavored Markdown kompatibel ist. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Gibt ein [`ResourceHandlingOptions`](../resourcehandlingoptions/) Objekt zurück, das für die Konfiguration der Ressourcenverwaltung verwendet wird. |

## Hinweise

Sie finden vollständige Beispiele und Datendateien auf [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Beispiele

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Bereiten Sie einen Pfad für das Speichern der konvertierten Datei vor
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Bereiten Sie HTML‑Code vor und speichern Sie ihn in die Datei
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Erstellen Sie eine Instanz von SaveOptions und legen Sie die Regel fest: 
      // - nur <a>- und <p>-Elemente werden in Markdown konvertiert
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Rufen Sie die Methode ConvertHTML auf, um das HTML in Markdown zu konvertieren.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### Siehe auch

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
