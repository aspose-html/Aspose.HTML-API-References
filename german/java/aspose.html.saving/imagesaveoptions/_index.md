---
title: "ImageSaveOptions Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.ImageSaveOptions Klasse. Spezifische Optionsdatenklasse. Sie bietet Eigenschaften zur Verwaltung der Bildausgabeauflösung, Glättung, Qualitätsformat sowie Seiteneinstellungen usw. Weitere Informationen erhalten Sie im Dokumentationsartikel."
type: docs

url: /de/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Spezielle Options-Datenklasse. Sie bietet Eigenschaften zur Verwaltung der Bildauflösung, Glättungsqualität, des Formats sowie der Seiteneinstellungen usw. Weitere Informationen erhalten Sie in der Dokumentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Initialisiert eine neue Instanz der `ImageSaveOptions` Klasse; Png wird als Standardbildformat verwendet. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Bildformat [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) basierend auf der Initialisierung |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gibt ein [`CssOptions`](../../com.aspose.html.rendering/cssoptions/)‑Objekt zurück, das für die Konfiguration der Verarbeitung von CSS‑Eigenschaften verwendet wird. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Legt die horizontale Auflösung für Ausgabe‑ und interne (bei der Filterverarbeitung verwendete) Bilder fest oder gibt sie zurück, in Pixel pro Zoll. Standardmäßig ist diese Eigenschaft 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gibt ein Seiten-Setup‑Objekt zurück, das für die Konfiguration des Ausgabe‑Page‑Sets verwendet wird. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Gibt ein [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) Objekt zurück, das für die Konfiguration der Textdarstellung verwendet wird. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Legt die vertikale Auflösung für Ausgabe‑ und interne (bei der Filterverarbeitung verwendete) Bilder fest oder gibt sie zurück, in Pixel pro Zoll. Standardmäßig ist diese Eigenschaft 300 dpi. |

## Hinweise

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Bereiten Sie einen Pfad zu einer Quell‑HTML‑Datei vor
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Bereiten Sie einen Pfad für das Speichern der konvertierten Datei vor
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Initialisieren Sie ein HTML‑Dokument aus der Datei
      using var document = new HTMLDocument(documentPath);

      // Initialisieren Sie ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // HTML nach PNG konvertieren
      Converter.ConvertHTML(document, options, savePath);
```

### Siehe auch

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
