---
title: "Converter.ConvertTemplate"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Converter. Fusionner la source du modèle présentée par HTMLDocument avec les données du modèle XML JSON. Le résultat est un fichier html créé par le chemin de fichier de sortie."
type: docs

url: /fr/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Fusionner la source du modèle présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/) avec les données du modèle (XML, JSON). Le résultat est un fichier html créé par le chemin de fichier de sortie.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| template | HTMLDocument | Fusion de la structure source présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source squelette html du formulaire
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Document HTML du formulaire comme source de conversion
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Initier le processus de conversion
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Libérer les ressources
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Fusionner la source HTML du modèle présentée par [`URL`](../../../com.aspose.html/url/) avec les données du modèle (XML, JSON). Le résultat est un fichier html créé à l'emplacement du chemin de sortie.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Fusion du squelette source HTML présenté par [`URL`](../../../com.aspose.html/url/). |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL du squelette source html du formulaire
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initier le processus de conversion
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Fusionner la source HTML du modèle présentée par [`URL`](../../../com.aspose.html/url/) avec les données du modèle (XML, JSON). Le résultat est un fichier html créé à l'emplacement du chemin de sortie.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Fusion du squelette source HTML présenté par [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL du squelette source html du formulaire
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData 
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Fusionner la source HTML du modèle présentée par le chemin complet du fichier avec les données du modèle (XML, JSON). Le résultat est un fichier html créé à partir du chemin du fichier de sortie.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Fusion du squelette source HTML présenté par le chemin complet du fichier. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source squelette html du formulaire
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initier le processus de conversion
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Fusionner la source HTML du modèle présentée par le chemin complet du fichier avec les données du modèle (XML, JSON). Le résultat est un fichier html créé à partir du chemin du fichier de sortie.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Fusion du squelette source HTML présenté par le chemin complet du fichier. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source squelette html du formulaire
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Fusionner la source HTML du modèle présentée par du contenu en ligne avec les données du modèle (XML, JSON). Le résultat est un fichier html créé à partir du chemin du fichier de sortie.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Fusion du squelette source HTML présenté par du contenu String en ligne. |
| baseUrl | String | URI de base du modèle html. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Contenu source en ligne du formulaire comme modèle
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Sortie du formulaire comme résultat de la fusion 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();
	  
      // Initier le processus de conversion
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### Voir aussi

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Fusionner la source HTML du modèle présentée par du contenu en ligne avec les données du modèle (XML, JSON). Le résultat est un fichier html créé à partir du chemin du fichier de sortie.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Fusion du squelette source HTML présenté par du contenu String en ligne. |
| baseUrl | String | URI de base du modèle html. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |
| outputPath | String | Chemin complet du fichier html en tant que résultat de conversion. |

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Contenu source en ligne du formulaire comme modèle
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // Chemin du fichier de données de modèle xml (json) du formulaire
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Définir une instance d'objet TemplateData
   var templateData = new TemplateData(templateDataPath);

   // Sortie du formulaire comme résultat de la fusion 
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Définir une instance d'objet configuration
   var configuration = new Configuration();

   // Définir l'objet TemplateLoadOptions par défaut
   var options = new TemplateLoadOptions();

   // Initier le processus de conversion avec la configuration par défaut
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Ci-dessous le fichier de données à fusionner avec la source comme modèle

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Fusionnez la source du modèle présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/) avec les données du modèle (XML, JSON). Le résultat est un nouveau HTMLDocument formé qui peut être enregistré en tant que fichier.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| template | HTMLDocument | Fusion de la structure source présentée par [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source squelette html du formulaire
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();
      
      // Document HTML du formulaire comme source de conversion
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Initier le processus de conversion
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Enregistrez le résultat avec les ressources liées
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Fusionnez la source HTML du modèle présentée par [`URL`](../../../com.aspose.html/url/) avec les données du modèle (XML, JSON). Le résultat est un nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formé qui peut être enregistré en tant que fichier.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Fusion du squelette source HTML présenté par [`URL`](../../../com.aspose.html/url/). |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formez l'URL vers le fichier source HTML squelette
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initier le processus de conversion
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Enregistrez le résultat avec les ressources liées
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Fusionnez la source HTML du modèle présentée par [`URL`](../../../com.aspose.html/url/) avec les données du modèle (XML, JSON). Le résultat est un nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formé qui peut être enregistré en tant que fichier.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Fusion du squelette source HTML présenté par [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formez l'URL vers le fichier source HTML squelette
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initier le processus de conversion avec la configuration par défaut
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Enregistrez le résultat avec les ressources liées
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

Fusionnez la source HTML du modèle présentée par le chemin complet du fichier avec les données du modèle (XML, JSON). Le résultat est un nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formé qui peut être enregistré en tant que fichier.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Fusion du squelette source HTML présenté par le chemin complet du fichier. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source squelette html du formulaire
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initier le processus de conversion
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Enregistrez le résultat avec les ressources liées
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Fusionnez la source HTML du modèle présentée par le chemin complet du fichier avec les données du modèle (XML, JSON). Le résultat est un nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formé qui peut être enregistré en tant que fichier.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Fusion du squelette source HTML présenté par le chemin complet du fichier. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source squelette html du formulaire
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initier le processus de conversion avec la configuration par défaut
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Enregistrez le résultat avec les ressources liées
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Fusionnez la source HTML du modèle présentée par le contenu en ligne avec les données du modèle (XML, JSON). Le résultat est un nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formé qui peut être enregistré en tant que fichier.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Fusion du squelette source HTML présenté par du contenu String en ligne. |
| baseUrl | String | URI de base du modèle html. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Contenu source en ligne du formulaire comme modèle
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Sortie du formulaire comme résultat de la fusion 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initiez le processus de conversion et enregistrez le résultat
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Fusionnez la source HTML du modèle présentée par le contenu en ligne avec les données du modèle (XML, JSON). Le résultat est un nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) formé qui peut être enregistré en tant que fichier.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Fusion du squelette source HTML présenté par du contenu String en ligne. |
| baseUrl | String | URI de base du modèle html. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| données | TemplateData | Données de modèle pour la fusion - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) instance d'objet. Il est utilisé pour déterminer si les noms du modèle et des éléments de données correspondent, quelle que soit la casse (options). |

