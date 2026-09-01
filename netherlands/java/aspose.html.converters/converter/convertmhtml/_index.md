---
title: "Converter.ConvertMHTML"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Converter-methode. Converteer MHTML-bron gepresenteerd door invoerstroom. Resultaat is een XPS‑bestand gevormd door het uitvoerbestandspad"
type: docs

url: /nl/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Converteer MHTML-bron gepresenteerd via invoerstroom [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). Resultaat is xps-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom mhtml (.mht). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar XPS. Resultaat is een xps-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definieer standaard XpsSaveOptions‑object
	var options = new XpsSaveOptions();

	// Start conversieproces
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Converteer MHTML-bron gepresenteerd via URL. Resultaat is een xps-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulier bronbestandspad
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Formulier resultaat‑bestandspad
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definieer standaard XpsSaveOptions‑object
	var options = new XpsSaveOptions();

	// Start conversieproces
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Converteer MHTML-bron gepresenteerd via invoer-[stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0). Resultaat is een xps-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Conversiebron mhtml (.mht) gegevensstroom. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar XPS. Resultaat is een xps-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Converteer MHTML-bron gepresenteerd via URL. Resultaat is een xps-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Volledig xps-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Converteer MHTML-bron gepresenteerd via invoerstroom. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Conversiebron mhtml (.mht) gegevensstroom. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar XPS. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Converteer MHTML-bron gepresenteerd via [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io; 
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Converteer MHTML-bron gepresenteerd via invoerstroom. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Conversiebron mhtml (.mht) gegevensstroom. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar XPS. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Converteer MHTML-bron gepresenteerd via URL. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentatie](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

MHTML-converter

MHTML naar [XPS](https://docs.fileformat.com/page-description-language/xps/) conversie is vaak vereist om voordeel te halen uit het XPS‑formaat voor specifieke taken. Een XPS‑bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft.

Zie het [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) waar u informatie vindt over hoe u MHTML naar XPS kunt converteren met de ConvertHTML()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar XPS

De Converter‑klasse biedt enkele MHTML‑specifieke conversies naar XPS. Om MHTML naar XPS te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML‑(.mht)‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object aan met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter‑klasse om MHTML op te slaan als een XPS‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar XPS-converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) die MHTML naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions‑object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Converteer MHTML-bron gepresenteerd via invoerstroom. Resultaat is docx-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar DOCX. Resultaat is docx-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | MHTML-bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Converteer MHTML-bron gepresenteerd via URL. Resultaat is een docx-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Converteer MHTML-bron gepresenteerd via invoerstroom. Resultaat is docx-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar DOCX. Resultaat is docx-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Converteer MHTML-bron gepresenteerd via [`URL`](../../../com.aspose.html/url/). Het resultaat is een docx-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Converteer MHTML-bron gepresenteerd via invoerstroom. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar DOCX. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Converteer MHTML-bron gepresenteerd via URL. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Converteer MHTML-bron gepresenteerd via invoerstroom. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar DOCX. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook configuration toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Converteer MHTML-bron gepresenteerd via [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar DOCX is vaak vereist om gebruik te maken van het [DOCX](https://docs.fileformat.com/word-processing/docx/) formaat voor specifieke taken. DOCX is een bekend formaat voor Microsoft Word-documenten. Het kan een breed scala aan gegevens bevatten, waaronder tekst, tabellen, raster- en vectorafbeeldingen, video, geluiden en diagrammen. Dit formaat is populair omdat het complexe opmaakfuncties ondersteunt en gebruikers een verscheidenheid aan opties biedt om elk type document te maken.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) waar u informatie vindt over hoe u MHTML naar DOCX kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar DOCX

De Converter-klasse biedt enkele MHTML-specifieke conversies naar DOCX. Om MHTML naar DOCX te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een standaard of aangepaste specifieke stream gebruiken als conversiebron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object met specifieke of standaardinstellingen. U kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()-methode van de Converter-klasse om MHTML op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) die MHTML naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Converteer MHTML-bron gepresenteerd via invoerstroom. Resultaat is pdf-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is een pdf-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Converteer MHTML-bron gepresenteerd via URL. Resultaat is een pdf-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Converteer MHTML-bron gepresenteerd via invoerstroom. Resultaat is pdf-bestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Converteer MHTML-bron gepresenteerd via volledig bestandspad naar PDF. Resultaat is een pdf-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | MHTML-bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Converteer MHTML-bron gepresenteerd via URL. Resultaat is een pdf-bestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Converteer MHTML-bron gepresenteerd via invoerstroom. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Converteer MHTML-bron, gepresenteerd via volledig bestandspad, naar PDF. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | MHTML-bronbestandspad. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Converteer MHTML-bron gepresenteerd via URL. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Converteer MHTML-bron gepresenteerd via invoerstroom. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Converteer MHTML-bron, gepresenteerd via volledig bestandspad, naar PDF. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Converteer MHTML-bron gepresenteerd via [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) objectgebruik stelt u in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Conversie van MHTML naar PDF is vaak vereist om gebruik te maken van het [PDF](https://docs.fileformat.com/pdf/) formaat voor specifieke taken. PDF biedt veel voordelen die andere bestanden niet hebben. Bijvoorbeeld, veel programma's en apps ondersteunen PDF-documenten; PDF-bestanden zijn geoptimaliseerd voor afdrukken, en ze zijn ideaal voor het maken van fysieke kopieën van uw documenten; u kunt de beveiligingsinstellingen voor PDF-bestanden configureren - afdrukken, bewerken, gebruik van een elektronische handtekening, enz. uitschakelen.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), waar u informatie vindt over hoe u MHTML naar PDF kunt converteren met behulp van de ConvertMHTML()-methoden van de klasse [`Converter`](../) en hoe u de parameters [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer MHTML naar PDF

Converter class biedt enkele MHTML-specifieke conversies naar PDF. Om MHTML naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe Url als conversiebron. Je kunt ook een standaard of aangepaste specifieke [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een PDF‑resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) die MHTML naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Converteer MHTML-bron gepresenteerd via invoerstroom naar afbeelding. Resultaat is afbeeldingsbestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Converteer MHTML-bron gepresenteerd via volledig bestandspad. Resultaat is afbeeldingsbestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Start conversieproces
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Converteer MHTML-bron gepresenteerd via URL. Resultaat is een afbeeldingsbestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Start conversieproces
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Converteer MHTML-bron gepresenteerd via invoerstroom naar afbeelding. Resultaat is afbeeldingsbestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Converteer MHTML-bron gepresenteerd via volledig bestandspad. Resultaat is afbeeldingsbestand gemaakt via het uitvoerbestandspad.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Converteer MHTML-bron gepresenteerd via URL. Resultaat is een afbeeldingsbestand gevormd door het uitvoerbestandspad.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Converteer MHTML-bron gepresenteerd via invoerstroom. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Converteer MHTML-bron, gepresenteerd via volledig bestandspad, naar afbeelding. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Converteer MHTML-bron gepresenteerd via URL. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Converteer MHTML-bron gepresenteerd via invoerstroom. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Invoergegevensstroom voor MHTML-conversie. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Converteer MHTML-bron, gepresenteerd via volledig bestandspad, naar afbeelding. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van de MHTML-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [` interface`](../../../com.aspose.html.io/icreatestreamprovider/) die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier bronbestandspad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Converteer MHTML-bron gepresenteerd via URL. Het resultaat is uitvoergegevens gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceUrl | Url | MHTML-brondocument-URL - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. |
| options | ImageSaveOptions | Het gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

MHTML-converter

Bestanden met de extensie [MHTML](https://docs.fileformat.com/web/mhtml/) vertegenwoordigen een webpagina-archiefformaat dat door verschillende applicaties kan worden aangemaakt. Het formaat staat bekend als archiefformaat omdat het de web‑HTML‑code en bijbehorende bronnen in één bestand opslaat. Deze bronnen omvatten alles wat aan de webpagina is gekoppeld, zoals afbeeldingen, applets, animaties, audiobestanden enzovoort. MHTML‑bestanden kunnen worden geopend in diverse applicaties zoals Internet Explorer en Microsoft Word. De feitelijke specificaties van het formaat worden gedetailleerd beschreven in [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Verwijs naar het artikel, waar je informatie vindt over hoe je MHTML naar afbeeldingen in verschillende formaten kunt converteren met behulp van de ConvertMHTML()-methoden van de Converter‑klasse en hoe je de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen.

Converteer MHTML naar afbeelding

Converter class biedt enkele MHTML-specifieke conversies naar afbeeldingen. Ondersteunde formaten zijn [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) en [TIFF](https://docs.fileformat.com/image/tiff/). Om MHTML naar een afbeelding te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal MHTML (.mht)-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een standaard of aangepaste specifieke stream gebruiken als bron. Conversieresultaat. Definieer het uitvoerpad van het resultaatbestand of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Het standaard afbeeldingsformaat is PNG. Je kunt ook configuratie toevoegen als optionele parameter. Gebruik de ConvertMHTML()‑methode van de Converter‑klasse om MHTML op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online MHTML-converter

Aspose.HTML biedt een gratis online [MHTML naar JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) die MHTML naar een jpeg‑bestand converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Maak Url op basis van invoer‑bestandspad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
