---
title: "Converter.ConvertSVG"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Converter-methode. Converteer SVG-bron gepresenteerd door SVGDocument. Het resultaat is uitvoergegevens gevormd door een ICreateStreamProvider interface-implementatie."
type: docs

url: /nl/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Converteer SVG-bron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | SVGDocument | Conversiebron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Maak SVG-document als conversiebron
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Start conversieproces met standaard configuratie
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Converteer SVG-bron gepresenteerd door een volledig bestandspad naar XPS. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Converteer SVG-bron gepresenteerd door een volledig bestandspad naar XPS. Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Converteer SVG-bron gepresenteerd door inline-inhoud naar XPS. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Converteer SVG-bron gepresenteerd door inline-inhoud naar XPS. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Converteer SVG-bron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Het resultaat is een docx-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | SVGDocument | Conversiebron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Maak SVG-document als conversiebron
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Start conversieproces met standaard configuratie
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een docx-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(sourceUrl, options, resultPath);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een docx-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Converteer SVG-bron die wordt gepresenteerd via volledig bestandspad naar DOCX. Resultaat is een docx-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Converteer SVG-bron die wordt gepresenteerd via volledig bestandspad naar DOCX. Resultaat is een docx-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Converteer SVG-bron gepresenteerd door inline-inhoud. Resultaat is een docx-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier inline SVG-inhoud
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Converteer SVG-bron gepresenteerd door inline-inhoud. Resultaat is een docx-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Volledig docx-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier inline SVG-inhoud
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Converteer SVG-bron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | SVGDocument | Conversiebron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Maak SVG-document als conversiebron
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Start conversieproces met standaard configuratie
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een docx-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Converteer SVG-bron gepresenteerd door volledig bestandspad naar DOCX. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Converteer SVG-bron gepresenteerd door volledig bestandspad naar DOCX. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Converteer SVG-bron gepresenteerd door inline-inhoud naar DOCX. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Zie ook

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Converteer SVG-bron gepresenteerd door inline-inhoud naar DOCX. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | DocSaveOptions | Het gebruik van het [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) waar je informatie vindt over hoe je SVG naar [DOCX](https://docs.fileformat.com/word-processing/docx/) kunt converteren met de ConvertSVG()-methoden van de Converter-klasse en hoe je de [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar DOCX

De Converter-klasse biedt meerdere SVG-specifieke conversies naar DOCX. Om SVG naar DOCX te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een DOCX-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) die SVG naar DOCX converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard DocSaveOptions‑object
      var options = new DocSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Converteer SVG-bron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) naar PDF. Het resultaat is een pdf-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | SVGDocument | Conversiebron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Maak SVG-document als conversiebron
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Start conversieproces met standaard configuratie
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een pdf-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een pdf-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Converteer SVG-bron die wordt gepresenteerd via volledig bestandspad naar PDF. Resultaat is een pdf-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Converteer SVG-bron die wordt gepresenteerd via volledig bestandspad naar PDF. Resultaat is een pdf-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Converteer SVG-bron gepresenteerd door inline-inhoud naar PDF. Resultaat is een pdf-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier inline SVG-inhoud
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Converteer SVG-bron gepresenteerd door inline-inhoud naar PDF. Resultaat is een pdf-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Volledig pdf-bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier inline SVG-inhoud
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Converteer SVG-bron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) naar PDF. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | SVGDocument | Conversiebron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Maak SVG-document als conversiebron
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Start conversieproces met standaard configuratie
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Converteer SVG-bron gepresenteerd door volledig bestandspad naar PDF. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Converteer SVG-bron gepresenteerd door volledig bestandspad naar PDF. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Converteer SVG-bron gepresenteerd door inline-inhoud naar PDF. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Zie ook

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Converteer SVG-bron gepresenteerd door inline-inhoud naar PDF. Het resultaat is uitvoergegevens gevormd door de [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | PdfSaveOptions | Het gebruik van het [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Verwijs naar [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) waar je informatie vindt over hoe je SVG naar PDF kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters toepast.

Converteer SVG naar PDF

De Converter-klasse biedt meerdere SVG-specifieke conversies naar PDF. Om SVG naar PDF te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een String-bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) object aan met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een PDF-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) die SVG naar PDF converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard PdfSaveOptions‑object
      var options = new PdfSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Converteer SVG-bron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Het resultaat is een afbeeldingsbestand dat wordt aangemaakt op het opgegeven uitvoerpad.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | SVGDocument | Conversiebron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Maak SVG-document als conversiebron
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Start conversieproces met standaard configuratie
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een afbeeldingsbestand dat wordt aangemaakt op het opgegeven uitvoerpad.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Start conversieproces
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een afbeeldingsbestand dat wordt aangemaakt op het opgegeven uitvoerpad.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Converteer SVG-bron die wordt gepresenteerd via volledig bestandspad naar afbeelding. Resultaat is een afbeeldingsbestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Start conversieproces
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Converteer SVG-bron die wordt gepresenteerd via volledig bestandspad naar afbeelding. Resultaat is een afbeeldingsbestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Converteer SVG-bron gepresenteerd door inline-inhoud naar afbeelding. Resultaat is een afbeeldingsbestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier inline SVG-inhoud
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Converteer SVG-bron gepresenteerd door inline-inhoud naar afbeelding. Resultaat is een afbeeldingsbestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| outputPath | String | Volledig afbeeldingsbestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulier inline SVG-inhoud
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Converteer SVG-bron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | SVGDocument | Conversiebron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Maak SVG-document als conversiebron
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Start conversieproces
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is uitvoergegevens gevormd door een [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Converteer SVG-bron gepresenteerd door een volledig bestandspad naar afbeelding. Het resultaat is uitvoergegevens die worden gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Converteer SVG-bron gepresenteerd door een volledig bestandspad naar afbeelding. Het resultaat is uitvoergegevens die worden gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Converteer SVG-bron gepresenteerd door inline‑inhoud naar afbeelding. Het resultaat is uitvoergegevens die worden gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Bekend (zie [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Zie ook

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Converteer SVG-bron gepresenteerd door inline‑inhoud naar afbeelding. Het resultaat is uitvoergegevens die worden gevormd door een implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | ImageSaveOptions | Gebruik van het [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object stelt u in staat het renderproces af te stemmen. U kunt de [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) , de [`margins`](../../../com.aspose.html.drawing/page/margin/) , het [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) enz. specificeren. |
| provider | ICreateStreamProvider | Implementatie van de [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die zal worden gebruikt om een uitvoerstroom te verkrijgen. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Bekijk het [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) waar u informatie vindt over hoe u SVG naar JPG kunt converteren met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe u de parameters [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kunt toepassen. Andere gerelateerde artikelen over populaire afbeeldingsformaten: [SVG naar PNG-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG naar BMP-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG naar GIF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) en [SVG naar TIFF-conversie](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Converteer SVG naar afbeelding

De Converter-klasse biedt meerdere SVG-specifieke conversies naar afbeelding in populaire formaten. Om SVG naar afbeelding te converteren, moet u een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG‑bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. U kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG‑inhoud gebruiken die wordt gepresenteerd door een string‑bron. Conversieresultaat. Definieer het uitvoerpad voor het resultaat of gebruik een bekende of aangepaste implementatie van de interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als uitvoer‑databuffer. Maak een nieuw [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) object aan met specifieke of standaardinstellingen. Merk op dat het standaard afbeeldingsformaat PNG is. U kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter‑klasse om SVG op te slaan als een afbeeldingsresultaat met drie of meer parameters, afhankelijk van het gebruiksscenario. Online SVG‑converter

Aspose.HTML biedt een gratis online [SVG naar JPG-converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) die SVG naar JPG converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer uw bestanden en ontvang resultaten binnen enkele seconden!

Andere populaire afbeeldingsconverters voor verschillende formaten zijn hier te vinden: [SVG naar PNG-converter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG naar BMP-converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG naar GIF-converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) en [SVG naar TIFF-converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gebruik een van de ICreateStreamProvider-implementaties
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieer standaard ImageSaveOptions‑object
      var options = new ImageSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Converteer SVG-bron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Het resultaat is een XPS‑bestand dat wordt aangemaakt op het opgegeven uitvoerpad.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | SVGDocument | Conversiebron gepresenteerd door [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Volledig xps‑bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Maak SVG-document als conversiebron
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Start conversieproces met standaard configuratie
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een XPS‑bestand dat wordt aangemaakt op het opgegeven uitvoerpad.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Volledig xps‑bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Converteer SVG-bron gepresenteerd door [`URL`](../../../com.aspose.html/url/). Het resultaat is een XPS‑bestand dat wordt aangemaakt op het opgegeven uitvoerpad.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | SVG-brondocument [`URL`](../../../com.aspose.html/url/) - biedt een objectrepresentatie van een universele identifier (URL). |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Volledig xps‑bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Zie ook

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Converteer SVG-bron die wordt gepresenteerd via volledig bestandspad naar XPS. Resultaat is een xps-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| outputPath | String | Volledig xps‑bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Converteer SVG-bron die wordt gepresenteerd via volledig bestandspad naar XPS. Resultaat is een xps-bestand dat is gevormd door het uitvoerbestandspad.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourcePath | String | Volledig bestandspad van SVG-bron. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Volledig xps‑bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Converteer SVG-bron gepresenteerd door inline-inhoud naar XPS. Resultaat is een xps-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. |
| outputPath | String | Volledig xps‑bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier inline SVG-inhoud
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Start conversieproces
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Converteer SVG-bron gepresenteerd door inline-inhoud naar XPS. Resultaat is een xps-bestand gevormd door het uitvoerpad.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | String als inline SVG-inhoud. |
| baseUri | String | De basis-URI van het document. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| configuration | Configuration | De omgevingsconfiguratie. Vertegenwoordigt het [`configuration`](../../../com.aspose.html/configuration/) contextobject dat wordt gebruikt om de omgevingsinstellingen voor de applicatie in te stellen. |
| options | XpsSaveOptions | Het gebruik van het [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object stelt je in staat het renderproces af te stemmen. Voor meer info zie [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Volledig xps‑bestandspad als uitvoerconversieresultaat. |

## Opmerkingen

SVG-converter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Zie [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) waar je informatie vindt over hoe je SVG naar XPS converteert met de ConvertSVG()-methoden van de [`Converter`](../) klasse en hoe je de parameters [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) en [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) toepast.

Converteer SVG naar XPS

De Converter-klasse biedt meerdere SVG-specifieke conversies naar XPS. Om SVG naar XPS te converteren, moet je een van de eenvoudige scenario's volgen die uit enkele stappen bestaan:

Conversiebron. Detecteer een bestaand lokaal SVG-bestand of een externe [`Url`](../../../com.aspose.html/url/) als conversiebron. Je kunt ook een [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) definiëren als conversiebron of zelfs inline SVG-inhoud gebruiken die wordt gepresenteerd door een stringbron. Conversieresultaat. Definieer het uitvoerbestandspad of gebruik een bekende of aangepaste [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface-implementatie als uitvoergegevensbuffer. Maak een nieuw [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) object met specifieke of standaardinstellingen. Je kunt ook [`configuration`](../../../com.aspose.html/configuration/) toevoegen als optionele parameter. Gebruik de ConvertSVG()-methode van de Converter-klasse om SVG op te slaan als een XPS-resultaat met drie of meer parameters, afhankelijk van het gebruikersscenario. Online SVG-converter

Aspose.HTML biedt een gratis online [SVG naar XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) die SVG naar XPS converteert met hoge kwaliteit, eenvoudig en snel. Upload gewoon, converteer je bestanden en krijg resultaten binnen enkele seconden!

Broncode

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulier inline SVG-inhoud
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulier resultaat‑bestandspad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definieer standaard XpsSaveOptions-object
      var options = new XpsSaveOptions();

      // Start conversieproces met standaard configuratie
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Zie ook

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