### Valeur de retour

Nouveau [`HTMLDocument`](../../../com.aspose.html/htmldocument/) créé comme résultat de conversion qui peut être enregistré via le chemin de fichier de sortie.

## Remarques

Fusionneur de modèle

L'idée de la fusion de modèle est de créer un document HTML basé sur un modèle HTML et de le remplir à partir d'une source de données. Aspose.HTML fournit la syntaxe des expressions en ligne pour travailler avec les modèles et divers types de sources de données, tels que XML et JSON. Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) où vous pouvez trouver plus d'informations sur la fusion de modèle et l'utilisation de la méthode ConvertTemplate().

Étapes de conversion (fusion)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Source du modèle. Définissez la source du modèle HTML par fichier, [`URL`](../../../com.aspose.html/url/), instance d'objet [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ou même par contenu en ligne. Résultat de la conversion. Vous pouvez obtenir directement le HTMLDocument résultant ou définir le chemin du fichier de sortie selon la signature de la méthode. Créez une instance de [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Utilisez la méthode ConvertTemplate() de la classe Converter pour fusionner le modèle avec les données. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Contenu source en ligne du formulaire comme modèle
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Chemin du fichier de données de modèle xml (json) du formulaire
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Définir une instance d'objet TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Sortie du formulaire comme résultat de la fusion 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Définir une instance d'objet configuration
      var configuration = new Configuration();

      // Définir l'objet TemplateLoadOptions par défaut
      var options = new TemplateLoadOptions();

      // Initiez le processus de conversion et enregistrez le résultat
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Voir aussi

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
