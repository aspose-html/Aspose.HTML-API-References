---
title: "Classe HTMLSaveOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.saving.HTMLSaveOptions class. Représente les options d'enregistrement HTML. En assignant des propriétés spécifiques, vous pouvez gérer le traitement des ressources comme la profondeur maximale de traitement, etc. Plus d'informations dans l'article de documentation"
type: docs

url: /fr/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Représente les options d'enregistrement HTML. En assignant des propriétés spécifiques, vous pouvez gérer le traitement des ressources telles que la profondeur maximale de traitement, etc. Plus d'informations dans la documentation [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Obtient un objet [`ResourceHandlingOptions`](../resourcehandlingoptions/) qui est utilisé pour la configuration du traitement des ressources. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Champs

| Nom | Description |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | Le type de document de sortie sera sélectionné automatiquement. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | Le document sera enregistré au format HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | Le document sera enregistré au format XHTML. |

## Remarques

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Préparez un chemin de sortie pour un document HTML 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Préparez un fichier HTML simple avec un document lié
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Préparez un fichier HTML lié simple
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Chargez le fichier "save-with-linked-file.html" en mémoire
      using (var document = new HTMLDocument(documentPath))
      {
        // Créez une instance d'options d'enregistrement
        var options = new HTMLSaveOptions();

        // La ligne suivante avec la valeur '0' coupe tous les autres fichiers HTML liés lors de l'enregistrement de cette instance
        // Si vous supprimez cette ligne ou changez la valeur en '1', le fichier 'linked.html' sera également enregistré dans le dossier de sortie
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Enregistrez le document avec les options d'enregistrement
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### Voir aussi

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
