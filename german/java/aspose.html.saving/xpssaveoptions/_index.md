---
title: "XpsSaveOptions Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.XpsSaveOptions Klasse. Spezifische Optionsdatenklasse bietet einige Eigenschaften zur Verwaltung des Konvertierungsergebnisses. Zum Beispiel legt PageSetup die Seiteneigenschaften fest. Siehe Dokumentationsartikel"
type: docs

url: /de/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Spezifische Optionsdatenklasse bietet einige Eigenschaften zur Verwaltung des Konvertierungsergebnisses. Zum Beispiel legt [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) die Seiteneigenschaften fest. Siehe den Dokumentations[Artikel](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gibt ein [`CssOptions`](../../com.aspose.html.rendering/cssoptions/)‑Objekt zurück, das für die Konfiguration der Verarbeitung von CSS‑Eigenschaften verwendet wird. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Legt die horizontale Auflösung für interne (bei der Filterverarbeitung verwendete) Bilder fest oder gibt sie zurück, in Pixel pro Zoll. Standardmäßig beträgt diese Eigenschaft 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gibt ein Seiten-Setup‑Objekt zurück, das für die Konfiguration des Ausgabe‑Page‑Sets verwendet wird. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Legt die vertikale Auflösung für interne (bei der Filterverarbeitung verwendete) Bilder fest oder gibt sie zurück, in Pixel pro Zoll. Standardmäßig beträgt diese Eigenschaft 300 dpi. |

## Hinweise

Sie finden vollständige Beispiele und Datendateien auf [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Beispiele

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Bereiten Sie HTML‑Code vor und speichern Sie ihn in einer Datei
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Initialisieren Sie ein HTML‑Dokument aus der HTML‑Datei
      using var document = new HTMLDocument(documentPath);
       
      // Legen Sie die Seitengröße, die Ränder fest und ändern Sie die Hintergrundfarbe zu AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // HTML zu XPS konvertieren
      Converter.ConvertHTML(document, options, savePath); 
```

### Siehe auch

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
