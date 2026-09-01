---
title: "Converter.ConvertHTML"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Converter. Convertit la source HTML présentée par HTMLDocument. Le résultat est un fichier docx créé à l'emplacement du chemin de sortie."
type: docs

url: /fr/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

Convertit la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est un fichier docx créé à l'emplacement du chemin de sortie.

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) instance comme source de conversion. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// Chemin du fichier source du formulaire
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // Instancier l'objet de configuration par défaut
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// Définir le chemin du fichier de sortie
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// Définir l'objet DocSaveOptions par défaut
        var options = new DocSaveOptions();
         
		// Initier le processus de conversion avec l'objet de configuration par défaut
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

Convertir la source HTML présentée par URL. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

Convertir la source HTML présentée par URL. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion avec l'objet de configuration par défaut
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

Convertir la source HTML présentée par le chemin complet du fichier en DOCX. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

Convertir la source HTML présentée par le chemin complet du fichier en DOCX. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Chemin du fichier source du formulaire
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Chemin du fichier résultat du formulaire
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // Définir l'objet DocSaveOptions par défaut
   var options = new DocSaveOptions();

   // Initier le processus de conversion avec la configuration par défaut
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

Convertir la source HTML présentée par du contenu en ligne. Le résultat est un fichier docx créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// Définir l'objet DocSaveOptions par défaut
   	var options = new DocSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

Convertir la source HTML présentée par du contenu en ligne. Le résultat est un fichier docx créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// Définir l'objet DocSaveOptions par défaut
   	var options = new DocSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

Convertir la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Définir le contenu HTML en ligne
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// Instancier l'objet de configuration par défaut
      	var configuration = new Configuration();

      	// Créer un document HTML de plusieurs manières
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// Définir le chemin du fichier résultat sans extension
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// Utiliser l'une des implémentations de ICreateStreamProvider
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// Définir l'objet DocSaveOptions par défaut
			var options = new DocSaveOptions();

        	// Initier le processus de conversion
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

Convertir la source HTML présentée par une URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // Formater l'URL source
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Définir le chemin du fichier résultat sans extension
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser une implémentation connue de ICreateStreamProvider
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

Convertir la source HTML présentée par une URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // Formater l'URL source
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Définir le chemin du fichier résultat sans extension
   var resultPath = Path.Combine(OutputFolder, "result");

   // Utiliser une implémentation connue de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Définir l'objet DocSaveOptions par défaut
   var options = new DocSaveOptions();

   // Initier le processus de conversion avec la configuration par défaut
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

Convertir la source HTML présentée par un chemin de fichier complet vers DOCX. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formater le chemin du fichier HTML source
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Définir le chemin du fichier résultat
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'implémentation par défaut de ICreateStreamProvider
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

Convertir la source HTML présentée par un chemin de fichier complet vers DOCX. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formater le chemin du fichier HTML source
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Définir le chemin du fichier résultat
   var resultPath = Path.Combine(OutputFolder, "result");

   // Utiliser l'implémentation par défaut de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Définir l'objet DocSaveOptions par défaut
   var options = new DocSaveOptions();

   // Initier le processus de conversion avec l'objet de configuration par défaut
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

Convertir la source HTML présentée par du contenu en ligne vers DOCX. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // Formater le contenu HTML en ligne
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // Définir le chemin du fichier résultat
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser une implémentation connue de ICreateStreamProvider orientée fichier local
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Instancier l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

Convertir la source HTML présentée par du contenu en ligne vers DOCX. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) l'utilisation de l'objet vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Comment convertir HTML en DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion DOCX

Un fichier DOCX est un document Microsoft Word qui contient généralement du texte mais peut contenir une large gamme de données, y compris des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Le fichier DOCX est très modifiable, facile à utiliser et de taille gérable. Ce format est populaire en raison de la variété d'options qu'il offre aux utilisateurs pour rédiger tout type de documents. Ce format de fichier est l'un des plus largement utilisés et est disponible via de nombreux programmes.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML en DOCX](https://products.aspose.app/html/en/conversion/html-to-docx) gratuit en ligne qui convertit le HTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // Formater le contenu HTML en ligne
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // Définir le chemin du fichier résultat
   var resultPath = Path.Combine(OutputFolder, "result");

   // Utiliser une implémentation connue de ICreateStreamProvider orientée fichier local
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Instancier l'objet DocSaveOptions par défaut
   var options = new DocSaveOptions();

   // Initier le processus de conversion avec la configuration par défaut
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

