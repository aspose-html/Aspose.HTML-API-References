---
title: "Classe MHTMLSaveOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.saving.MHTMLSaveOptions. Représente les options d'enregistrement MHTML. En assignant des propriétés spécifiques, vous pouvez gérer le traitement des ressources telles que la profondeur maximale de traitement, etc. Pour plus d'informations, voir l'article de documentation."
type: docs

url: /fr/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Représente les options d'enregistrement MHTML. En assignant des propriétés spécifiques, vous pouvez gérer le traitement des ressources telles que la profondeur maximale de traitement, etc. Plus d'informations dans la documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Obtient un objet [`ResourceHandlingOptions`](../resourcehandlingoptions/) qui est utilisé pour la configuration du traitement des ressources. |

## Remarques

Vous pouvez trouver des exemples complets et des fichiers de données sur [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Préparez du code HTML avec un lien vers un autre fichier et enregistrez-le dans le fichier sous le nom 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Préparez du code HTML et enregistrez-le dans le fichier sous le nom 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Modifiez la valeur de la profondeur de liaison des ressources à 1 afin de convertir le document avec des ressources directement liées
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // Convertir HTML en MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Voir aussi

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
