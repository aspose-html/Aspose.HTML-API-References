---
title: "MHTMLSaveOptions-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.MHTMLSaveOptions-klass. Representerar MHTML-sparalternativ. Genom att tilldela specifika egenskaper kan du hantera resursbehandling såsom maximal hanteringsdjup med mera. Mer information finns i dokumentationsartikeln"
type: docs

url: /sv/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Representerar MHTML‑sparalternativ. Genom att tilldela specifika egenskaper kan du hantera resursbehandling såsom maximal hanteringsdjup med mera. Mer information finns i dokumentationen [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Hämtar ett [`ResourceHandlingOptions`](../resourcehandlingoptions/)‑objekt som används för konfiguration av resurs‑hantering. |

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
	 // Förbered HTML‑kod med en länk till en annan fil och spara den till filen som 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Förbered HTML‑kod och spara den till filen som 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Ändra värdet för resurslänkningsdjupet till 1 för att konvertera dokumentet med direkt länkade resurser
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // Konvertera HTML till MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Se även

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