Convertir la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est un fichier PDF généré à partir du chemin de sortie.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Instancier l'objet de configuration par défaut
      var configuration = new Configuration();

      // Créer un document html de l'une des multiples manières
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// Chemin du fichier résultat du formulaire
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // Définir l'objet PdfSaveOptions par défaut
        var options = new PdfSaveOptions();

		// Instancier le processus de conversion
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

Convertir la source HTML présentée par URL. Le résultat est un fichier pdf créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // Former une URL source basée sur un fichier
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

Convertir la source HTML présentée par URL. Le résultat est un fichier pdf créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // Former une URL source basée sur un fichier
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Chemin du fichier résultat du formulaire
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Définir l'objet PdfSaveOptions par défaut
   var options = new PdfSaveOptions();

   // Initier le processus de conversion avec l'objet de configuration par défaut
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

Convertir la source HTML présentée par le chemin complet du fichier en PDF. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Chemin du fichier source du formulaire
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Chemin du fichier résultat du formulaire
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Définir l'objet PdfSaveOptions par défaut
   var options = new PdfSaveOptions();

   // Initier le processus de conversion
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

Convertir la source HTML présentée par le chemin complet du fichier en PDF. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Chemin du fichier source du formulaire
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Chemin du fichier résultat du formulaire
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // Définir l'objet PdfSaveOptions par défaut
  var options = new PdfSaveOptions();

  // Initier le processus de conversion avec la configuration par défaut
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

Convertir la source HTML présentée par du contenu en ligne en PDF. Le résultat est un fichier pdf créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Définir l'objet PdfSaveOptions par défaut
   	var options = new PdfSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

Convertir la source HTML présentée par du contenu en ligne en PDF. Le résultat est un fichier pdf créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Définir l'objet PdfSaveOptions par défaut
  	var options = new PdfSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

Convertir la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/) en PDF. Le résultat est les données de sortie générées par l'implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Définir le contenu HTML en ligne
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// Instancier l'objet de configuration par défaut
   	var configuration = new Configuration();

   	// Créer un document HTML de plusieurs manières
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// Définir le chemin du fichier résultat sans extension
		var resultPath = Path.Combine(OutputFolder, "result");

		// Utiliser l'une des implémentations de ICreateStreamProvider
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// Définir l'objet PdfSaveOptions par défaut
		var options = new PdfSaveOptions();

		// Initier le processus de conversion
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

Convertir la source HTML présentée par une URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Créer une URL basée sur le chemin du fichier d'entrée
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Chemin du fichier résultat du formulaire
   var resultPath = Path.Combine(OutputFolder, "result");

   // Utiliser l'une des implémentations de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Définir l'objet PdfSaveOptions par défaut
   var options = new PdfSaveOptions();

   // Initier le processus de conversion
   Converter.ConvertHTML(sourceUrl, options, provider);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

Convertir la source HTML présentée par une URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Créer une URL basée sur le chemin du fichier d'entrée
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Chemin du fichier résultat du formulaire
   var resultPath = Path.Combine(OutputFolder, "result ");

   // Utiliser l'une des implémentations de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Définir l'objet PdfSaveOptions par défaut
   var options = new PdfSaveOptions();

   // Initier le processus de conversion avec la configuration par défaut
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

Convertir la source HTML présentée par le chemin complet du fichier en PDF. Le résultat est les données de sortie générées par l'implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Créer le chemin du fichier source
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Chemin du fichier résultat du formulaire
   var resultPath = Path.Combine(OutputFolder, "result");

   // Utiliser l'une des implémentations de ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Définir l'objet PdfSaveOptions par défaut
   var options = new PdfSaveOptions();

   // Initier le processus de conversion
   Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

