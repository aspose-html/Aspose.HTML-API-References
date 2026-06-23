---
title: "Converter.ConvertSVG"
second_title: "Aspose.HTML för Java API-referens"
description: "Converter‑metod. Konvertera SVG‑källa som presenteras av SVGDocument. Resultatet är utdata som bildas av ICreateStreamProvider‑gränssnittets implementation"
type: docs

url: /sv/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Konvertera SVG‑källa som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SVGDocument | Konverteringskälla som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Skapa SVG‑dokument som konverteringskälla
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Initiera konverteringsprocessen med standardkonfiguration
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Konvertera SVG‑källa som presenteras av fullständig filsökväg till XPS. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Konvertera SVG‑källa som presenteras av fullständig filsökväg till XPS. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Konvertera SVG-källa som presenteras som inline-innehåll till XPS. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Konvertera SVG-källa som presenteras som inline-innehåll till XPS. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Konvertera SVG‑källa som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Resultatet är en docx‑fil som skapas av utskriftsfilens sökväg.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | SVGDocument | Konverteringskälla som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Skapa SVG‑dokument som konverteringskälla
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiera konverteringsprocessen med standardkonfiguration
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en docx‑fil som skapas av utskriftsfilens sökväg.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en docx‑fil som skapas av utskriftsfilens sökväg.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Konvertera SVG‑källa som anges med fullständig filsökväg till DOCX. Resultatet är en docx‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Konvertera SVG‑källa som anges med fullständig filsökväg till DOCX. Resultatet är en docx‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Konvertera SVG-källan som presenteras av inbäddat innehåll. Resultatet är en docx-fil som bildas av utdatans filsökväg.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formatera inline‑svg‑innehåll
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Konvertera SVG-källan som presenteras av inbäddat innehåll. Resultatet är en docx-fil som bildas av utdatans filsökväg.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formatera inline‑svg‑innehåll
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Konvertera SVG‑källa som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SVGDocument | Konverteringskälla som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Skapa SVG‑dokument som konverteringskälla
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiera konverteringsprocessen med standardkonfiguration
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en docx‑fil som skapas av utskriftsfilens sökväg.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Konvertera SVG‑källa som presenteras av fullständig filsökväg till DOCX. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Konvertera SVG‑källa som presenteras av fullständig filsökväg till DOCX. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Konvertera SVG‑källa som presenteras av inline‑innehåll till DOCX. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Konvertera SVG‑källa som presenteras av inline‑innehåll till DOCX. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | Användning av objektet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) där du hittar information om hur du konverterar SVG till [DOCX](https://docs.fileformat.com/word-processing/docx/) med ConvertSVG()-metoderna i Converter‑klassen och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till DOCX

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till DOCX. För att konvertera SVG till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till DOCX‑konverterare](https://products.aspose.app/svg/en/conversion/svg) som konverterar SVG till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Konvertera SVG‑källa som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) till PDF. Resultatet är en pdf‑fil som skapas av utskriftsfilens sökväg.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | SVGDocument | Konverteringskälla som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Skapa SVG‑dokument som konverteringskälla
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiera konverteringsprocessen med standardkonfiguration
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en pdf‑fil som skapas av utskriftsfilens sökväg.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en pdf‑fil som skapas av utskriftsfilens sökväg.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Konvertera SVG‑källa som anges med fullständig filsökväg till PDF. Resultatet är en pdf‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Konvertera SVG‑källa som anges med fullständig filsökväg till PDF. Resultatet är en pdf‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Konvertera SVG-källan som presenteras av inbäddat innehåll till PDF. Resultatet är en pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formatera inline‑svg‑innehåll
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Konvertera SVG-källan som presenteras av inbäddat innehåll till PDF. Resultatet är en pdf-fil som bildas av utdatans filsökväg.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formatera inline‑svg‑innehåll
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Konvertera SVG‑källa som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SVGDocument | Konverteringskälla som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Skapa SVG‑dokument som konverteringskälla
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiera konverteringsprocessen med standardkonfiguration
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Konvertera SVG‑källa som presenteras av fullständig filsökväg till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Konvertera SVG‑källa som presenteras av fullständig filsökväg till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Konvertera SVG‑källa som presenteras av inline‑innehåll till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Konvertera SVG‑källa som presenteras av inline‑innehåll till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | Användning av objektet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) där du hittar information om hur du konverterar SVG till PDF med ConvertSVG()-metoderna i [`Converter`](../)-klassen och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till PDF

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till PDF. För att konvertera SVG till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Detektera en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inline‑SVG‑innehåll som presenteras av en strängkälla. Konverteringsresultat. Ange sökväg för resultatfilen eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenario. Online‑SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till PDF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-pdf) som konverterar SVG till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Konvertera SVG-källan som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Resultatet är en bildfil som bildas av utdatafilens sökväg.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | SVGDocument | Konverteringskälla som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Skapa SVG‑dokument som konverteringskälla
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiera konverteringsprocessen med standardkonfiguration
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Konvertera SVG-källan som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en bildfil som bildas av utdatafilens sökväg.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Konvertera SVG-källan som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en bildfil som bildas av utdatafilens sökväg.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Konvertera SVG‑källa som anges med fullständig filsökväg till bild. Resultatet är en bildfil som skapas av utdatans filsökväg.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Konvertera SVG‑källa som anges med fullständig filsökväg till bild. Resultatet är en bildfil som skapas av utdatans filsökväg.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Konvertera SVG-källan som presenteras av inbäddat innehåll till bild. Resultatet är en bildfil som bildas av utdatans filsökväg.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formatera inline‑svg‑innehåll
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Konvertera SVG-källan som presenteras av inbäddat innehåll till bild. Resultatet är en bildfil som bildas av utdatans filsökväg.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formatera inline‑svg‑innehåll
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Konvertera SVG‑källa som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SVGDocument | Konverteringskälla som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Skapa SVG‑dokument som konverteringskälla
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initiera konverteringsprocessen
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Konvertera SVG‑källa som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittets implementation.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Konvertera SVG-källan som presenteras av fullständig filsökväg till bild. Resultatet är utdata som bildas av en implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Konvertera SVG-källan som presenteras av fullständig filsökväg till bild. Resultatet är utdata som bildas av en implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Konvertera SVG-källan som presenteras av inbäddat innehåll till bild. Resultatet är utdata som bildas av en implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Konvertera SVG-källan som presenteras av inbäddat innehåll till bild. Resultatet är utdata som bildas av en implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) där du hittar information om hur du konverterar SVG till JPG med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Andra populära bildformatrelaterade artiklar: [SVG till PNG-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG till BMP-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG till GIF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) och [SVG till TIFF-konvertering](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konvertera SVG till bild

Klassen Converter erbjuder flera SVG-specifika konverteringar till bild i populära format. För att konvertera SVG till bild bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal SVG-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG-innehåll som presenteras av en strängkälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata-buffert. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Observera att standardbildformatet är PNG. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertSVG()-metoden i klassen Converter för att spara SVG som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online [SVG till JPG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-jpg) som konverterar SVG till JPG med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Andra populära bildkonverterare för olika format kan hittas här: [SVG till PNG‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG till BMP‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG till GIF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-gif) och [SVG till TIFF‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Konvertera SVG-källan som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Resultatet är en XPS-fil som bildas av utdatafilens sökväg.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | SVGDocument | Konverteringskälla som presenteras av [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Skapa SVG‑dokument som konverteringskälla
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Initiera konverteringsprocessen med standardkonfiguration
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Konvertera SVG-källan som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en XPS-fil som bildas av utdatafilens sökväg.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg     
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Konvertera SVG-källan som presenteras av [`URL`](../../../com.aspose.html/url/). Resultatet är en XPS-fil som bildas av utdatafilens sökväg.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | SVG‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Skapa Url baserat på indatafilens sökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Konvertera SVG‑källa som anges med fullständig filsökväg till XPS. Resultatet är en xps‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Konvertera SVG‑källa som anges med fullständig filsökväg till XPS. Resultatet är en xps‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | SVG‑källa fullständig filsökväg. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Konvertera SVG-källan som presenteras av inbäddat innehåll till XPS. Resultatet är en xps-fil som bildas av utdatans filsökväg.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) objektanvändning gör det möjligt att finjustera renderingsprocessen. |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formatera inline‑svg‑innehåll
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Konvertera SVG-källan som presenteras av inbäddat innehåll till XPS. Resultatet är en xps-fil som bildas av utdatans filsökväg.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Sträng som inline‑svg‑innehåll. |
| baseUri | String | Bas-URI för dokumentet. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objektet gör att du kan finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

SVG‑konverterare

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) där du hittar information om hur du konverterar SVG till XPS med ConvertSVG()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera SVG till XPS

Converter‑klassen erbjuder flera SVG‑specifika konverteringar till XPS. För att konvertera SVG till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal SVG‑fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också definiera [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) som konverteringskälla eller till och med använda inbäddat SVG‑innehåll som presenteras av String‑källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittsimplementation som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan också lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertSVG()-metoden i Converter‑klassen för att spara SVG som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online SVG‑konverterare

Aspose.HTML erbjuder en gratis online‑[SVG till XPS‑konverterare](https://products.aspose.app/svg/en/conversion/svg-to-xps) som konverterar SVG till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formatera inline‑svg‑innehåll
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
