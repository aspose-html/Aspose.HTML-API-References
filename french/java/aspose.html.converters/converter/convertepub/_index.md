---
title: "Converter.ConvertEPUB"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Converter. Convertissez la source EPUB présentée par un flux d'entrée de données. Le résultat est un fichier créé à l'emplacement du chemin de sortie."
type: docs

url: /fr/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Convertir la source EPUB présentée par un flux d'entrée de données. Le résultat est un fichier créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| options | ImageSaveOptions | Nouvelles options d'image créées comme format, résolution, etc. Voir la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) et la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Définissez l'URL en fonction du fichier EPUB existant au chemin spécifié. Définissez le chemin du fichier de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez également transmettre l'objet ImageSaveOptions et l'objet Configuration à la conversion d'image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Ouvrir le fichier existant en lecture sous forme de flux
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Définir le chemin du fichier de sortie
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Définir l'instance des options par défaut
var options = new ImageSaveOptions();

// Initier le processus de conversion
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Convertir la source EPUB présentée par le chemin complet du fichier. Le résultat est un fichier image créé à partir du chemin du fichier de sortie. Le format d'image est spécifié par l'objet ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB en tant que paramètre d'entrée. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Définissez l'URL en fonction du fichier EPUB existant au chemin spécifié. Définissez le chemin du fichier de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez également transmettre l'objet ImageSaveOptions et l'objet Configuration à la conversion d'image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Définir l'instance par défaut de l'objet ImageSaveOptions
var options = new ImageSaveOptions(); 

// Initier le processus de conversion
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Convertir la source EPUB définie par URL. Le résultat est un fichier image créé à partir du chemin du fichier de sortie. Le format d'image est spécifié par l'objet ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Définissez l'URL en fonction du fichier EPUB existant au chemin spécifié. Définissez le chemin du fichier de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez également transmettre l'objet ImageSaveOptions et l'objet Configuration à la conversion d'image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Créer une URL basée sur le chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Définir l'instance des options par défaut
var options = new ImageSaveOptions();

// Initier le processus de conversion
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Convertir la source EPUB présentée par le flux d'entrée de données. Le résultat est un fichier image créé à partir du chemin du fichier de sortie. Le format d'image est spécifié par l'objet ImageSaveOptions.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Définissez l'URL en fonction du fichier EPUB existant au chemin spécifié. Définissez le chemin du fichier de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez également transmettre l'objet ImageSaveOptions et l'objet Configuration à la conversion d'image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Ouvrir le fichier existant en lecture sous forme de flux
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Définir le chemin du fichier de sortie
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Définir l'instance des options par défaut
var options = new ImageSaveOptions();

// Initier le processus de conversion avec l'objet de configuration par défaut
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Convertir la source EPUB présentée par le chemin complet du fichier. Le résultat est un fichier image créé à partir du chemin du fichier de sortie. Le format d'image est spécifié par l'objet ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB en tant que paramètre d'entrée. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte de [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) qui est utilisé pour définir les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Définissez l'URL en fonction du fichier EPUB existant au chemin spécifié. Définissez le chemin du fichier de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez également transmettre l'objet ImageSaveOptions et l'objet Configuration à la conversion d'image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Définir l'instance par défaut de l'objet ImageSaveOptions
var options = new ImageSaveOptions(); 

// Initier le processus de conversion avec l'objet de configuration par défaut
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Convertir la source EPUB définie par URL. Le résultat est un fichier image créé à partir du chemin du fichier de sortie. Le format d'image est spécifié par l'objet ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), les [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), le [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype), etc. Voir la classe [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions). |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Définissez l'URL en fonction du fichier EPUB existant au chemin spécifié. Définissez le chemin du fichier de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez également transmettre l'objet ImageSaveOptions et l'objet Configuration à la conversion d'image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Créer une URL basée sur le chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Définir le chemin du fichier de sortie
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Définir l'instance des options par défaut
var options = new ImageSaveOptions(); 

// Initier le processus de conversion avec l'objet de configuration par défaut
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Convertir la source epub présentée par le [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) d'entrée en image. Le résultat est un fichier image généré par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Ouvrir un fichier EPUB existant. Dans l'exemple, nous utilisons la méthode OpenRead() de la classe System.IO.FileStream pour ouvrir et lire un fichier EPUB depuis le système de fichiers au chemin spécifié. Utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez transmettre le flux d'entrée EPUB, ImageSaveOptions et le flux de sortie à la méthode ConvertEPUB() pour la conversion d'EPUB en image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Créer l'instance des options par défaut  
var options = new ImageSaveOptions();    

