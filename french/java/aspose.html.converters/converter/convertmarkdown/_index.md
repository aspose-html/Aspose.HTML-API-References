---
title: "Converter.ConvertMarkdown"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Converter. Convertir la source MD markdown présentée par le flux d'entrée en html. Le résultat est HTMLDocument qui peut être enregistré via le chemin de fichier de sortie."
type: docs

url: /fr/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Convertir la source MD (markdown) présentée par le flux d'entrée en html. Le résultat est [`HTMLDocument`](../../../com.aspose.html/htmldocument/) qui peut être enregistré via le chemin de fichier de sortie.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MD (Markdown). |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Convertisseur Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Étapes de conversion

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier MD local existant ou créez un flux de données d'entrée comme source de conversion. Résultat de conversion. Vous pouvez obtenir directement [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou définir le chemin de fichier de sortie du résultat selon la signature de la méthode. Utilisez la méthode ConvertMarkdown() de la classe Converter pour enregistrer le MD en tant que résultat html. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre optionnel. Convertisseur MD en ligne

Vous pourriez également être intéressé par un convertisseur en ligne gratuit [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) qui convertit le MD en HTML avec une haute qualité, de façon simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes ! Vous pouvez également consulter d'autres convertisseurs MD en ligne : [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) et trouver les [convertisseurs MD vers image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Ouvrir le fichier source en flux
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initier le processus de conversion
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Enregistrer le résultat de la conversion
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Convertir la source MD (markdown) présentée par le flux d'entrée en html. Le résultat est [`HTMLDocument`](../../../com.aspose.html/htmldocument/) qui peut être enregistré via le chemin de fichier de sortie.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MD (Markdown). |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Convertisseur Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Étapes de conversion

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier MD local existant ou créez un flux de données d'entrée comme source de conversion. Résultat de conversion. Vous pouvez obtenir directement [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou définir le chemin de fichier de sortie du résultat selon la signature de la méthode. Utilisez la méthode ConvertMarkdown() de la classe Converter pour enregistrer le MD en tant que résultat html. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre optionnel. Convertisseur MD en ligne

Vous pourriez également être intéressé par un convertisseur en ligne gratuit [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) qui convertit le MD en HTML avec une haute qualité, de façon simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes ! Vous pouvez également consulter d'autres convertisseurs MD en ligne : [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) et trouver les [convertisseurs MD vers image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ouvrir le fichier source en flux
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initier le processus de conversion avec la configuration par défaut
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Enregistrer le résultat de la conversion
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Convertir la source MD (markdown) présentée par le flux d'entrée en html. Le résultat est un fichier html créé par le chemin du fichier de sortie.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MD (Markdown). |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Convertisseur Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Étapes de conversion

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier MD local existant ou créez un flux de données d'entrée comme source de conversion. Résultat de conversion. Vous pouvez obtenir directement [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou définir le chemin de fichier de sortie du résultat selon la signature de la méthode. Utilisez la méthode ConvertMarkdown() de la classe Converter pour enregistrer le MD en tant que résultat html. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre optionnel. Convertisseur MD en ligne

Vous pourriez également être intéressé par un convertisseur en ligne gratuit [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) qui convertit le MD en HTML avec une haute qualité, de façon simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes ! Vous pouvez également consulter d'autres convertisseurs MD en ligne : [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) et trouver les [convertisseurs MD vers image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ouvrir le fichier source en flux
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initier le processus de conversion
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Convertir la source MD (markdown) présentée par le flux d'entrée en html. Le résultat est un fichier html créé par le chemin du fichier de sortie.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MD (Markdown). |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Convertisseur Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Étapes de conversion

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier MD local existant ou créez un flux de données d'entrée comme source de conversion. Résultat de conversion. Vous pouvez obtenir directement [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou définir le chemin de fichier de sortie du résultat selon la signature de la méthode. Utilisez la méthode ConvertMarkdown() de la classe Converter pour enregistrer le MD en tant que résultat html. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre optionnel. Convertisseur MD en ligne

