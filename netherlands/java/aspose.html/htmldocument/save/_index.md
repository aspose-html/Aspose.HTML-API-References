---
title: "HTMLDocument.Save"
second_title: "Aspose.HTML voor Java API-referentie"
description: "HTMLDocument-methode. Slaat het document op in een lokaal bestand gespecificeerd door url. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map waarvan de naam wordt samengesteld als output_file_name _files."
type: docs

url: /nl/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Slaat het document op in een lokaal bestand opgegeven door url. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als output_file_name + "_files".

```java
public void Save(Url url)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokale [`URL`](../../url/) naar uitvoerbestand. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als de opgegeven `url` geen geldige lokale bestands-URL is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(Url)-methode

Het is noodzakelijk een volledig Url‑pad op te geven – 'outputFilePath' voor het opslaan van een HTML‑document. De Url(url)-constructor maakt een instantie van de [`Url`](../../url/)‑klasse met de opgegeven url. Vervolgens moet u die instantie doorgeven aan de Save(Url)-methode. Het document wordt opgeslagen in het lokale bestand gespecificeerd door url. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als output_file_name + \"_files\".

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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

### Zie ook

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Slaat de documentinhoud en bronnen op met behulp van de [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resource-handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Zie ook

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Slaat het document op in een lokaal bestand opgegeven door pad. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt opgebouwd als: output_file_name + "_files".

```java
public void Save(String path)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | String | Lokaal bestandssysteempad naar uitvoerbestand. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als het opgegeven `path` geen geldig lokaal bestandspad is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(String)-methode neemt als parameter een lokaal bestandssysteempad naar een uitvoerbestand en slaat een HTML‑document op in het lokale bestand gespecificeerd door pad. Alle bronnen die in het document worden gebruikt, worden opgeslagen in een aangrenzende map.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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

### Zie ook

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Slaat het document op in een lokaal bestand opgegeven door pad. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als output_file_name + "_files".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | String | Lokaal bestandspad naar uitvoerbestand. |
| saveFormat | HTMLSaveFormat | Formaat waarin het document wordt opgeslagen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als het opgegeven `path` geen geldig lokaal bestandspad is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(String, HTMLSaveFormat) Methode

Save(String, HTMLSaveFormat) methode neemt als parameters een lokaal bestandssysteempad naar het uitvoerbestand en saveFormat. De [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) enumeratie geeft het formaat aan waarin het document wordt opgeslagen; het kan HTML-, MHTML- en MD-formaten zijn. De methode slaat het HTML-document op in het opgegeven formaat naar het lokale bestand dat door het pad wordt gespecificeerd. Alle bronnen die in het document worden gebruikt, worden opgeslagen in een aangrenzende map.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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

&lt;title&gt;Titel&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;Container met ID - identifier&lt;/div&gt;

&lt;div class="custom-class"&gt;Aangepast door css-klasse container&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;Eerste gestileerd door pStyle-klasse alinea&lt;/p&gt;

&lt;p class="pStyle"&gt;Tweede gestileerd door pStyle-klasse alinea&lt;/p&gt;

&lt;p class="pStyle"&gt;Derde gestileerd door pStyle-klasse alinea&lt;/p&gt;

&lt;span class="pStyle"&gt;Span gestileerd door pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id="p1" class="ddd kkk"&gt;Paragraaf gestyled met klassenaam =ddd kkk=&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;Paragraaf gestyled met klassenaam =ddd fff=&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;Paragraaf gestyled met klassenaam =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Hallo van DIV-element&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Content-Type: text/css;

Content-Location: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### Zie ook

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Slaat het document op in een lokaal bestand opgegeven door url. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokale URL naar uitvoerbestand. |
| saveFormat | HTMLSaveFormat | Formaat waarin het document wordt opgeslagen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als de opgegeven `url` geen geldige lokale bestands-URL is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(Url, HTMLSaveFormat) Methode

Het is noodzakelijk om een volledig Url-pad op te geven - 'outputFilePath' voor het opslaan van een HTML-document. De Url(url)-constructor maakt een instantie van de [`Url`](../../url/) klasse met de opgegeven url. De [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) enumeratie geeft het formaat aan waarin het document wordt opgeslagen; dit kan HTML, MHTML en MD-formaten zijn. Vervolgens moet u de parameters doorgeven aan de Save(url, saveFormat) methode. Het document wordt opgeslagen in het opgegeven formaat naar het lokale bestand dat door url is opgegeven.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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

### Zie ook

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Slaat de documentinhoud en bronnen op met behulp van de [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resource-handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Formaat waarin het document wordt opgeslagen. |

### Zie ook

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Slaat het document op in een lokaal bestand opgegeven door pad. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt opgebouwd als: output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | String | Lokaal pad naar uitvoerbestand. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) object is voor het beheer van het resource handling proces. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als het opgegeven `path` geen geldig lokaal bestandspad is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(String, HTMLSaveOptions) Methode

Save(String, HTMLSaveOptions) methode neemt als parameters een pad in het lokale bestandssysteem naar het uitvoerbestand, een instantie van de [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) klasse en slaat een HTML-document met resources op naar het lokale bestand dat door het pad is opgegeven. De HTMLSaveOptions() constructor maakt een instantie van opslaanopties die [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) eigenschappen bevat die worden gebruikt voor de configuratie van resource handling. Alle resources die in het document worden gebruikt, worden opgeslagen in een aangrenzende map.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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
	// Definieer opties klasse instantie
	var options = new HTMLSaveOptions();
	// Beperking van pagina-afhandeling
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Zie ook

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Slaat het document op in een lokaal bestand opgegeven door url. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokale [`URL`](../../url/) naar uitvoerbestand. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) object is voor het beheer van het resource handling proces. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als de opgegeven `url` geen geldige lokale bestands-URL is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(Url, HTMLSaveOptions) Methode