// Initier le processus de conversion  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Convertir la source EPUB présentée par le chemin du fichier en image. Le résultat est un fichier image créé par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | ImageSaveOptions | Nouvelles options d'image créées comme format, résolution, etc. Voir la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) et la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface, qui sera utilisée pour obtenir un flux de sortie. Plus d'informations sur les fournisseurs dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Ouvrir un fichier EPUB existant. Dans l'exemple, nous utilisons la méthode OpenRead() de la classe System.IO.FileStream pour ouvrir et lire un fichier EPUB depuis le système de fichiers au chemin spécifié. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Créez un nouvel objet ImageSaveOptions avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez transmettre le flux d'entrée EPUB, ImageSaveOptions et le flux de sortie à la méthode ConvertEPUB() pour la conversion d'EPUB en image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

EPUB en JPG en deux lignes de code

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Ouvrir un fichier EPUB existant en lecture.
import var stream = File.OpenRead(DataDir + "input.epub");

// Appelez la méthode ConvertEPUB pour convertir le code EPUB en image JPG      
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Convertissez la source epub présentée par URL en image. Le résultat est un fichier image créé par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la classe [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implémentation de l'interface, qui sera utilisée pour obtenir un flux de sortie. Plus d'informations sur les fournisseurs dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Ouvrir un fichier EPUB existant. Dans l'exemple, nous utilisons la méthode OpenRead() de la classe System.IO.FileStream pour ouvrir et lire un fichier EPUB depuis le système de fichiers au chemin spécifié. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Créez un nouvel objet ImageSaveOptions avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez transmettre le flux d'entrée EPUB, ImageSaveOptions et le flux de sortie à la méthode ConvertEPUB() pour la conversion d'EPUB en image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  

// Créer une URL basée sur le chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Créer l'instance des options par défaut  
var options = new ImageSaveOptions();

// Initier le processus de conversion  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Convertir la source epub présentée par le [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) d'entrée en image. Le résultat est un fichier image généré par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| fournisseur | ICreateStreamProvider | Implémentation de l'interface, qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Ouvrir un fichier EPUB existant. Dans l'exemple, nous utilisons la méthode OpenRead() de la classe System.IO.FileStream pour ouvrir et lire un fichier EPUB depuis le système de fichiers au chemin spécifié. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Créez un nouvel objet ImageSaveOptions avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez transmettre le flux d'entrée EPUB, ImageSaveOptions et le flux de sortie à la méthode ConvertEPUB() pour la conversion d'EPUB en image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Créer l'instance des options par défaut  
var options = new ImageSaveOptions();    


// Initiez le processus de conversion avec la configuration par défaut  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Convertissez la source epub présentée par le chemin du fichier en image. Le résultat est un fichier image créé par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Source EPUB définie par le chemin du fichier. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface, qui sera utilisée pour obtenir un flux de sortie. Voir un exemple d'implémentation ICreateStreamProvider dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Ouvrir un fichier EPUB existant. Dans l'exemple, nous utilisons la méthode OpenRead() de la classe System.IO.FileStream pour ouvrir et lire un fichier EPUB depuis le système de fichiers au chemin spécifié. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Créez un nouvel objet ImageSaveOptions avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez transmettre le flux d'entrée EPUB, ImageSaveOptions et le flux de sortie à la méthode ConvertEPUB() pour la conversion d'EPUB en image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Définir l'instance par défaut de l'objet ImageSaveOptions
var options = new ImageSaveOptions(); 

// Initier le processus de conversion avec l'objet de configuration par défaut
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Convertir la source epub présentée par URL en image. Le résultat est un fichier image créé par l'implémentation de l'interface [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet ImageSaveOptions vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface, qui sera utilisée pour obtenir un flux de sortie. Voir un exemple d'implémentation ICreateStreamProvider dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Remarques

Comment convertir EPUB en image

EPUB est un format de fichier de livre électronique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum (IDPF) et est maintenant pris en charge par de nombreux lecteurs électroniques et applications logicielles.

Convertir des fichiers EPUB au format PNG peut être utile si vous devez inclure des fichiers dans une présentation PowerPoint ou les envoyer par e‑mail. Veuillez les convertir au format image et les utiliser comme vous le souhaitez ! Vous pouvez utiliser des paramètres de conversion supplémentaires pour obtenir le résultat désiré.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe Converter qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide du convertisseur EPUB, vous trouverez les articles suivants :

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Convertir EPUB en image

Pour convertir le format de fichier EPUB en image, vous devez suivre quelques étapes :

Ouvrir un fichier EPUB existant. Dans l'exemple, nous utilisons la méthode OpenRead() de la classe System.IO.FileStream pour ouvrir et lire un fichier EPUB depuis le système de fichiers au chemin spécifié. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Créez un nouvel objet ImageSaveOptions avec le ImageFormat requis. Par défaut, la propriété Format est PNG. Utilisez la méthode ConvertEPUB() de la classe Converter pour enregistrer l'EPUB en tant qu'image. Vous devez transmettre le flux d'entrée EPUB, ImageSaveOptions et le flux de sortie à la méthode ConvertEPUB() pour la conversion d'EPUB en image. Convertisseurs EPUB en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) qui convertit les fichiers EPUB en image PNG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Vous pourriez également être intéressé par la conversion de formats d'image spécifiques

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Formez l'URL source à partir du chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Créer l'instance des options par défaut  
var options = new ImageSaveOptions();

// Initier le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Convertir la source epub présentée par le flux d'entrée en xps. Le résultat est un fichier xps défini par le chemin complet.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux d'entrée comme source de conversion. Voir la spécification du Stream dans la [source officielle](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de la page, les marges, le CSS, etc. |
| outputPath | String | Chemin complet du fichier .xps en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec plusieurs paramètres préférés tels que la taille de la page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en fichier xps. Vous devez fournir la source EPUB, XpsSaveOptions, et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Ouvrez un fichier EPUB existant pour la lecture
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Préparez un chemin pour enregistrer le fichier converti 
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Créez une instance de XpsSaveOptions. Configurez la taille de la page et changez la couleur d'arrière-plan en LightGray 
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // Appelez la méthode ConvertEPUB pour convertir l'EPUB en XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Convertir la source epub présentée par le chemin du fichier EPUB d'entrée en xps. Le résultat est un fichier xps défini par le chemin complet.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`taille de la page`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`marges`](../../../com.aspose.html.drawing/page/margin/), le [`type de média CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier .xps en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec plusieurs paramètres préférés tels que la taille de la page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en fichier xps. Vous devez fournir la source EPUB, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/), et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Initier le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Convertir la source epub présentée par URL en fichier xps défini par le chemin complet. Voir [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`taille de la page`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`marges`](../../../com.aspose.html.drawing/page/margin/), le [`type de média CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier .xps en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion.

Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Formez l'URL source à partir du chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Initier le processus de conversion
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Convertir la source epub présentée par le [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) d'entrée en xps. Le résultat est un fichier xps défini par le chemin complet.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`taille de la page`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`marges`](../../../com.aspose.html.drawing/page/margin/), le [`type de média CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier .xps en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Ouvrez un fichier EPUB existant pour la lecture
import var stream = File.OpenRead(DataDir + "input.epub");

// Préparez un chemin pour l'enregistrement du fichier converti
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Initialisez XpsSaveOptions
var options = new XpsSaveOptions();
   
// Appelez la méthode ConvertEPUB pour convertir l'EPUB en XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Convertir la source epub présentée par le chemin du fichier EPUB d'entrée en xps. Le résultat est un fichier xps défini par le chemin complet.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte de [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) qui est utilisé pour définir les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de la page, les marges, le CSS, etc. |
| outputPath | String | Chemin complet du fichier .xps en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Initier le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Convertir la source epub présentée par URL en fichier xps défini par le chemin complet. Voir [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte de [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) qui est utilisé pour définir les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de la page, les marges, le CSS, etc. |
| outputPath | String | Chemin complet du fichier .xps en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formez l'URL source à partir du chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Lancez le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Convertissez la source EPUB présentée par le [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) d'entrée en xps. Le résultat est des données de sortie xps définies par une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`taille de page`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`marges`](../../../com.aspose.html.drawing/page/margin/), le [`type de média CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface qui sera utilisée pour obtenir un flux de sortie. Voir un exemple d'implémentation de ICreateStreamProvider dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Créez une instance de MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Ouvrez un fichier EPUB existant pour la lecture
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Préparez un chemin pour enregistrer le fichier converti 
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Convertissez EPUB en XPS en utilisant la classe MemoryStreamProvider
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Obtenez l'accès au flux mémoire contenant les données du résultat
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Videz les données du résultat dans le fichier de sortie
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Convertissez la source EPUB présentée par le chemin du fichier EPUB d'entrée en xps. Le résultat est des données de sortie xps définies par une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de la page, les marges, le CSS, etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec plusieurs paramètres préférés tels que la taille de la page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en fichier xps. Vous devez fournir la source EPUB, XpsSaveOptions, et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Initier le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Convertissez la source EPUB présentée par une URL en fichier xps défini par un chemin complet. Le résultat est des données de sortie xps définies par une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de la page, les marges, le CSS, etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formez l'URL source à partir du chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Initier le processus de conversion
Converter.ConvertEPUB(sourceUrl, options, sp);
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

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Convertissez la source EPUB présentée par le [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) d'entrée en xps. Le résultat est des données de sortie xps définies par une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`taille de page`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`marges`](../../../com.aspose.html.drawing/page/margin/), le [`type de média CSS`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Initier le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Convertissez la source EPUB présentée par le chemin du fichier EPUB d'entrée en xps. Le résultat est des données de sortie xps définies par une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de la page, les marges, le CSS, etc. |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Initier le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Convertissez la source EPUB présentée par une URL en fichier xps défini par un chemin complet. Le résultat est des données de sortie xps définies par une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | Options de conversion. L'utilisation de l'objet [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`taille de page`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`marges`](../../../com.aspose.html.drawing/page/margin/), le [`type de média CSS`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Remarques

Comment convertir EPUB en XPS

Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise XML pour la mise en page, l'apparence et les informations d'impression d'un document.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique EPUB Converter XPS, vous trouverez l'article suivant :

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Convertir EPUB en XPS

Pour convertir le format de fichier EPUB en XPS, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. À titre d'exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet XpsSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe XpsSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier xps. Vous devez fournir la date source de l'EPUB, XpsSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB vers XPS en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formez l'URL source à partir du chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Créer l'instance des options par défaut  
var options = new XpsSaveOptions();

// Initier le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Convertir le fichier source EPUB présenté par son chemin complet vers DOCX. Le résultat est un fichier docx défini par le chemin complet.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Source de conversion présentée par le [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) d'entrée. |
| options | DocSaveOptions | Options de conversion. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) L'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier .docx en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Créer l'instance des options par défaut  
var options = new DocSaveOptions();   

// Initier le processus de conversion
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Convertir la source EPUB présentée par le chemin complet du fichier en DOCX. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB en tant que paramètre d'entrée. |
| options | DocSaveOptions | Options de conversion. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) L'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier .docx en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Définir l'instance des options par défaut
var options = new DocSaveOptions();

// Lancer le processus de conversion
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Convertir la source EPUB présentée par URL. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| options | DocSaveOptions | L'utilisation de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), les [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier .docx en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formez l'URL source à partir du chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Définir l'instance des options par défaut
var options = new DocSaveOptions();

// Lancer le processus de conversion
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Convertir la source EPUB présentée par le flux d'entrée de données. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | Options de conversion. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) L'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier .docx en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Créer l'instance des options par défaut  
var options = new DocSaveOptions();   

// Lancez le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Convertir la source EPUB présentée par le chemin complet du fichier en DOCX. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | Options de conversion. [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions) l'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de page, les marges, le CSS, etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier .docx en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Définir l'instance des options par défaut
var options = new DocSaveOptions();

// Lancer le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Convertir la source EPUB présentée par URL. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), les [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier .docx en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formez l'URL source à partir du chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Chemin du fichier de résultat de la conversion du formulaire
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Créer l'instance des options par défaut  
var options = new DocSaveOptions();

// Initiez le processus de conversion avec la configuration par défaut  
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Convertir la source EPUB en flux d'entrée vers DOCX. Le résultat est un fichier docx créé par l'implémentation de ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| options | DocSaveOptions | Options de conversion. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) L'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Créer l'instance des options par défaut  
var options = new DocSaveOptions();   

// Initier le processus de conversion
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Convertir la source EPUB présentée par le chemin complet du fichier en DOCX. Le résultat est les données de sortie générées par l'implémentation de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | DocSaveOptions | Options de conversion. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) L'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Créer l'instance des options par défaut  
var options = new DocSaveOptions ();   

// Initier le processus de conversion  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Convertir la source EPUB présentée par URL. Le résultat est des données de sortie générées par l'implémentation de l'interface ICreateStreamProvider.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| options | DocSaveOptions | L'utilisation de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de page, les marges, les résolutions, le CSS, etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet DocSaveOptions avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formez l'URL source à partir du chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Créer l'instance des options par défaut  
var options = new DocSaveOptions ();   

// Initier le processus de conversion
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Convertir la source EPUB présentée par le flux d'entrée de données. Le résultat est des données de sortie générées par l'implémentation de l'interface ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), les [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Créer l'instance des options par défaut  
var options = new DocSaveOptions();   

// Lancez le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Convertir la source EPUB présentée par le chemin complet du fichier en DOCX. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | Options de conversion. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) L'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Créer l'instance des options par défaut  
var options = new DocSaveOptions ();   

// Initier le processus de conversion  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Convertir la source EPUB présentée par URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte de [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) qui est utilisé pour définir les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), les [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Remarques

Comment convertir EPUB en DOCX

DOCX est un format bien connu pour les documents Microsoft Word. Ce format est populaire car il prend en charge un large éventail de fonctionnalités de mise en forme et offre aux utilisateurs de nombreuses options pour rédiger tout type de document. Les fichiers DOCX peuvent être ouverts avec Word 2007 et les versions ultérieures, mais pas avec les versions antérieures de MS Word, qui ne prennent en charge que les extensions de fichier DOC. La conversion d'EPUB en DOCX est souvent nécessaire pour tirer parti du format DOCX pour des tâches spécifiques des utilisateurs.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers DOCX, vous trouverez l'article suivant :

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en DOCX

Pour convertir le format de fichier EPUB en DOCX, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec plusieurs paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe DocSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier docx. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'URL, l'instance DocSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour initier le processus de conversion. Vous pouvez utiliser la configuration qui représente le [`configuration`](../../../com.aspose.html/configuration/) objet de contexte utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en DOCX en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) qui convertit les fichiers EPUB en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Créer une URL basée sur le chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Créer l'instance des options par défaut  
var options = new DocSaveOptions();   

// Lancez le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

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

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Convertir la source EPUB présentée par un flux d'entrée de données. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Chemin du fichier source EPUB en tant que paramètre d'entrée. |
| options | PdfSaveOptions | Options de conversion. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) l'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier .pdf en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Chemin du fichier de résultat du formulaire  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Créer l'instance des options par défaut  
var options = new PdfSaveOptions();   

// Initier le processus de conversion  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Convertir la source EPUB présentée par le chemin complet du fichier en PDF. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | PdfSaveOptions | Options de conversion. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) l'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier .pdf en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Définir l'instance des options par défaut
var options = new PdfSaveOptions();

// Lancer le processus de conversion
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Convertir la source EPUB présentée par URL. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| options | PdfSaveOptions | L'utilisation de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), les [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier .pdf en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Créer une URL basée sur le chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Définir l'instance des options par défaut
var options = new com.aspose.html.saving.PdfSaveOptions();

// Lancer le processus de conversion
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Convertir la source EPUB présentée par un flux d'entrée de données. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | Options de conversion. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) l'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier .pdf en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Chemin du fichier de résultat du formulaire  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Créer l'instance des options par défaut  
var options = new PdfSaveOptions();   

// Lancez le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Convertir la source EPUB présentée par un flux d'entrée de données. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | Options de conversion. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) l'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier .pdf en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Définir l'instance des options par défaut
var options = new PdfSaveOptions();

// Lancer le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Convertir la source EPUB présentée par URL. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte de [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) qui est utilisé pour définir les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), les [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier .pdf en tant que résultat de conversion. |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;
import com.aspose.html.converters;
...  
// Créer une URL basée sur le chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Former le chemin du fichier de résultat de sortie
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Définir l'instance des options par défaut
var options = new PdfSaveOptions();

// Lancer le processus de conversion avec la configuration par défaut
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Convertir la source EPUB présentée par un flux d'entrée de données. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| options | PdfSaveOptions | Options de conversion. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) l'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Créer l'instance des options par défaut  
var options = new PdfSaveOptions ();   

// Initier le processus de conversion  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Convertir la source EPUB présentée par le chemin complet du fichier en PDF. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | PdfSaveOptions | Options de conversion. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) l'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Créer l'instance des options par défaut  
var options = new PdfSaveOptions();   

// Initier le processus de conversion  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Convertir la source EPUB présentée par URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| options | PdfSaveOptions | L'utilisation de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), les [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;   
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Créer une URL basée sur le chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Définir l'instance des options par défaut
var options = new PdfSaveOptions();

// Initier le processus de conversion
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Convertir la source EPUB présentée par un flux d'entrée de données. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux d'entrée comme source de conversion. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | Options de conversion. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) l'utilisation de l'objet permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

L'atout principal d'Aspose.HTML est la fonction de conversion. EPUB est un format ouvert basé sur XML pour les livres numériques et les publications, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package [`com.aspose.html.converters`](../) offre un accès facile aux méthodes de conversion. Il propose une large gamme de conversions [EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Ouvrir le fichier existant en lecture sous forme de flux  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Créer l'instance des options par défaut  
var options = new PdfSaveOptions ();   

// Lancer le processus de conversion avec l'objet de configuration par défaut  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Convertir la source EPUB présentée par le chemin complet du fichier en PDF. Le résultat est des données de sortie générées par l'implémentation de l'interface ICreateStreamProvider.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source EPUB. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte de [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) qui est utilisé pour définir les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | Options de conversion. L'utilisation de l'objet [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la taille de page, les marges, le CSS, etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Chemin du fichier source du formulaire
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Créer l'instance des options par défaut  
var options = new PdfSaveOptions();   

// Lancer le processus de conversion avec l'objet de configuration par défaut 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Convertir la source EPUB présentée par URL. Le résultat est les données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL source EPUB – fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte de [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) qui est utilisé pour définir les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu ; vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), les [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. Voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'interface [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) qui sera utilisée pour obtenir un flux de sortie. Voir un exemple avancé dans la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Remarques

Comment convertir EPUB en PDF

EPUB est un format de fichier de livre numérique qui fournit un format de publication numérique standard. Il a été créé par l'International Digital Publishing Forum ([IDPF](http://idpf.org/)), et il est désormais pris en charge par de nombreux lecteurs électroniques et applications logicielles. La conversion d'EPUB en PDF est souvent nécessaire pour profiter du format PDF. Le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des métadonnées, etc. Les fichiers PDF peuvent être ouverts dans Adobe Acrobat Reader/Writer et la plupart des navigateurs modernes comme Chrome, Safari, Firefox. Ils sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez également configurer les paramètres de sécurité pour le PDF.

Le principal atout d'Aspose.HTML est la fonctionnalité de conversion. EPUB est un format ouvert basé sur XML pour les livres et publications numériques, qui peut être visualisé et lu sur les smartphones, tablettes et ordinateurs. Le package com.aspose.html.converters offre un accès facile aux méthodes de conversion. Il fournit une large gamme de conversions d'[EPUB](https://docs.fileformat.com/ebook/epub/) vers des formats populaires, tels que [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) et [GIF](https://docs.fileformat.com/image/gif/).

Cette section fournit des informations sur la liste des scénarios de conversion EPUB pris en charge et sur la façon de les réaliser en utilisant une classe [`Converter`](../) qui regroupe toutes les opérations de conversion de bas niveau dans une seule classe pour les rendre confortables et faciles à utiliser. Dans le guide spécifique du convertisseur EPUB vers PDF, vous trouverez l'article suivant :

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Convertir EPUB en PDF

Pour convertir le format de fichier EPUB en PDF, vous devez suivre quelques étapes :

Ouvrez un fichier EPUB existant. Par exemple, nous pouvons définir le chemin du fichier source comme premier paramètre de la méthode ConvertEPUB. En alternative, nous pouvons utiliser un flux d'entrée ou une instance d'objet Url. Utilisez une implémentation connue ou personnalisée de l'interface ICreateStreamProvider comme tampon de données de sortie. Nous pouvons également utiliser une alternative plus simple sous forme de chemin de fichier de sortie. Créez un nouvel objet PdfSaveOptions avec un certain nombre de paramètres préférés tels que la taille de page, les marges, le CSS, etc. Il est possible d'utiliser l'instance par défaut de la classe PdfSaveOptions. Utilisez la méthode ConvertEPUB() de la classe statique Converter pour enregistrer l'EPUB en tant que fichier PDF. Vous devez fournir la source EPUB sous forme de chemin de fichier ou de flux d'entrée ainsi que l'Url, l'instance PdfSaveOptions et le tampon de données de sortie sous n'importe quelle forme pour lancer le processus de conversion. Vous pouvez utiliser la configuration qui représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) utilisé pour configurer les paramètres d'environnement de l'application. Convertisseur EPUB en PDF en ligne

Aspose.HTML propose un convertisseur en ligne gratuit [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) qui convertit les fichiers EPUB en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Créer une URL basée sur le chemin du fichier d'entrée
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Se référer à l'implémentation de l'interface ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Définir l'instance des options par défaut
var options = new PdfSaveOptions();

// Initier le processus de conversion avec l'objet de configuration par défaut
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