Vous pourriez également être intéressé par un convertisseur en ligne gratuit [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) qui convertit le MD en HTML avec une haute qualité, de façon simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes ! Vous pouvez également consulter d'autres convertisseurs MD en ligne : [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) et trouver les [convertisseurs MD vers image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Ouvrir le fichier source en flux
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Initier le processus de conversion avec la configuration par défaut
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Convertir la source MD (markdown) présentée par le chemin complet du fichier en html. Le résultat est [`HTMLDocument`](../../../com.aspose.html/htmldocument/) qui peut être enregistré via le chemin de fichier de sortie.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MD (Markdown). |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Convertisseur Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Étapes de conversion

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier MD local existant ou créez un flux de données d'entrée comme source de conversion. Résultat de conversion. Vous pouvez obtenir directement [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou définir le chemin de fichier de sortie du résultat selon la signature de la méthode. Utilisez la méthode ConvertMarkdown() de la classe Converter pour enregistrer le MD en tant que résultat html. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre optionnel. Convertisseur MD en ligne

Vous pourriez également être intéressé par un convertisseur en ligne gratuit [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) qui convertit le MD en HTML avec une haute qualité, de façon simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes ! Vous pouvez également consulter d'autres convertisseurs MD en ligne : [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) et trouver les [convertisseurs MD vers image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initier le processus de conversion
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Enregistrer le résultat de la conversion en fichier local
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Convertir la source MD (markdown) présentée par le chemin complet du fichier en html. Le résultat est [`HTMLDocument`](../../../com.aspose.html/htmldocument/) qui peut être enregistré via le chemin de fichier de sortie.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MD (Markdown). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Convertisseur Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Étapes de conversion

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier MD local existant ou créez un flux de données d'entrée comme source de conversion. Résultat de conversion. Vous pouvez obtenir directement [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou définir le chemin de fichier de sortie du résultat selon la signature de la méthode. Utilisez la méthode ConvertMarkdown() de la classe Converter pour enregistrer le MD en tant que résultat html. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre optionnel. Convertisseur MD en ligne

Vous pourriez également être intéressé par un convertisseur en ligne gratuit [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) qui convertit le MD en HTML avec une haute qualité, de façon simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes ! Vous pouvez également consulter d'autres convertisseurs MD en ligne : [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) et trouver les [convertisseurs MD vers image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initier le processus de conversion avec la configuration par défaut
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Enregistrer le résultat de la conversion en fichier local
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Convertir la source MD (markdown) présentée par le chemin complet du fichier en html. Le résultat est un fichier html créé par le chemin du fichier de sortie.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier Markdown source. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Convertisseur Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Étapes de conversion

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier MD local existant ou créez un flux de données d'entrée comme source de conversion. Résultat de conversion. Vous pouvez obtenir directement [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou définir le chemin de fichier de sortie du résultat selon la signature de la méthode. Utilisez la méthode ConvertMarkdown() de la classe Converter pour enregistrer le MD en tant que résultat html. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre optionnel. Convertisseur MD en ligne

Vous pourriez également être intéressé par un convertisseur en ligne gratuit [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) qui convertit le MD en HTML avec une haute qualité, de façon simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes ! Vous pouvez également consulter d'autres convertisseurs MD en ligne : [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) et trouver les [convertisseurs MD vers image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initier le processus de conversion
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Voir aussi

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Convertir la source MD (markdown) présentée par le chemin complet du fichier en html. Le résultat est un fichier html créé par le chemin du fichier de sortie.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier Markdown source. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Convertisseur Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Étapes de conversion

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Source de conversion. Détectez un fichier MD local existant ou créez un flux de données d'entrée comme source de conversion. Résultat de conversion. Vous pouvez obtenir directement [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou définir le chemin de fichier de sortie du résultat selon la signature de la méthode. Utilisez la méthode ConvertMarkdown() de la classe Converter pour enregistrer le MD en tant que résultat html. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre optionnel. Convertisseur MD en ligne

Vous pourriez également être intéressé par un convertisseur en ligne gratuit [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) qui convertit le MD en HTML avec une haute qualité, de façon simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes ! Vous pouvez également consulter d'autres convertisseurs MD en ligne : [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) et trouver les [convertisseurs MD vers image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/).

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
