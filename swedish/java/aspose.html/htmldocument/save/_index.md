---
title: "HTMLDocument.Save"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLDocument method. Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som output_file_name _files."
type: docs

url: /sv/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som output_file_name + "_files".

```java
public void Save(Url url)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Lokal [`URL`](../../url/) till utdatafil. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `url` inte är en giltig lokal fil-URL. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(Url)-metod

Det är nödvändigt att ange en full Url-sökväg – 'outputFilePath' för sparning av HTML-dokument. Url(url)-konstruktorn skapar en instans av klassen [`Url`](../../url/) med den angivna url:en. Därefter ska du skicka instansen till Save(Url)-metoden. Dokumentet kommer att sparas till den lokala fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som output_file_name + "_files".

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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

### Se även

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Se även

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Sparar dokumentet till en lokal fil som anges av sökvägen. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som: output_file_name + "_files".

```java
public void Save(String path)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | String | Lokal filsökväg till utdatafil. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `path` inte är en giltig lokal filsökväg. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(String)-metoden tar som parameter en lokal filsökväg till en utdatafil och sparar ett HTML-dokument till den lokala fil som anges av sökvägen. Alla resurser som används i dokumentet kommer att sparas i en intilliggande mapp.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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

### Se även

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Sparar dokumentet till en lokal fil som anges av sökväg. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som output_file_name + "_files".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | String | Lokal filsökväg till utdatafil. |
| saveFormat | HTMLSaveFormat | Format som dokumentet sparas i. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `path` inte är en giltig lokal filsökväg. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(String, HTMLSaveFormat) Metod

Save(String, HTMLSaveFormat) metod tar som parametrar en lokal filsökväg till utdatafilen och saveFormat. Den [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/)‑enumerationen specificerar det format i vilket dokumentet sparas, det kan vara HTML-, MHTML- och MD-format. Metoden sparar HTML‑dokumentet i det angivna formatet till den lokala fil som anges av sökvägen. Alla resurser som används i dokumentet kommer att sparas i en intilliggande mapp.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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

&lt;!DOCTYPE html&gt;&lt;html lang=\"en\" xmlns:xml=\"http://www.w3.org/XML/1998/package\"&gt;&lt;head&gt;

&lt;meta charset=\"UTF-8\"&gt;

&lt;link rel=\"stylesheet\" href=\"main.css\"&gt;

&lt;title&gt;Titel&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id=\"uniqueIdentifier\"&gt;Behållare med ID - identifierare&lt;/div&gt;

&lt;div class=\"custom-class\"&gt;Anpassad av CSS-klassbehållare&lt;/div&gt;

&lt;div&gt;

&lt;p class=\"pStyle\"&gt;Första stylade av pStyle-klass paragraf&lt;/p&gt;

&lt;p class=\"pStyle\"&gt;Andra stylade av pStyle-klass paragraf&lt;/p&gt;

&lt;p class=\"pStyle\"&gt;Tredje stylade av pStyle-klass paragraf&lt;/p&gt;

&lt;span class=\"pStyle\"&gt;Span stylad av pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns=\"http://www.w3.org/1998/Math/MathML\"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id=\"smart class\"&gt;

&lt;p id="p1" class="ddd kkk"&gt;Stycke stylat med klassnamn =ddd kkk=&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;Stycke stylat med klassnamn =ddd fff=&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;Stycke stylat med klassnamn =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Hej från DIV-element&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Innehållstyp: text/css;

Innehållsplats: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### Se även

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Lokal URL till utdatafil. |
| saveFormat | HTMLSaveFormat | Format som dokumentet sparas i. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `url` inte är en giltig lokal fil-URL. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(Url, HTMLSaveFormat) metod

Det är nödvändigt att ange en fullständig Url-sökväg - 'outputFilePath' för att spara HTML-dokument. Konstruktorn Url(url) skapar en instans av klassen [`Url`](../../url/) med den angivna url:en. Uppräkningen [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) specificerar det format i vilket dokumentet sparas, det kan vara HTML, MHTML och MD-format. Därefter bör du skicka parametrarna till metoden Save(url, saveFormat). Dokumentet kommer att sparas i det angivna formatet till den lokala fil som anges av url.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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

### Se även

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Format som dokumentet sparas i. |

### Se även

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Sparar dokumentet till en lokal fil som anges av sökvägen. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som: output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | String | Lokal sökväg till utdatafil. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) objektet är för resurshanteringsprocessens hantering. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `path` inte är en giltig lokal filsökväg. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(String, HTMLSaveOptions) metod

Save(String, HTMLSaveOptions)-metoden tar som parametrar en lokal filsökväg till utdatafilen, en instans av klassen [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) och sparar ett HTML-dokument med resurser till den lokala fil som anges av sökvägen. Konstruktorn HTMLSaveOptions() skapar en instans av sparalternativ som har egenskaperna [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) som används för konfiguration av resurshantering. Alla resurser som används i dokumentet kommer att sparas i en intilliggande mapp.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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
	// Definiera alternativklassinstans
	var options = new HTMLSaveOptions();
	// Begränsning för sidhantering
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Se även

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Lokal [`URL`](../../url/) till utdatafil. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) objektet är för resurshanteringsprocessens hantering. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `url` inte är en giltig lokal fil-URL. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(Url, HTMLSaveOptions) metod