Convertir la source HTML présentée par le chemin complet du fichier en PDF. Le résultat est les données de sortie générées par l'implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Créer le chemin du fichier source
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Chemin du fichier résultat du formulaire
  var resultPath = Path.Combine(OutputFolder, "result");

  // Utiliser l'une des implémentations de ICreateStreamProvider
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // Définir l'objet PdfSaveOptions par défaut
  var options = new PdfSaveOptions();

  // Initier le processus de conversion avec la configuration par défaut
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

Convertir la source HTML présentée par du contenu en ligne en PDF. Le résultat est les données de sortie générées par l'implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation d'interface personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Utiliser l'une des implémentations de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Définir l'objet PdfSaveOptions par défaut
  	var options = new PdfSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

Convertir la source HTML présentée par du contenu en ligne en PDF. Le résultat est les données de sortie générées par l'implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion PDF

Le Portable Document Format (PDF) est un type de document créé par Adobe au début des années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et d'autres matériels de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. Un fichier PDF est un ensemble d'octets qui peuvent être regroupés en jetons selon les règles de syntaxe définies par les spécifications PDF. Une fois qu'un ou plusieurs jetons sont combinés pour former des entités syntaxiques de niveau supérieur, principalement des objets, qui sont les valeurs de données de base à partir desquelles un document PDF est construit.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Autres conversions de formats populaires

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) gratuit en ligne qui convertit HTML en PDF avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Utiliser l'une des implémentations de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Définir l'objet PdfSaveOptions par défaut
 	var options = new PdfSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

Convertir la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est un fichier mhtml (.mht) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Chemin complet du fichier mhtml (.mht) en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat MHTML avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) gratuit en ligne qui convertit HTML en MHTML avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Former le document HTML
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Créer un document HTML de plusieurs manières
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// Définir l'objet MHTMLSaveOptions par défaut
 		var options = new MHTMLSaveOptions();

		// Chemin du fichier résultat du formulaire
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// Initier le processus de conversion
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

Convertir la source HTML présentée par URL. Le résultat est un fichier mhtml (.mht) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Chemin complet du fichier mhtml (.mht) en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat MHTML avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) gratuit en ligne qui convertit HTML en MHTML avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Définir l'objet MHTMLSaveOptions par défaut
	var options = new MHTMLSaveOptions();

	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Initier le processus de conversion
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

Convertir la source HTML présentée par URL. Le résultat est un fichier mhtml (.mht) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Chemin complet du fichier mhtml (.mht) en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat MHTML avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) gratuit en ligne qui convertit HTML en MHTML avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Définir l'objet MHTMLSaveOptions par défaut
	var options = new MHTMLSaveOptions();

	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

Convertir la source HTML présentée par le chemin complet du fichier en MHTML. Le résultat est un fichier mhtml (.mht) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Chemin complet du fichier mhtml (.mht) en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat MHTML avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) gratuit en ligne qui convertit HTML en MHTML avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Définir l'objet MHTMLSaveOptions par défaut
	var options = new MHTMLSaveOptions();

	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Initier le processus de conversion
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

Convertir la source HTML présentée par le chemin complet du fichier en MHTML. Le résultat est un fichier mhtml (.mht) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Chemin complet du fichier mhtml (.mht) en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat MHTML avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) gratuit en ligne qui convertit HTML en MHTML avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Définir l'objet MHTMLSaveOptions par défaut
	var options = new MHTMLSaveOptions();

	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

Convertir la source HTML présentée par du contenu en ligne en MHTML. Le résultat est un fichier mhtml (.mht) créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Chemin complet du fichier mhtml (.mht) en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie du résultat ou utilisez une implémentation d'interface connue ou personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant que résultat MHTML avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) gratuit en ligne qui convertit HTML en MHTML avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Définir l'objet d'options de sauvegarde par défaut
  	var options = new MHTMLSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

Convertir la source HTML présentée par du contenu en ligne en MHTML. Le résultat est un fichier mhtml (.mht) créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Chemin complet du fichier mhtml (.mht) en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat MHTML avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) gratuit en ligne qui convertit HTML en MHTML avec une haute qualité, facile et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Définir l'objet d'options de sauvegarde par défaut
 	var options = new MHTMLSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

