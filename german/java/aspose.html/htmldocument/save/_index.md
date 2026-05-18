---
title: "HTMLDocument.Save"
second_title: "Aspose.HTML für Java API-Referenz"
description: "HTMLDocument-Methode. Speichert das Dokument in einer lokalen Datei, die durch die URL angegeben ist. Alle im Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert, dessen Name aus output_file_name _files zusammengesetzt wird."
type: docs

url: /de/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Speichert das Dokument in einer lokalen Datei, die durch die URL angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einem angrenzenden Ordner gespeichert, dessen Name als output_file_name + "_files" konstruiert wird.

```java
public void Save(Url url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale [`URL`](../../url/) zur Ausgabedatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei-URL ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Save(Url)-Methode

Es ist erforderlich, einen vollständigen Url-Pfad – 'outputFilePath' – für das Speichern eines HTML‑Dokuments anzugeben. Der Url(url)-Konstruktor erstellt eine Instanz der [`Url`](../../url/)‑Klasse mit der angegebenen URL. Anschließend sollten Sie die Instanz an die Save(Url)-Methode übergeben. Das Dokument wird in der durch die URL angegebenen lokalen Datei gespeichert. Alle im Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert, dessen Name aus output_file_name + "_files" zusammengesetzt wird.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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

### Siehe auch

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Siehe auch

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Speichert das Dokument in einer lokalen Datei, die durch den Pfad angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(String path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Lokaler Dateisystempfad zur Ausgabedatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Die Save(String)-Methode nimmt als Parameter einen lokalen Dateisystempfad zu einer Ausgabedatei und speichert ein HTML‑Dokument in der durch den Pfad angegebenen lokalen Datei. Alle im Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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

### Siehe auch

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Speichert das Dokument in einer lokalen Datei, die durch den Pfad angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einem angrenzenden Ordner gespeichert, dessen Name als output_file_name + "_files" konstruiert wird.

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Lokaler Dateipfad zur Ausgabedatei. |
| saveFormat | HTMLSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Save(String, HTMLSaveFormat) Methode

Save(String, HTMLSaveFormat) Methode nimmt als Parameter einen Pfad im lokalen Dateisystem zur Ausgabedatei und das saveFormat. Die [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) Aufzählung gibt das Format an, in dem das Dokument gespeichert wird; es kann HTML-, MHTML- und MD-Formate sein. Die Methode speichert das HTML-Dokument im angegebenen Format in der durch den Pfad spezifizierten lokalen Datei. Alle im Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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

Content-Type: Multipart/related; boundary=\"boundary\";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang=\"en\" xmlns:xml=\"http://www.w3.org/XML/1998/package\"&gt;&lt;head&gt;

&lt;meta charset=\"UTF-8\"&gt;

&lt;link rel=\"stylesheet\" href=\"main.css\"&gt;

&lt;title&gt;Titel&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id=\"uniqueIdentifier\"&gt;Container mit ID - Bezeichner&lt;/div&gt;

&lt;div class=\"custom-class\"&gt;Durch CSS‑Klassen‑Container angepasst&lt;/div&gt;

&lt;div&gt;

&lt;p class=\"pStyle\"&gt;Erster durch die pStyle-Klasse formatierter Absatz&lt;/p&gt;

&lt;p class=\"pStyle\"&gt;Zweiter durch die pStyle-Klasse formatierter Absatz&lt;/p&gt;

&lt;p class=\"pStyle\"&gt;Dritter durch die pStyle-Klasse formatierter Absatz&lt;/p&gt;

&lt;span class=\"pStyle\"&gt;Span durch pStyle formatiert&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns=\"http://www.w3.org/1998/Math/MathML\"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id=\"smart class\"&gt;

&lt;p id="p1" class="ddd kkk"&gt;Absatz formatiert mit Klassenname =ddd kkk=&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;Absatz formatiert mit Klassenname =ddd fff=&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;Absatz formatiert mit Klassenname =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Hallo vom DIV-Element&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Content-Type: text/css;

Content-Location: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### Siehe auch

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Speichert das Dokument in einer lokalen Datei, die durch die URL angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einem angrenzenden Ordner gespeichert, dessen Name als output_file_name + "_files" konstruiert wird.

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveFormat | HTMLSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei-URL ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Save(Url, HTMLSaveFormat) Methode

Es ist erforderlich, einen vollständigen Url-Pfad – 'outputFilePath' – für das Speichern des HTML-Dokuments anzugeben. Der Url(url)-Konstruktor erstellt eine Instanz der [`Url`](../../url/) Klasse mit der angegebenen Url. Die [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) Aufzählung gibt das Format an, in dem das Dokument gespeichert wird; es kann HTML-, MHTML- oder MD-Formate sein. Anschließend sollten Sie die Parameter an die Save(url, saveFormat)-Methode übergeben. Das Dokument wird im angegebenen Format in die lokale Datei gespeichert, die durch die Url angegeben ist.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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

### Siehe auch

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Siehe auch

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Speichert das Dokument in einer lokalen Datei, die durch den Pfad angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Lokaler Pfad zur Ausgabedatei. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) Objekt dient der Verwaltung des Ressourcenhandhabungsprozesses. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Save(String, HTMLSaveOptions) Methode

Save(String, HTMLSaveOptions) Methode nimmt als Parameter einen Pfad im lokalen Dateisystem zur Ausgabedatei, eine Instanz der [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) Klasse und speichert ein HTML-Dokument mit Ressourcen in die durch den Pfad angegebene lokale Datei. Der HTMLSaveOptions()-Konstruktor erstellt eine Instanz von Speicheroptionen, die [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) Eigenschaften enthält, die zur Konfiguration der Ressourcenverwaltung verwendet werden. Alle im Dokument verwendeten Ressourcen werden in einen benachbarten Ordner gespeichert.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
	// Optionen-Klasseninstanz definieren
	var options = new HTMLSaveOptions();
	// Beschränkung der Seitenverarbeitung
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Siehe auch

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Speichert das Dokument in einer lokalen Datei, die durch die URL angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einem angrenzenden Ordner gespeichert, dessen Name wie folgt konstruiert wird: output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale [`URL`](../../url/) zur Ausgabedatei. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) Objekt dient der Verwaltung des Ressourcenhandhabungsprozesses. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei-URL ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Save(Url, HTMLSaveOptions) Methode

Es ist erforderlich, einen vollständigen Url-Pfad für das Speichern des HTML-Dokuments anzugeben. Der Url(url)-Konstruktor erstellt eine Instanz der [`Url`](../../url/) Klasse mit der angegebenen Url. Der HTMLSaveOptions()-Konstruktor erstellt eine Instanz der [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) Klasse, die ResourceHandlingOptions‑Eigenschaften enthält, die zur Konfiguration der Ressourcenverwaltung verwendet werden. Die Save(url, saveOptions)-Methode nimmt Parameter entgegen und speichert das HTML-Dokument mit Ressourcen in die durch die Url angegebene lokale Datei.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
	// Optionen-Klasseninstanz definieren
	var options = new HTMLSaveOptions();
	// Beschränkung der Seitenverarbeitung
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Siehe auch

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | HTML-Speicheroptionen. |

### Siehe auch

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Speichert das Dokument in einer lokalen Datei, die durch den Pfad angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Lokaler Pfad zur Ausgabedatei. |
| saveOptions | MarkdownSaveOptions | Die Verwendung des [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Save(String, MarkdownSaveOptions) Methode

Es ist erforderlich, einen Pfad im lokalen Dateisystem zur Ausgabedatei für das Speichern des Dokuments anzugeben. Der MarkdownSaveOptions()-Konstruktor erstellt eine Instanz der [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Klasse, die eine Reihe von Eigenschaften besitzt. Beispielsweise können Sie den Markdown-Formatierungsstil festlegen, vordefinierte, mit GitLab Flavored Markdown kompatible Optionen verwenden und die Ressourcenverwaltung konfigurieren. Die Save(path, saveOptions)-Methode nimmt den Pfad im lokalen Dateisystem zur Ausgabedatei und die Optionsinstanz als Parameter und speichert HTML als Markdown-Dokument mit Ressourcen in die durch den Pfad angegebene lokale Datei.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
	// Optionen-Klasseninstanz definieren
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Siehe auch

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Speichert das Dokument in einer lokalen Datei, die durch die URL angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einem angrenzenden Ordner gespeichert, dessen Name wie folgt konstruiert wird: output_file_name + "_files".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale [`URL`](../../url/) zur Ausgabedatei. |
| saveOptions | MarkdownSaveOptions | Die Verwendung des [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei-URL ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Save(Url, MarkdownSaveOptions) Methode

Es ist erforderlich, einen vollständigen Url-Pfad für das Speichern des Dokuments anzugeben. Der Url(url)-Konstruktor erstellt eine Instanz der [`Url`](../../url/) Klasse mit der angegebenen Url. Der MarkdownSaveOptions()-Konstruktor erstellt eine Instanz der [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Klasse, die eine Reihe von Eigenschaften besitzt. Beispielsweise können Sie den Markdown-Formatierungsstil festlegen, vordefinierte, mit GitLab Flavored Markdown kompatible Optionen verwenden und die Ressourcenverwaltung konfigurieren. Die Save(url, saveOptions)-Methode nimmt Url- und SaveOptions‑Instanzen als Parameter und speichert das Dokument mit Ressourcen in die durch die Url angegebene lokale Datei.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
	// Optionen-Klasseninstanz definieren
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Siehe auch

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Markdown-Speicheroptionen. |

### Siehe auch

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Speichert das Dokument in einer lokalen Datei, die durch den Pfad angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einen angrenzenden Ordner gespeichert, dessen Name wie folgt gebildet wird: output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | String | Lokaler Pfad zur Ausgabedatei. |
| saveOptions | MHTMLSaveOptions | Die Verwendung des [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der angegebene `path` kein gültiger lokaler Dateipfad ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Methode Save(String, MHTMLSaveOptions)

Es ist erforderlich, einen lokalen Dateisystempfad für die Ausgabedatei beim Speichern des Dokuments anzugeben. Der Konstruktor MHTMLSaveOptions() initialisiert eine Instanz der [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Klasse, die die Property ResourceHandlingOptions enthält, die zur Konfiguration der Ressourcenverwaltung verwendet wird. Die Methode Save(path, saveOptions) nimmt einen lokalen Dateisystempfad zur Ausgabedatei und eine Instanz von Speicheroptionen als Parameter und speichert HTML als MHTML-Dokument in der durch path angegebenen lokalen Datei.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
	// Optionen-Klasseninstanz definieren
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Siehe auch

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Speichert das Dokument in einer lokalen Datei, die durch die URL angegeben ist. Alle in diesem Dokument verwendeten Ressourcen werden in einem angrenzenden Ordner gespeichert, dessen Name wie folgt konstruiert wird: output_file_name + "_files".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveOptions | MHTMLSaveOptions | Die Verwendung des [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die angegebene `url` keine gültige lokale Datei-URL ist. |

## Hinweise

HTML speichern

Die meisten Aufgaben, die Sie ausführen müssen, erfordern das Speichern eines Dokuments. Sobald Sie die vorhandene Datei geladen oder ein HTML‑Dokument von Grund auf neu erstellt haben, können Sie Ihre Änderungen mit einer der HTMLDocument.Save()-Methoden speichern. Die Methoden ermöglichen das Speichern von HTML in einer lokalen Datei, die durch Pfad, URL oder Ausgabespeicher angegeben ist. Weitere Informationen zum Speichern finden Sie in der [Dokumentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

Methode Save(Url, MHTMLSaveOptions)

Es ist erforderlich, einen vollständigen Url-Pfad für das Speichern des Dokuments anzugeben. Der Konstruktor Url(url) erstellt eine Instanz der [`Url`](../../url/) Klasse mit der angegebenen URL. Der Konstruktor MHTMLSaveOptions() initialisiert eine Instanz der [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Klasse, die die Property ResourceHandlingOptions enthält, die zur Konfiguration der Ressourcenverwaltung verwendet wird. Die Methode Save(url, saveOptions) nimmt URL und Optionen als Parameter und speichert HTML als MHTML-Dokument in der durch url angegebenen lokalen Datei.

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
	// Optionen-Klasseninstanz definieren
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### Siehe auch

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Speichert den Dokumentinhalt und die Ressourcen mithilfe des [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Der Ressourcen-Handler [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | MHTML-Speicheroptionen. |

### Siehe auch

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
