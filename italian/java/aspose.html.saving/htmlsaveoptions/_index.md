---
title: "Classe HTMLSaveOptions"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.saving.HTMLSaveOptions. Rappresenta le opzioni di salvataggio HTML. Assegnando proprietà specifiche è possibile gestire l'elaborazione delle risorse, come la profondità massima di gestione e così via. Per ulteriori informazioni vedere l'articolo della documentazione"
type: docs

url: /it/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Rappresenta le opzioni di salvataggio HTML. Assegnando proprietà specifiche è possibile gestire l'elaborazione delle risorse, ad esempio la profondità massima di gestione e così via. Maggiori informazioni nella documentazione [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Ottiene un oggetto [`ResourceHandlingOptions`](../resourcehandlingoptions/) che viene utilizzato per la configurazione della gestione delle risorse. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | Il tipo di documento di output verrà selezionato automaticamente. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | Il documento verrà salvato come HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | Il documento verrà salvato come XHTML. |

## Osservazioni

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Prepara un percorso di output per un documento HTML 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Prepara un semplice file HTML con un documento collegato
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Prepara un semplice file HTML collegato
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Carica "save-with-linked-file.html" in memoria
      using (var document = new HTMLDocument(documentPath))
      {
        // Crea un'istanza delle opzioni di salvataggio
        var options = new HTMLSaveOptions();

        // La riga seguente con valore '0' esclude tutti gli altri file HTML collegati durante il salvataggio di questa istanza
        // Se rimuovi questa riga o cambi il valore in '1', il file 'linked.html' verrà salvato anch'esso nella cartella di output
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Salva il documento con le opzioni di salvataggio
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### Vedi anche

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
