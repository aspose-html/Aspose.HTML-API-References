---
title: "Classe MHTMLSaveOptions"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.saving.MHTMLSaveOptions. Rappresenta le opzioni di salvataggio MHTML. Assegnando proprietà specifiche è possibile gestire l'elaborazione delle risorse, come la profondità massima di gestione e così via. Per ulteriori informazioni vedere l'articolo della documentazione"
type: docs

url: /it/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Rappresenta le opzioni di salvataggio MHTML. Assegnando proprietà specifiche è possibile gestire l'elaborazione delle risorse, ad esempio la profondità massima di gestione e così via. Maggiori informazioni nella documentazione [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
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
	 // Prepara il codice HTML con un collegamento a un altro file e salvalo nel file come 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Prepara il codice HTML e salvalo nel file come 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Modifica il valore della profondità di collegamento delle risorse a 1 per convertire il documento con risorse collegate direttamente
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // Converti HTML in MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Vedi anche

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
