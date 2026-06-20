---
title: "HTMLDocument.Save"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode HTMLDocument. Enregistre le document dans un fichier local spécifié par l’url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent dont le nom sera construit comme output_file_name_files."
type: docs

url: /fr/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme output_file_name + "_files".

```java
public void Save(Url url)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL locale [`URL`](../../url/) vers le fichier de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `url` spécifié n'est pas une URL de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Méthode Save(Url)

Il est nécessaire de spécifier un chemin Url complet – 'outputFilePath' pour l’enregistrement du document HTML. Le constructeur Url(url) crée une instance de la classe [`Url`](../../url/) avec l’url spécifiée. Vous devez ensuite passer l’instance à la méthode Save(Url). Le document sera enregistré dans le fichier local spécifié par l’url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme output_file_name + \"_files\".

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Voir aussi

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Le gestionnaire de ressources [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Voir aussi

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit ainsi : output_file_name + "_files".

```java
public void Save(String path)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | String | Chemin du système de fichiers local vers le fichier de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `path` spécifié n'est pas un chemin de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

La méthode Save(String) prend en paramètre un chemin du système de fichiers local vers un fichier de sortie et enregistre un document HTML dans le fichier local spécifié par le chemin. Toutes les ressources utilisées dans le document seront enregistrées dans un dossier adjacent.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Voir aussi

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme output_file_name + "_files".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | String | Chemin du fichier local vers le fichier de sortie. |
| saveFormat | HTMLSaveFormat | Format dans lequel le document est enregistré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `path` spécifié n'est pas un chemin de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Save(String, HTMLSaveFormat) Méthode

Save(String, HTMLSaveFormat) méthode prend comme paramètres un chemin du système de fichiers local vers le fichier de sortie et saveFormat. L'énumération [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) spécifie le format dans lequel le document est enregistré, il peut être aux formats HTML, MHTML et MD. La méthode enregistre le document HTML dans le format spécifié dans le fichier local indiqué par le chemin. Toutes les ressources utilisées dans le document seront enregistrées dans un dossier adjacent.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="en" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;Titre&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;Conteneur avec ID - identifiant&lt;/div&gt;

&lt;div class="custom-class"&gt;Personnalisé par la classe css du conteneur&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;Premier paragraphe stylisé par la classe pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Deuxième paragraphe stylisé par la classe pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Troisième paragraphe stylisé par la classe pStyle&lt;/p&gt;

&lt;span class="pStyle"&gt;Span stylisé par pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id="p1" class="ddd kkk"&gt;Paragraphe stylisé par le nom de classe =ddd kkk=&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;Paragraphe stylisé par le nom de classe =ddd fff=&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;Paragraphe stylisé par le nom de classe =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Bonjour depuis l'élément DIV&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Type de contenu : text/css;

Emplacement du contenu : main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### Voir aussi

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |
| saveFormat | HTMLSaveFormat | Format dans lequel le document est enregistré. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `url` spécifié n'est pas une URL de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Save(Url, HTMLSaveFormat) Méthode