Convertir la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est un fichier markdown (.md) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Chemin complet du fichier md en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat Markdown avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML vers Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en ligne gratuit qui convertit le HTML en MD avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Chemin du fichier source du formulaire
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// Chemin du fichier résultat du formulaire
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// Définir une instance d'objet d'options de sauvegarde
			var options = new MarkdownSaveOptions();

			// Initier le processus de conversion
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

Convertir la source HTML présentée par URL. Le résultat est un fichier markdown (.md) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Chemin complet du fichier md en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat Markdown avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML vers Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en ligne gratuit qui convertit le HTML en MD avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// Chemin du fichier résultat du formulaire
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Définir une instance d'objet d'options de sauvegarde
	var options = new MarkdownSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

Convertir la source HTML présentée par URL. Le résultat est un fichier markdown (.md) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Chemin complet du fichier md en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat Markdown avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML vers Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en ligne gratuit qui convertit le HTML en MD avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// Chemin du fichier résultat du formulaire
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Définir une instance d'objet d'options de sauvegarde
	var options = new MarkdownSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

Convertir la source HTML présentée par le chemin complet du fichier en Markdown. Le résultat est un fichier markdown (.md) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Chemin complet du fichier md en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat Markdown avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML vers Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en ligne gratuit qui convertit le HTML en MD avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// Chemin du fichier résultat du formulaire
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Définir une instance d'objet d'options de sauvegarde
	var options = new MarkdownSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

Convertir la source HTML présentée par le chemin complet du fichier en Markdown. Le résultat est un fichier markdown (.md) créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Chemin complet du fichier md en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat Markdown avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML vers Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en ligne gratuit qui convertit le HTML en MD avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// Chemin du fichier résultat du formulaire
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Définir une instance d'objet d'options de sauvegarde
	var options = new MarkdownSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

Convertir la source HTML présentée par du contenu en ligne en Markdown. Le résultat est un fichier mhtml (.mht) créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Chemin complet du fichier md en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat Markdown avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML vers Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en ligne gratuit qui convertit le HTML en MD avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Définir l'objet d'options de sauvegarde par défaut
  	var options = new MarkdownSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

Convertir la source HTML présentée par du contenu en ligne en Markdown. Le résultat est un fichier mhtml (.mht) créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Chemin complet du fichier md en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Autres conversions de formats populaires

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat Markdown avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [HTML vers Markdown](https://products.aspose.app/html/en/conversion/html-to-md) en ligne gratuit qui convertit le HTML en MD avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Définir l'objet d'options de sauvegarde par défaut
 	var options = new MarkdownSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

Convertir la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est un fichier xps créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Chemin du fichier source du formulaire
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// Chemin du fichier résultat du formulaire
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// Créer un document HTML de plusieurs manières
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// Définir une instance d'objet d'options de sauvegarde
        	var options = new XpsSaveOptions();

        	// Initier le processus de conversion
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

Convertir la source HTML présentée par URL. Le résultat est un fichier xps créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Chemin du fichier résultat du formulaire
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new XpsSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

Convertir la source HTML présentée par URL. Le résultat est un fichier xps créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Chemin du fichier résultat du formulaire
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new XpsSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

Convertir la source HTML présentée par le chemin complet du fichier en XPS. Le résultat est un fichier xps créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Chemin du fichier résultat du formulaire
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new XpsSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

Convertir la source HTML présentée par le chemin complet du fichier en XPS. Le résultat est un fichier xps créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Chemin du fichier résultat du formulaire
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new XpsSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

Convertir la source HTML présentée par du contenu en ligne en XPS. Le résultat est un fichier xps créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Définir l'objet d'options de sauvegarde par défaut
  	var options = new XpsSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

Convertir la source HTML présentée par du contenu en ligne en XPS. Le résultat est un fichier xps créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Définir l'objet d'options de sauvegarde par défaut
 	var options = new XpsSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

Convertir la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Chemin du fichier résultat du formulaire
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// Créer un document HTML de plusieurs manières
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// Définir une instance d'objet d'options de sauvegarde
    	var options = new XpsSaveOptions();

		// Utilisez l'une des implémentations connues de ICreateStreamProvider
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// Initier le processus de conversion
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

Convertir la source HTML présentée par une URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL du document source HTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Chemin du fichier résultat du formulaire
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Utiliser l'une des implémentations de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new XpsSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

Convertir la source HTML présentée par une URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL source HTML - fournit une représentation d'objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Chemin du fichier résultat du formulaire
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Utiliser l'une des implémentations de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new XpsSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

Convertir la source HTML présentée par le chemin complet du fichier en XPS. Le résultat est des données de sortie créées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation d'interface personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Chemin du fichier résultat du formulaire
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Utiliser l'une des implémentations de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new XpsSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

Convertir la source HTML présentée par le chemin complet du fichier en XPS. Le résultat est des données de sortie créées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Chemin du fichier résultat du formulaire
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Utiliser l'une des implémentations de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new XpsSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

Convertissez la source HTML présentée par du contenu en ligne en XPS. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps) qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Utiliser l'une des implémentations de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Définir l'objet d'options de sauvegarde par défaut
  	var options = new XpsSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

