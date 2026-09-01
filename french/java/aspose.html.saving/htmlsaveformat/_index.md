---
title: "Énumération HTMLSaveFormat"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Énumération com.aspose.html.saving.HTMLSaveFormat. Spécifie le format dans lequel le document est enregistré. Vous pouvez trouver plus d'informations sur l'enregistrement de HTMLDocument dans l'article"
type: docs

url: /fr/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Spécifie le format dans lequel le document est enregistré. Vous pouvez trouver plus d'informations sur l'enregistrement de [`HTMLDocument`](../../com.aspose.html/htmldocument/) dans [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Original | `0` | Le document sera enregistré dans son format d'origine. |
| Markdown | `1` | Le document sera enregistré au format Markdown. |
| MHTML | `2` | Le document sera enregistré au format MHTML. |

## Remarques

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Préparer un chemin de sortie pour l'enregistrement d'un document
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Préparer le code HTML
  var html_code = "<H2>Hello World!</H2>";
   
  // Initialiser un document à partir de la variable String
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Enregistrer le document en tant que fichier Markdown
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### Voir aussi

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
