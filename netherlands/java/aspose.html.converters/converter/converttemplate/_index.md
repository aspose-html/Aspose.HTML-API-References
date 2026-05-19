---
title: "Converter.ConvertTemplate"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Converter-methode. Voeg sjabloonbron samen, gepresenteerd door HTMLDocument, met sjabloongegevens XML JSON. Resultaat is html‑bestand gevormd door het uitvoerbestandspad."
type: docs

url: /nl/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Voeg sjabloonbron samen, gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/), met sjabloongegevens (XML, JSON). Resultaat is html‑bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| template | HTMLDocument | Samenvoegen van bron‑skelet gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier‑skelet html‑bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Formulier HTML‑document als conversiebron
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Start conversieproces
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Resources vrijgeven
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Voeg sjabloon‑HTML‑bron, gepresenteerd via [`URL`](../../../com.aspose.html/url/) samen met sjabloongegevens (XML, JSON). Het resultaat is een html‑bestand dat wordt aangemaakt op het uitvoerpad.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Samenvoegen van HTML‑bron‑skelet gepresenteerd via [`URL`](../../../com.aspose.html/url/). |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier skelet html‑bron‑Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start conversieproces
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Voeg sjabloon‑HTML‑bron, gepresenteerd via [`URL`](../../../com.aspose.html/url/) samen met sjabloongegevens (XML, JSON). Het resultaat is een html‑bestand dat wordt aangemaakt op het uitvoerpad.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Samenvoegen van HTML‑bron‑skelet gepresenteerd via [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier skelet html‑bron‑Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie 
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Voeg sjabloon-HTML-bron gepresenteerd door volledig bestandspad samen met sjabloongegevens (XML, JSON). Resultaat is een html-bestand gevormd door het uitvoerpad.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Samenvoegen van HTML‑bron‑skelet gepresenteerd via volledig bestandspad. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier‑skelet html‑bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start conversieproces
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Zie ook

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Voeg sjabloon-HTML-bron gepresenteerd door volledig bestandspad samen met sjabloongegevens (XML, JSON). Resultaat is een html-bestand gevormd door het uitvoerpad.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Samenvoegen van HTML‑bron‑skelet gepresenteerd via volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier‑skelet html‑bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Voeg sjabloon-HTML-bron gepresenteerd door inline-inhoud samen met sjabloongegevens (XML, JSON). Resultaat is een html-bestand gevormd door het uitvoerpad.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | Samenvoegen van HTML‑bron‑skelet gepresenteerd via inline‑String‑inhoud. |
| baseUrl | String | Basis‑URI van de html‑sjabloon. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Formulier inline‑broninhoud als sjabloon
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
       
      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier uitvoer als samenvoegresultaat 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();
	  
      // Start conversieproces
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

### Zie ook

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Voeg sjabloon-HTML-bron gepresenteerd door inline-inhoud samen met sjabloongegevens (XML, JSON). Resultaat is een html-bestand gevormd door het uitvoerpad.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | Samenvoegen van HTML‑bron‑skelet gepresenteerd via inline‑String‑inhoud. |
| baseUrl | String | Basis‑URI van de html‑sjabloon. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |
| outputPath | String | Volledig html-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Formulier inline‑broninhoud als sjabloon
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
    
   // Formulier xml (json) sjabloongegevensbestandspad
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Definieer TemplateData objectinstantie
   var templateData = new TemplateData(templateDataPath);

   // Formulier uitvoer als samenvoegresultaat 
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Definieer configuration objectinstantie
   var configuration = new Configuration();

   // Definieer standaard TemplateLoadOptions object
   var options = new TemplateLoadOptions();

   // Start conversieproces met standaard configuratie
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Hieronder staat het gegevensbestand om te combineren met de bron als sjabloon

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

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Combineer de sjabloonbron gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/) met sjabloongegevens (XML, JSON). Het resultaat is een nieuw gevormd HTMLDocument dat als bestand kan worden opgeslagen.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| template | HTMLDocument | Samenvoegen van bron‑skelet gepresenteerd door [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier‑skelet html‑bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();
      
      // Formulier HTML‑document als conversiebron
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Start conversieproces
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Sla het resultaat op met gekoppelde bronnen
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Combineer de sjabloon-HTML-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/) met sjabloongegevens (XML, JSON). Het resultaat is een nieuw gevormd [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dat als bestand kan worden opgeslagen.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Samenvoegen van HTML‑bron‑skelet gepresenteerd via [`URL`](../../../com.aspose.html/url/). |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak een URL voor het skelet-HTML-bronbestand
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start conversieproces
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Sla het resultaat op met gekoppelde bronnen
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Combineer de sjabloon-HTML-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/) met sjabloongegevens (XML, JSON). Het resultaat is een nieuw gevormd [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dat als bestand kan worden opgeslagen.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | Samenvoegen van HTML‑bron‑skelet gepresenteerd via [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak een URL voor het skelet-HTML-bronbestand
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start conversieproces met standaard configuratie
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Sla het resultaat op met gekoppelde bronnen
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Zie ook

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

Combineer de sjabloon-HTML-bron gepresenteerd door een volledig bestandspad met sjabloongegevens (XML, JSON). Het resultaat is een nieuw gevormd [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dat als bestand kan worden opgeslagen.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Samenvoegen van HTML‑bron‑skelet gepresenteerd via volledig bestandspad. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier‑skelet html‑bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start conversieproces
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Sla het resultaat op met gekoppelde bronnen
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Combineer de sjabloon-HTML-bron gepresenteerd door een volledig bestandspad met sjabloongegevens (XML, JSON). Het resultaat is een nieuw gevormd [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dat als bestand kan worden opgeslagen.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Samenvoegen van HTML‑bron‑skelet gepresenteerd via volledig bestandspad. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier‑skelet html‑bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start conversieproces met standaard configuratie
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Sla het resultaat op met gekoppelde bronnen
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Combineer de sjabloon-HTML-bron gepresenteerd door inline-inhoud met sjabloongegevens (XML, JSON). Het resultaat is een nieuw gevormd [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dat als bestand kan worden opgeslagen.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | Samenvoegen van HTML‑bron‑skelet gepresenteerd via inline‑String‑inhoud. |
| baseUrl | String | Basis‑URI van de html‑sjabloon. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier inline‑broninhoud als sjabloon
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

      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier uitvoer als samenvoegresultaat 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start het conversieproces en sla het resultaat op
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

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Combineer de sjabloon-HTML-bron gepresenteerd door inline-inhoud met sjabloongegevens (XML, JSON). Het resultaat is een nieuw gevormd [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dat als bestand kan worden opgeslagen.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | Samenvoegen van HTML‑bron‑skelet gepresenteerd via inline‑String‑inhoud. |
| baseUrl | String | Basis‑URI van de html‑sjabloon. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| gegevens | TemplateData | Sjabloongegevens voor samenvoegen - substitutie (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objectinstantie. Het wordt gebruikt om te bepalen of de sjabloon- en gegevenselementnamen overeenkomen, ongeacht hoofdlettergebruik (opties). |

### Retourwaarde

Nieuw gevormde [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als conversieresultaat die kan worden opgeslagen via het uitvoerbestandspad.

## Opmerkingen

Sjabloonsamenvoeger

Het idee van sjabloonsamenvoeging is om een HTML-document te maken op basis van een html-sjabloon en het te vullen vanuit een gegevensbron. Aspose.HTML biedt de syntaxis voor inline‑expressies om met sjablonen en verschillende typen gegevensbronnen te werken, zoals XML en JSON. Zie [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) voor meer informatie over sjabloonsamenvoeging en het gebruik van de ConvertTemplate()-methode.

Conversie (samenvoeging) stappen

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sjabloonbron. Definieer de HTML-sjabloonbron via een bestand, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objectinstantie of zelfs via inline‑inhoud. Conversieresultaat. Je kunt direct het resulterende HTMLDocument verkrijgen of het uitvoerpad voor het resultaat definiëren, afhankelijk van de methode‑handtekening. Maak een instantie van [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gebruik de ConvertTemplate()-methode van de Converter‑klasse om het sjabloon met gegevens te samenvoegen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier inline‑broninhoud als sjabloon
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
       
      // Formulier xml (json) sjabloongegevensbestandspad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieer TemplateData objectinstantie
      var templateData = new TemplateData(templateDataPath);

      // Formulier uitvoer als samenvoegresultaat 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definieer configuration objectinstantie
      var configuration = new Configuration();

      // Definieer standaard TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Start het conversieproces en sla het resultaat op
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

### Zie ook

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
