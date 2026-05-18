---
title: "Classe XpsSaveOptions"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.saving.XpsSaveOptions. La classe de données d'options spécifiques fournit quelques propriétés pour gérer le résultat de la conversion. Par exemple, PageSetup spécifie les caractéristiques de la page. Consultez l'article de documentation."
type: docs

url: /fr/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

La classe de données d'options spécifiques fournit quelques propriétés pour gérer le résultat de la conversion. Par exemple, [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) spécifie les caractéristiques de la page. Consultez la documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtient un objet [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) qui est utilisé pour la configuration du traitement des propriétés CSS. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Définit ou obtient la résolution horizontale pour les images internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtient un objet de configuration de page utilisé pour la configuration de la sortie du jeu de pages. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Définit ou obtient la résolution verticale pour les images internes (utilisées lors du traitement des filtres), en pixels par pouce. Par défaut, cette propriété est de 300 dpi. |

## Remarques

Vous pouvez trouver des exemples complets et des fichiers de données sur [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Préparez le code HTML et enregistrez-le dans un fichier
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Initialisez un Document HTML à partir du fichier html
      using var document = new HTMLDocument(documentPath);
       
      // Configurez la taille de page, les marges et changez la couleur d'arrière-plan en AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Convertir HTML en XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### Voir aussi

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