Convertissez la source HTML présentée par du contenu en ligne en XPS. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation d'interface personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Remarques

Comment convertir HTML en XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversion XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Convertir HTML en XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de n'importe quelle manière. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface connue ou personnalisée de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres personnalisés ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un [convertisseur HTML vers XPS](https://products.aspose.app/html/en/conversion/html-to-xps) en ligne gratuit qui convertit le HTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Essayez d'utiliser d'autres conversions de formats populaires

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Utiliser l'une des implémentations de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Définir l'objet d'options de sauvegarde par défaut
 	var options = new XpsSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

Convertissez la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "source.html");

// Chemin du fichier résultat du formulaire
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// Définir une instance d'objet d'options de sauvegarde
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initier le processus de conversion
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

Convertir la source HTML présentée par URL. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL source HTML - fournit une représentation d'objet d'un identifiant universel (URL). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Chemin du fichier résultat du formulaire
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initier le processus de conversion
	Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

Convertir la source HTML présentée par URL. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL source HTML - fournit une représentation d'objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Chemin du fichier résultat du formulaire
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

Convertir la source HTML présentée par le chemin complet du fichier en image. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | ImageSaveOptions | Pour en savoir plus sur la classe [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/), veuillez lire l'article [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Chemin du fichier résultat du formulaire
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Définissez une instance d'objet d'options d'enregistrement. PNG est le format d'image par défaut.
	var options = new ImageSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

Convertir la source HTML présentée par le chemin complet du fichier en image. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | Pour en savoir plus sur la classe [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/), veuillez lire l'article [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Chemin du fichier résultat du formulaire
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Définissez une instance d'objet d'options d'enregistrement. PNG est le format d'image par défaut.
	var options = new ImageSaveOptions();

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

Convertir la source HTML présentée par du contenu en ligne en image. Le résultat est un fichier image créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | ImageSaveOptions | Nouvelles options d'image créées comme le format, la résolution, etc. Voir la classe [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Définir l'objet d'options de sauvegarde par défaut
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

Convertir la source HTML présentée par du contenu en ligne en image. Le résultat est un fichier image créé par le chemin du fichier de sortie.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | Nouvelles options d'image créées comme le format, la résolution, etc. Voir la classe [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Définir l'objet d'options de sauvegarde par défaut
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

Convertir la source HTML présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result");

	// Créer un document HTML de plusieurs manières
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// Définir une instance d'objet d'options de sauvegarde
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// Utiliser l'une des implémentations de ICreateStreamProvider
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// Initier le processus de conversion
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

Convertir la source HTML présentée par une URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL source HTML - fournit une représentation d'objet d'un identifiant universel (URL). |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation d'interface personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Chemin du fichier résultat du formulaire
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utiliser l'une des implémentations de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initier le processus de conversion
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