Det är nödvändigt att ange en fullständig Url-sökväg för att spara HTML-dokument. Konstruktorn Url(url) skapar en instans av klassen [`Url`](../../url/) med den angivna url:en. Konstruktorn HTMLSaveOptions() skapar en instans av klassen [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) som har egenskaper för ResourceHandlingOptions som används för konfiguration av resurshantering. Metoden Save(url, saveOptions) tar parametrar och sparar HTML-dokumentet med resurser till den lokala fil som anges av url.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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
	// Definiera alternativklassinstans
	var options = new HTMLSaveOptions();
	// Begränsning för sidhantering
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Se även

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | HTML-sparalternativ. |

### Se även

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Sparar dokumentet till en lokal fil som anges av sökvägen. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som: output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | String | Lokal sökväg till utdatafil. |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektet gör det möjligt att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `path` inte är en giltig lokal filsökväg. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(String, MarkdownSaveOptions) metod

Det är nödvändigt att ange en lokal filsökväg till utdatafilen för att spara dokumentet. Konstruktorn MarkdownSaveOptions() skapar en instans av klassen [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) som har en uppsättning egenskaper. Till exempel kan du ange markdown-formateringsstil, använda fördefinierade GitLab Flavored Markdown‑kompatibla alternativ och konfigurera resurshantering. Metoden Save(path, saveOptions) tar den lokala filsökvägen till utdatafilen och ett alternativobjekt som parametrar och sparar HTML som ett Markdown-dokument med resurser till den lokala fil som anges av sökvägen.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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
	// Definiera alternativklassinstans
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Se även

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Lokal [`URL`](../../url/) till utdatafil. |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) objektet gör det möjligt att finjustera renderingsprocessen. För mer info, se [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `url` inte är en giltig lokal fil-URL. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(Url, MarkdownSaveOptions) metod

Det är nödvändigt att ange en fullständig Url-sökväg för att spara dokumentet. Konstruktorn Url(url) skapar en instans av klassen [`Url`](../../url/) med den angivna url:en. Konstruktorn MarkdownSaveOptions() skapar en instans av klassen [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) som har en uppsättning egenskaper. Till exempel kan du ange Markdown-formateringsstil, använda fördefinierade GitLab Flavored Markdown‑kompatibla alternativ och konfigurera resurshantering. Metoden Save(url, saveOptions) tar url och sparalternativ som parametrar och sparar dokumentet med resurser till den lokala fil som anges av url.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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
	// Definiera alternativklassinstans
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Se även

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Markdown-sparalternativ. |

### Se även

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Sparar dokumentet till en lokal fil som anges av sökvägen. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp vars namn konstrueras som: output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | String | Lokal sökväg till utdatafil. |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objektet gör det möjligt att finjustera renderingsprocessen. För mer info, se [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `path` inte är en giltig lokal filsökväg. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(String, MHTMLSaveOptions) metod

Det är nödvändigt att ange en lokal filsökväg till utdatafilen för dokumentlagring. Konstruktoren MHTMLSaveOptions() initierar en instans av [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) klass som har egenskapen ResourceHandlingOptions som används för konfiguration av resurshantering. Metoden Save(path, saveOptions) tar en lokal filsökväg till utdatafilen och en instans av sparalternativ som parametrar och sparar HTML som ett MHTML-dokument till den lokala fil som anges av path.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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
	// Definiera alternativklassinstans
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Se även

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Sparar dokumentet till en lokal fil som anges av url. Alla resurser som används i detta dokument kommer att sparas i en intilliggande mapp, vars namn kommer att konstrueras som: output_file_name + "_files".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Lokal URL till utdatafil. |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) objektet gör det möjligt att finjustera renderingsprocessen. För mer info, se [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas om den angivna `url` inte är en giltig lokal fil-URL. |

## Anmärkningar

Spara HTML

De flesta uppgifter du behöver utföra kräver att ett dokument sparas. När du har laddat den befintliga filen eller skapat ett HTML-dokument från början kan du spara dina ändringar med någon av HTMLDocument.Save()-metoderna. Metoderna möjliggör att spara HTML till en lokal fil som anges av sökväg, URL eller utskriftslagring. Se [dokumentationen](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) för att lära dig mer om sparning.

Save(Url, MHTMLSaveOptions) metod

Det är nödvändigt att ange en fullständig Url-sökväg för dokumentlagring. Konstruktoren Url(url) skapar en instans av [`Url`](../../url/) klassen med den angivna url:en. Konstruktoren MHTMLSaveOptions() initierar en instans av [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) klass som har egenskapen ResourceHandlingOptions som används för konfiguration av resurshantering. Metoden Save(url, saveOptions) tar url och alternativ som parametrar och sparar HTML som ett MHTML-dokument till den lokala fil som anges av url.

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

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
	// Definiera alternativklassinstans
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### Se även

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Sparar dokumentets innehåll och resurser med hjälp av [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Resurshanteraren [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | MHTML-sparalternativ. |

### Se även

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
