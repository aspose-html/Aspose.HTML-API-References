---
title: "DocSaveOptions Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.DocSaveOptions Klasse. Spezifische Optionsdatenklasse. Durch das Zuweisen von Eigenschaften können Sie Rendering‑Merkmale wie Auflösung, Seitengröße, Hintergrundfarbe sowie dokumentspezifische Optionen wie Schriftart‑Einbettung verwalten. Weitere Informationen siehe im Dokumentationsartikel"
type: docs

url: /de/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Spezieller Options-Datenklasse. Durch Zuweisen von Eigenschaften können Sie Rendering‑Parameter wie Auflösung, Seitengröße, Hintergrundfarbe sowie dokumentenspezifische Optionen wie Schriftart‑Einbettung verwalten. Weitere Informationen finden Sie in der Dokumentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gibt ein [`CssOptions`](../../com.aspose.html.rendering/cssoptions/)‑Objekt zurück, das für die Konfiguration der Verarbeitung von CSS‑Eigenschaften verwendet wird. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Legt die horizontale Auflösung für interne (bei der Filterverarbeitung verwendete) Bilder fest oder gibt sie zurück, in Pixel pro Zoll. Standardmäßig beträgt diese Eigenschaft 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gibt ein Seiten-Setup‑Objekt zurück, das für die Konfiguration des Ausgabe‑Page‑Sets verwendet wird. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Legt die vertikale Auflösung für interne (bei der Filterverarbeitung verwendete) Bilder fest oder gibt sie zurück, in Pixel pro Zoll. Standardmäßig beträgt diese Eigenschaft 300 dpi. |

## Hinweise

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Bereiten Sie einen Pfad zu einer Quell‑HTML‑Datei vor
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Bereiten Sie einen Pfad für das Speichern der konvertierten Datei vor
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Initialisieren Sie ein HTML‑Dokument aus der Datei
      using var document = new HTMLDocument(documentPath);

      // Initialisieren Sie DocSaveOptions. Legen Sie die Seitengröße von 600 × 400 Pixeln und die Ränder fest
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // HTML in DOCX konvertieren
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### Siehe auch

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