Convertir la source HTML présentée par une URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL source HTML - fournit une représentation d'objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface, qui sera utilisée pour obtenir un flux de sortie. Plus d'informations sur les fournisseurs dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Créer une URL basée sur le chemin du fichier d'entrée
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Chemin du fichier résultat du formulaire
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utiliser l'une des implémentations de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

Convertissez la source HTML présentée par le chemin complet du fichier en image. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source HTML. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface, qui sera utilisée pour obtenir un flux de sortie. Plus d'informations sur les fournisseurs dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Chemin du fichier résultat du formulaire
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utilisez l'une des implémentations connues de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initier le processus de conversion
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

Convertissez la source HTML présentée par le chemin complet du fichier en image. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface, qui sera utilisée pour obtenir un flux de sortie. Plus d'informations sur les fournisseurs dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// Chemin du fichier résultat du formulaire
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Définir une instance d'objet d'options de sauvegarde
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utilisez l'une des implémentations connues de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

Convertissez la source HTML présentée par du contenu en ligne en image. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation d'interface personnalisée [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Définir l'objet d'options de sauvegarde par défaut
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utilisez l'une des implémentations connues de ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initier le processus de conversion
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

Convertissez la source HTML présentée par du contenu en ligne en image. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu HTML en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration `](../../../com.aspose.html/configuration/) qui est utilisé pour définir les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. Plus d'informations sur les fournisseurs dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir du HTML en image

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

L'atout principal d'Aspose.HTML est la fonction de conversion. La conversion entre formats est nécessaire pour diverses raisons : travailler dans un format familier et pratique ou profiter de différents formats pour des tâches spécifiques. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions HTML vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), et [MD](https://docs.fileformat.com/word-processing/md/).

Cet article fournit des informations sur la liste des conversions HTML prises en charge et sur la façon de les réaliser en utilisant la classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles d'utilisation. Dans le guide du Convertisseur HTML, vous trouverez les articles suivants :

Conversions d'images

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Autres conversions de formats populaires

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Convertir le HTML en image

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier HTML local existant ou une URL distante comme source de conversion. Vous pouvez même définir du contenu HTML en ligne comme source de conversion ou créer un document HTML (HTMLDocument) de quelque manière que ce soit. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) requis. Par défaut, la propriété Format est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertHTML() de la classe Converter pour enregistrer le HTML en tant qu'image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseurs HTML en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) qui convertit le HTML en images avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formater le contenu HTML en ligne
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Définir l'objet d'options de sauvegarde par défaut
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Utilisez l'une des implémentations connues de ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Initier le processus de conversion avec la configuration par défaut
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

Convertir le document html en texte. Le résultat est un fichier TXT.

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | HTMLDocument | Source de conversion. |
| options | TextSaveOptions | Options de conversion. |
| outputPath | String | Chemin du fichier de sortie. |

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

Convertir le document html en texte. Le résultat est un fichier TXT.

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | L'URL du document. |
| options | TextSaveOptions | Options de conversion. |
| outputPath | String | Chemin du fichier de sortie. |

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

Convertir le document html en texte. Le résultat est un fichier TXT.

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | L'URL du document. |
| configuration | Configuration | La configuration de l'environnement. |
| options | TextSaveOptions | Options de conversion. |
| outputPath | String | Chemin du fichier de sortie. |

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

Convertir le document html en texte. Le résultat est un fichier TXT.

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | TextSaveOptions | Options de conversion. |
| outputPath | String | Chemin du fichier de sortie. |

### Voir aussi

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

Convertir le document html en texte. Le résultat est un fichier TXT.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin source du fichier HTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. |
| options | TextSaveOptions | Options de conversion. |
| outputPath | String | Chemin du fichier de sortie. |

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

Convertir le document html en texte. Le résultat est un fichier TXT.

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Contenu HTML de chaîne en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | TextSaveOptions | Options de conversion. |
| outputPath | String | Chemin du fichier de sortie. |

### Voir aussi

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

Convertir le document html en texte. Le résultat est un fichier TXT.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Contenu HTML de chaîne en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. |
| options | TextSaveOptions | Options de conversion. |
| outputPath | String | Chemin du fichier de sortie. |

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