Il est nécessaire de spécifier un chemin Url complet - 'outputFilePath' pour l'enregistrement du document HTML. Le constructeur Url(url) crée une instance de la classe [`Url`](../../url/) avec l'url spécifiée. L'énumération [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) spécifie le format dans lequel le document est enregistré, il peut être HTML, MHTML et MD. Ensuite, vous devez transmettre les paramètres à la méthode Save(url, saveFormat). Le document sera enregistré dans le format spécifié dans le fichier local indiqué par l'url.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Voir aussi

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Le gestionnaire de ressources [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Format dans lequel le document est enregistré. |

### Voir aussi

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit ainsi : output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | String | Chemin local vers le fichier de sortie. |
| saveOptions | HTMLSaveOptions | L'objet [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) sert à la gestion du processus de traitement des ressources. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `path` spécifié n'est pas un chemin de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Save(String, HTMLSaveOptions) Méthode

La méthode Save(String, HTMLSaveOptions) prend en paramètres un chemin du système de fichiers local vers le fichier de sortie, une instance de la classe [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) et enregistre un document HTML avec ses ressources dans le fichier local indiqué par le chemin. Le constructeur HTMLSaveOptions() crée une instance d'options d'enregistrement qui possède des propriétés [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) utilisées pour la configuration de la gestion des ressources. Toutes les ressources utilisées dans le document seront enregistrées dans un dossier adjacent.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Définir une instance de classe d'options
	var options = new HTMLSaveOptions();
	// Restriction de la gestion des pages
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Voir aussi

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL locale [`URL`](../../url/) vers le fichier de sortie. |
| saveOptions | HTMLSaveOptions | L'objet [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) sert à la gestion du processus de traitement des ressources. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `url` spécifié n'est pas une URL de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Save(Url, HTMLSaveOptions) Méthode

Il est nécessaire de spécifier un chemin Url complet pour l'enregistrement du document HTML. Le constructeur Url(url) crée une instance de la classe [`Url`](../../url/) avec l'url spécifiée. Le constructeur HTMLSaveOptions() crée une instance de la classe [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) qui possède des propriétés ResourceHandlingOptions utilisées pour la configuration de la gestion des ressources. La méthode Save(url, saveOptions) prend des paramètres et enregistre le document HTML avec ses ressources dans le fichier local indiqué par l'url.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Définir une instance de classe d'options
	var options = new HTMLSaveOptions();
	// Restriction de la gestion des pages
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Voir aussi

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Le gestionnaire de ressources [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | Options d'enregistrement HTML. |

### Voir aussi

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit ainsi : output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | String | Chemin local vers le fichier de sortie. |
| saveOptions | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `path` spécifié n'est pas un chemin de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Save(String, MarkdownSaveOptions) Méthode

Il est nécessaire de spécifier un chemin du système de fichiers local vers le fichier de sortie pour l'enregistrement du document. Le constructeur MarkdownSaveOptions() crée une instance de la classe [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) qui possède un ensemble de propriétés. Par exemple, vous pouvez définir le style de formatage markdown, utiliser des options compatibles avec GitLab Flavored Markdown prédéfinies et configurer la gestion des ressources. La méthode Save(path, saveOptions) prend en paramètres le chemin du système de fichiers local vers le fichier de sortie et l'instance d'options, et enregistre le HTML sous forme de document Markdown avec ses ressources dans le fichier local indiqué par le chemin.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Définir une instance de classe d'options
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Voir aussi

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL locale [`URL`](../../url/) vers le fichier de sortie. |
| saveOptions | MarkdownSaveOptions | L'utilisation de l'objet [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `url` spécifié n'est pas une URL de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Save(Url, MarkdownSaveOptions) Méthode

Il est nécessaire de spécifier un chemin Url complet pour l'enregistrement du document. Le constructeur Url(url) crée une instance de la classe [`Url`](../../url/) avec l'url spécifiée. Le constructeur MarkdownSaveOptions() crée une instance de la classe [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) qui possède un ensemble de propriétés. Par exemple, vous pouvez définir le style de formatage Markdown, utiliser des options compatibles avec GitLab Flavored Markdown prédéfinies et configurer la gestion des ressources. La méthode Save(url, saveOptions) prend en paramètres l'url et les instances d'options d'enregistrement et enregistre le document avec ses ressources dans le fichier local indiqué par l'url.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Définir une instance de classe d'options
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Voir aussi

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Le gestionnaire de ressources [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Options d'enregistrement Markdown. |

### Voir aussi

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Enregistre le document dans un fichier local spécifié par le chemin. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit ainsi : output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | String | Chemin local vers le fichier de sortie. |
| saveOptions | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `path` spécifié n'est pas un chemin de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Méthode Save(String, MHTMLSaveOptions)

Il est nécessaire de spécifier un chemin du système de fichiers local vers le fichier de sortie pour l’enregistrement du document. Le constructeur MHTMLSaveOptions() initialise une instance de la classe [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) qui possède la propriété ResourceHandlingOptions utilisée pour la configuration de la gestion des ressources. La méthode Save(path, saveOptions) prend en paramètres un chemin du système de fichiers local vers le fichier de sortie et une instance d’options d’enregistrement, et enregistre le HTML en tant que document MHTML dans le fichier local spécifié par le chemin.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Définir une instance de classe d'options
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Voir aussi

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Enregistre le document dans un fichier local spécifié par l'url. Toutes les ressources utilisées dans ce document seront enregistrées dans un dossier adjacent, dont le nom sera construit comme : output_file_name + "_files".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | URL locale vers le fichier de sortie. |
| saveOptions | MHTMLSaveOptions | L'utilisation de l'objet [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Levée si le `url` spécifié n'est pas une URL de fichier local valide. |

## Remarques

Enregistrer HTML

La plupart des tâches que vous devez effectuer nécessitent d’enregistrer un document. Une fois que vous avez chargé le fichier existant ou créé un document HTML à partir de zéro, vous pouvez enregistrer vos modifications en utilisant l’une des méthodes HTMLDocument.Save(). Les méthodes permettent d’enregistrer du HTML dans un fichier local spécifié par le chemin, l’URL ou le stockage de sortie. Consultez la [documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) pour en savoir plus sur l’enregistrement.

Méthode Save(Url, MHTMLSaveOptions)

Il est nécessaire de spécifier un chemin Url complet pour l’enregistrement du document. Le constructeur Url(url) crée une instance de la classe [`Url`](../../url/) avec l’url spécifiée. Le constructeur MHTMLSaveOptions() initialise une instance de la classe [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) qui possède la propriété ResourceHandlingOptions utilisée pour la configuration de la gestion des ressources. La méthode Save(url, saveOptions) prend l’url et les options en paramètres et enregistre le HTML en tant que document MHTML dans le fichier local spécifié par l’url.

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Définir une instance de classe d'options
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### Voir aussi

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Enregistre le contenu du document et les ressources en utilisant le [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Le gestionnaire de ressources [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | Options d’enregistrement MHTML. |

### Voir aussi

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