Het is noodzakelijk om een volledig Url-pad op te geven voor het opslaan van een HTML-document. De Url(url)-constructor maakt een instantie van de [`Url`](../../url/) klasse met de opgegeven url. De HTMLSaveOptions() constructor maakt een instantie van de [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) klasse die ResourceHandlingOptions-eigenschappen bevat die worden gebruikt voor de configuratie van resource handling. De Save(url, saveOptions) methode neemt parameters en slaat het HTML-document met resources op naar het lokale bestand dat door url is opgegeven.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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
	// Definieer opties klasse instantie
	var options = new HTMLSaveOptions();
	// Beperking van pagina-afhandeling
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Zie ook

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Slaat de documentinhoud en bronnen op met behulp van de [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resource-handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | HTML opslaan opties. |

### Zie ook

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Slaat het document op in een lokaal bestand opgegeven door pad. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt opgebouwd als: output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | String | Lokaal pad naar uitvoerbestand. |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie de [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als het opgegeven `path` geen geldig lokaal bestandspad is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(String, MarkdownSaveOptions) Methode

Het is noodzakelijk om een pad in het lokale bestandssysteem naar het uitvoerbestand op te geven voor het opslaan van het document. De MarkdownSaveOptions() constructor maakt een instantie van de [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) klasse die een reeks eigenschappen heeft. Bijvoorbeeld, u kunt de markdown-opmaakstijl instellen, vooraf gedefinieerde GitLab Flavored Markdown-compatibele opties gebruiken en resource handling configureren. De Save(path, saveOptions) methode neemt het lokale bestandssysteempad naar het uitvoerbestand en de opties‑instantie als parameters en slaat HTML op als een Markdown-document met resources naar het lokale bestand dat door het pad is opgegeven.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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
	// Definieer opties klasse instantie
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Zie ook

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Slaat het document op in een lokaal bestand opgegeven door url. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokale [`URL`](../../url/) naar uitvoerbestand. |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie de [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als de opgegeven `url` geen geldige lokale bestands-URL is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(Url, MarkdownSaveOptions) Methode

Het is noodzakelijk om een volledig Url-pad op te geven voor het opslaan van het document. De Url(url)-constructor maakt een instantie van de [`Url`](../../url/) klasse met de opgegeven url. De MarkdownSaveOptions() constructor maakt een instantie van de [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) klasse die een reeks eigenschappen heeft. Bijvoorbeeld, u kunt de Markdown-opmaakstijl instellen, vooraf gedefinieerde GitLab Flavored Markdown-compatibele opties gebruiken en resource handling configureren. De Save(url, saveOptions) methode neemt url en save‑options‑instanties als parameters en slaat het document met resources op naar het lokale bestand dat door url is opgegeven.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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
	// Definieer opties klasse instantie
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Zie ook

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Slaat de documentinhoud en bronnen op met behulp van de [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resource-handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Markdown opslaan opties. |

### Zie ook

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Slaat het document op in een lokaal bestand opgegeven door pad. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt opgebouwd als: output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | String | Lokaal pad naar uitvoerbestand. |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie de [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als het opgegeven `path` geen geldig lokaal bestandspad is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(String, MHTMLSaveOptions) Methode

Het is noodzakelijk om een lokaal bestandssysteempad naar het uitvoerbestand op te geven voor het opslaan van het document. De MHTMLSaveOptions() constructor initialiseert een instantie van [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) klasse die de eigenschap ResourceHandlingOptions bevat, die wordt gebruikt voor de configuratie van resource‑afhandeling. De Save(path, saveOptions) methode neemt een lokaal bestandssysteempad naar het uitvoerbestand en een instantie van save‑options als parameters en slaat HTML op als een MHTML‑document naar het lokale bestand dat door pad wordt opgegeven.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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
	// Definieer opties klasse instantie
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Zie ook

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Slaat het document op in een lokaal bestand opgegeven door url. Alle bronnen die in dit document worden gebruikt, worden opgeslagen in een aangrenzende map, waarvan de naam wordt samengesteld als: output_file_name + "_files".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Lokale URL naar uitvoerbestand. |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie de [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt opgegooid als de opgegeven `url` geen geldige lokale bestands-URL is. |

## Opmerkingen

HTML opslaan

De meeste taken die u moet uitvoeren, vereisen het opslaan van een document. Zodra u het bestaande bestand laadt of een HTML‑document vanaf nul maakt, kunt u uw wijzigingen opslaan met een van de HTMLDocument.Save()-methoden. De methoden maken het mogelijk HTML op te slaan in een lokaal bestand gespecificeerd door pad, URL of opslaglocatie. Raadpleeg de [documentatie](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) voor meer informatie over opslaan.

Save(Url, MHTMLSaveOptions) Methode

Het is noodzakelijk om een volledige Url‑pad op te geven voor het opslaan van het document. De Url(url) constructor maakt een instantie van de [`Url`](../../url/) klasse met de opgegeven url. De MHTMLSaveOptions() constructor initialiseert een instantie van [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) klasse die de eigenschap ResourceHandlingOptions bevat, die wordt gebruikt voor de configuratie van resource‑afhandeling. De Save(url, saveOptions) methode neemt url en opties als parameters en slaat HTML op als een MHTML‑document naar het lokale bestand dat door url wordt opgegeven.

Broncode

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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
	// Definieer opties klasse instantie
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### Zie ook

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Slaat de documentinhoud en bronnen op met behulp van de [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resourceHandler | ResourceHandler | De resource-handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | MHTML‑opslaanopties. |

### Zie ook

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
