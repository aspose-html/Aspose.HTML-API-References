---
title: "Classe MarkdownSaveOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.saving.MarkdownSaveOptions. Représente les options d'enregistrement Markdown. Par exemple, vous pouvez définir le style de formatage Markdown en utilisant des options compatibles pré‑définies GitLab Flavored Markdown et configurer la gestion des ressources. Consultez plus d'informations dans l'article."
type: docs

url: /fr/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Représente les options d'enregistrement Markdown. Par exemple, vous pouvez définir le style de formatage Markdown, utiliser des options compatibles prédefinies GitLab Flavored Markdown et configurer le traitement des ressources. Reportez-vous à plus d'informations dans [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Initialise une nouvelle instance de la classe `MarkdownSaveOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Retourne un ensemble d'options compatibles avec la documentation Markdown par défaut. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Retourne un ensemble d'options compatibles avec GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
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
	 // Préparez un chemin pour l'enregistrement du fichier converti
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Préparez le code HTML et enregistrez-le dans le fichier
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Créez une instance de SaveOptions et définissez la règle : 
      // - seuls les éléments <a> et <p> seront convertis en Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Appelez la méthode ConvertHTML pour convertir le HTML en Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### Voir aussi

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
