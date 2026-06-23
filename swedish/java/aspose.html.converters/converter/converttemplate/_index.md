---
title: "Converter.ConvertTemplate"
second_title: "Aspose.HTML för Java API-referens"
description: "Converter‑metod. Slå samman mallkälla som presenteras av HTMLDocument med malldata XML JSON. Resultatet är en HTML‑fil som bildas av utdatafilens sökväg."
type: docs

url: /sv/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Slå samman mallkälla som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/) med malldata (XML, JSON). Resultatet är en HTML‑fil som bildas av utdatafilens sökväg.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| template | HTMLDocument | Sammanfogar källskelett som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulärs skelett‑HTML‑källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Formulär HTML‑dokument som konverteringskälla
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Initiera konverteringsprocessen
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Rensa resurser
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Sammanfoga mall‑HTML‑källa som presenteras via [`URL`](../../../com.aspose.html/url/) med malldata (XML, JSON). Resultatet är en HTML‑fil som skapas enligt utskriftsfilens sökväg.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Sammanfogar HTML‑källskelett som presenteras via [`URL`](../../../com.aspose.html/url/). |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär skelett‑HTML‑käll‑URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Sammanfoga mall‑HTML‑källa som presenteras via [`URL`](../../../com.aspose.html/url/) med malldata (XML, JSON). Resultatet är en HTML‑fil som skapas enligt utskriftsfilens sökväg.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Sammanfogar HTML‑källskelett som presenteras via [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär skelett‑HTML‑käll‑URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Sammanfoga mallens HTML-källa som presenteras av fullständig filsökväg med malldata (XML, JSON). Resultatet är en html-fil som bildas av utdatans filsökväg.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sammanfogar HTML‑källskelett som presenteras via fullständig filsökväg. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulärs skelett‑HTML‑källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Se även

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Sammanfoga mallens HTML-källa som presenteras av fullständig filsökväg med malldata (XML, JSON). Resultatet är en html-fil som bildas av utdatans filsökväg.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sammanfogar HTML‑källskelett som presenteras via fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulärs skelett‑HTML‑källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Sammanfoga mallens HTML-källa som presenteras av inbäddat innehåll med malldata (XML, JSON). Resultatet är en html-fil som bildas av utdatans filsökväg.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sammanfogar HTML‑källskelett som presenteras via inline‑String‑innehåll. |
| baseUrl | String | Bas-URI för HTML‑mallen. Den kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Formulär inline‑källinnehåll som mall
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
       
      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulärutdata som sammanfogningsresultat 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();
	  
      // Initiera konverteringsprocessen
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

### Se även

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Sammanfoga mallens HTML-källa som presenteras av inbäddat innehåll med malldata (XML, JSON). Resultatet är en html-fil som bildas av utdatans filsökväg.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sammanfogar HTML‑källskelett som presenteras via inline‑String‑innehåll. |
| baseUrl | String | Bas-URI för HTML‑mallen. Den kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |
| outputPath | String | Fullständig HTML‑filväg som utdata för konverteringsresultat. |

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Formulär inline‑källinnehåll som mall
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
    
   // Formulär XML (JSON) malldatafilssökväg
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Definiera TemplateData‑objektinstans
   var templateData = new TemplateData(templateDataPath);

   // Formulärutdata som sammanfogningsresultat 
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Definiera configuration‑objektinstans
   var configuration = new Configuration();

   // Definiera standard‑TemplateLoadOptions‑objekt
   var options = new TemplateLoadOptions();

   // Initiera konverteringsprocessen med standardkonfiguration
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Nedan är datafilen att slå ihop med källan som mall

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

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Slå ihop mallkällan som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/) med malldata (XML, JSON). Resultatet är ett nytt bildat HTMLDocument som kan sparas som fil.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| template | HTMLDocument | Sammanfogar källskelett som presenteras av [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulärs skelett‑HTML‑källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();
      
      // Formulär HTML‑dokument som konverteringskälla
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Initiera konverteringsprocessen
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Spara resultatet med länkade resurser
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Slå ihop mall-HTML-källan som presenteras av [`URL`](../../../com.aspose.html/url/) med malldata (XML, JSON). Resultatet är ett nytt bildat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas som fil.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Sammanfogar HTML‑källskelett som presenteras via [`URL`](../../../com.aspose.html/url/). |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url till skelett-HTML-källfil
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Spara resultatet med länkade resurser
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Slå ihop mall-HTML-källan som presenteras av [`URL`](../../../com.aspose.html/url/) med malldata (XML, JSON). Resultatet är ett nytt bildat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas som fil.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Sammanfogar HTML‑källskelett som presenteras via [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url till skelett-HTML-källfil
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Spara resultatet med länkade resurser
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Se även

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

Slå ihop mall-HTML-källan som presenteras av fullständig filsökväg med malldata (XML, JSON). Resultatet är ett nytt bildat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas som fil.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sammanfogar HTML‑källskelett som presenteras via fullständig filsökväg. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulärs skelett‑HTML‑källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Spara resultatet med länkade resurser
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Slå ihop mall-HTML-källan som presenteras av fullständig filsökväg med malldata (XML, JSON). Resultatet är ett nytt bildat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas som fil.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Sammanfogar HTML‑källskelett som presenteras via fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulärs skelett‑HTML‑källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Spara resultatet med länkade resurser
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Slå ihop mall-HTML-källan som presenteras av inbäddat innehåll med malldata (XML, JSON). Resultatet är ett nytt bildat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas som fil.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sammanfogar HTML‑källskelett som presenteras via inline‑String‑innehåll. |
| baseUrl | String | Bas-URI för HTML‑mallen. Den kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär inline‑källinnehåll som mall
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

      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulärutdata som sammanfogningsresultat 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen och spara resultatet
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

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Slå ihop mall-HTML-källan som presenteras av inbäddat innehåll med malldata (XML, JSON). Resultatet är ett nytt bildat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som kan sparas som fil.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sammanfogar HTML‑källskelett som presenteras via inline‑String‑innehåll. |
| baseUrl | String | Bas-URI för HTML‑mallen. Den kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| data | TemplateData | Malldata för sammanslagning - ersättning (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objektinstans. Den används för att avgöra om mall- och dataobjektnamnen matchar, oavsett om de är skiftlägeskänsliga eller inte (alternativ). |

### Returvärde

Nytt skapat [`HTMLDocument`](../../../com.aspose.html/htmldocument/) som konverteringsresultat som kan sparas via utdatafilens sökväg.

## Anmärkningar

Mallsammanfogare

Idén med mallsammanfogning är att skapa ett HTML‑dokument baserat på en HTML‑mall och fylla det från en datakälla. Aspose.HTML tillhandahåller syntaxen för inline‑uttryck för att arbeta med mallar och olika typer av datakällor, såsom XML och JSON. Se [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) där du kan hitta mer information om mallsammanfogning och användning av metoden ConvertTemplate().

Steg för konvertering (sammanfogning)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Mallkälla. Definiera HTML‑mallkälla via fil, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objektinstans eller även via inline‑innehåll. Konverteringsresultat. Du kan direkt erhålla det resulterande HTMLDocument eller definiera sökväg för utdatafil beroende på metodsignatur. Skapa en instans av [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Använd ConvertTemplate()-metoden i Converter‑klassen för att sammanfoga mallen med data. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär inline‑källinnehåll som mall
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
       
      // Formulär XML (JSON) malldatafilssökväg
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definiera TemplateData‑objektinstans
      var templateData = new TemplateData(templateDataPath);

      // Formulärutdata som sammanfogningsresultat 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definiera configuration‑objektinstans
      var configuration = new Configuration();

      // Definiera standard‑TemplateLoadOptions‑objekt
      var options = new TemplateLoadOptions();

      // Initiera konverteringsprocessen och spara resultatet
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

### Se även

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
