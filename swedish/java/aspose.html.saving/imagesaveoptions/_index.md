---
title: "ImageSaveOptions-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.ImageSaveOptions class. Specifik alternativdataklass. Den tillhandahåller egenskaper för att hantera bildresultatets upplösning, jämning, kvalitet, format samt sidinställningar med mera. Mer information kan du hitta i dokumentationsartikel"
type: docs

url: /sv/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Specifik dataklass för alternativ. Den tillhandahåller egenskaper för att hantera bildresultatets upplösning, jämnhetskvalitet, format samt sidinställningar med mera. Mer information kan du hitta i dokumentationen [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Initierar en ny instans av `ImageSaveOptions`-klassen; Png kommer att användas som standardbildformat. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Bildformat [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) baserat på initiering |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Hämtar ett [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) objekt som används för konfiguration av css‑egenskapers bearbetning. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Ställer in eller hämtar horisontell upplösning för utdata- och interna (som används under filterbehandling) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Hämtar ett sidinställningsobjekt som används för konfiguration av utdata siduppsättning. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Hämtar ett [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/)‑objekt som används för konfiguration av textrendering. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Ställer in eller hämtar vertikal upplösning för utdata- och interna (som används under filterbehandling) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |

## Anmärkningar

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Förbered en sökväg till en käll-HTML-fil.
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Förbered en sökväg för att spara den konverterade filen 
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Initiera ett HTML-dokument från filen.
      using var document = new HTMLDocument(documentPath);

      // Initiera ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Konvertera HTML till PNG
      Converter.ConvertHTML(document, options, savePath);
```

### Se även

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
