---
title: "Converter.ConvertMHTML"
second_title: "Aspose.HTML för Java API-referens"
description: "Converter‑metod. Konvertera MHTML-källan som presenteras av inmatningsström. Resultatet är en XPS-fil som bildas av utdatafilens sökväg"
type: docs

url: /sv/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Konvertera MHTML‑källa som presenteras via inmatnings‑[ström](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). Resultatet är xps‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Inmatnings‑mhtml (.mht) datastream. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Konvertera MHTML‑källa som anges med fullständig filsökväg till XPS. Resultatet är en xps‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär källfilssökväg
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Formulär resultatfilssökväg
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definiera standard‑XpsSaveOptions‑objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Konvertera MHTML‑källa som anges med URL. Resultatet är en xps‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulär källfilssökväg
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Formulär resultatfilssökväg
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definiera standard‑XpsSaveOptions‑objekt
	var options = new XpsSaveOptions();

	// Initiera konverteringsprocessen
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Konvertera MHTML‑källa som anges med inmatnings‑[stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0). Resultatet är en xps‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Konverteringskälla mhtml (.mht) datastream. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Konvertera MHTML‑källa som anges med fullständig filsökväg till XPS. Resultatet är en xps‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Konvertera MHTML‑källa som anges med URL. Resultatet är en xps‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Fullständig XPS‑filssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

Källkod

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulär källfilssökväg
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Konverteringskälla mhtml (.mht) datastream. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Konvertera MHTML‑källa som presenteras via fullständig filsökväg till XPS. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Konvertera MHTML‑källa som presenteras via [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Konverteringskälla mhtml (.mht) datastream. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Konvertera MHTML‑källa som presenteras via fullständig filsökväg till XPS. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Konvertera MHTML‑källa som presenteras via URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | XpsSaveOptions | Användning av objektet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) gör det möjligt att finjustera renderingsprocessen. För mer information, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

MHTML‑konverterare

MHTML till [XPS](https://docs.fileformat.com/page-description-language/xps/)‑konvertering krävs ofta för att utnyttja XPS-formatet för specifika uppgifter. En XPS-fil representerar sidlayoutfiler som är baserade på XML Paper Specifications, skapade av Microsoft.

Se [artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) där du hittar information om hur du konverterar MHTML till XPS med ConvertHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till XPS

Klassen Converter erbjuder några MHTML-specifika konverteringar till XPS. För att konvertera MHTML till XPS bör du följa ett av de enkla scenarierna som består av några steg:

Källan för konvertering. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Resultat av konvertering. Definiera utdatafilens sökväg eller använd en känd eller anpassad implementation av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som ett alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett XPS‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till XPS‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-xps) som konverterar MHTML till XPS med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑XpsSaveOptions‑objekt
      var options = new XpsSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är docx‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Konvertera MHTML‑källa som presenteras via fullständig filsökväg till DOCX. Resultatet är docx‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | MHTML‑källfilssökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Konvertera MHTML‑källa som anges med URL. Resultatet är en docx‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är docx‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Konvertera MHTML‑källa som presenteras via fullständig filsökväg till DOCX. Resultatet är docx‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Konvertera MHTML‑källa som presenteras via [`URL`](../../../com.aspose.html/url/). Resultatet är en docx‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Fullständig docx‑filväg som utskriftskonverteringsresultat. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Konvertera MHTML‑källa som presenteras via fullständig filsökväg till DOCX. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Konvertera MHTML‑källa som presenteras via URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Konvertera MHTML‑källa som presenteras via fullständig filsökväg till DOCX. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till konfiguration som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Konvertera MHTML‑källa som presenteras via [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument [`URL`](../../../com.aspose.html/url/) – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till DOCX‑konvertering krävs ofta för att dra nytta av [DOCX](https://docs.fileformat.com/word-processing/docx/)‑formatet för specifika uppgifter. DOCX är ett välkänt format för Microsoft Word‑dokument. Det kan innehålla ett brett spektrum av data, inklusive text, tabeller, raster‑ och vektorgrafik, video, ljud och diagram. Detta format är populärt eftersom det stödjer komplexa formateringsfunktioner och ger användarna en mängd alternativ för att skapa vilken typ av dokument som helst.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) där du hittar information om hur du konverterar MHTML till DOCX med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till DOCX

Klassen Converter erbjuder några MHTML‑specifika konverteringar till DOCX. För att konvertera MHTML till DOCX bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr‑[`Url`](../../../com.aspose.html/url/) som konverteringskälla. Du kan också använda en standard‑ eller anpassad specifik ström som konverteringskälla. Konverteringsresultat. Definiera resultatets utskriftsfilssökväg eller använd en känd eller anpassad implementering av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) som utdata‑buffert. Skapa ett nytt [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till konfiguration som alternativparameter. Använd ConvertMHTML()-metoden i klassen Converter för att spara MHTML som ett DOCX‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online‑[MHTML till DOCX‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-docx) som konverterar MHTML till DOCX med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard DocSaveOptions‑objekt
      var options = new DocSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### Se även

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är pdf‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till [`configuration`](../../../com.aspose.html/configuration/) som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Konvertera MHTML‑källa som anges med fullständig filsökväg till PDF. Resultatet är en pdf‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Konvertera MHTML‑källa som anges med URL. Resultatet är en pdf‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är pdf‑fil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Konvertera MHTML‑källa som anges med fullständig filsökväg till PDF. Resultatet är en pdf‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | MHTML‑källfilssökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Konvertera MHTML‑källa som anges med URL. Resultatet är en pdf‑fil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Fullständig pdf‑filväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Konvertera MHTML‑källan som anges med fullständig filsökväg till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | MHTML‑källfilssökväg. Den kommer att kombineras med den aktuella katalogens sökväg för att bilda en absolut URL. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Konvertera MHTML‑källa som presenteras via URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Konvertera MHTML‑källan som anges med fullständig filsökväg till PDF. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Konvertera MHTML‑källa som presenteras via [`URL`](../../../com.aspose.html/url/). Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)`‑objektet möjliggör att finjustera renderingsprocessen. För mer info, se [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

MHTML till PDF‑konvertering krävs ofta för att dra nytta av [PDF](https://docs.fileformat.com/pdf/)‑formatet för specifika uppgifter. PDF har många fördelar som andra filer inte har. Till exempel stöder många program och appar PDF‑dokument; PDF‑filer är optimerade för utskrift, och de är idealiska för att skapa fysiska kopior av dina dokument; du kan konfigurera säkerhetsinställningarna för PDF‑filer – inaktivera utskrift, redigering, användning av elektronisk signatur, etc.

Se [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), där du hittar information om hur du konverterar MHTML till PDF med ConvertMHTML()-metoderna i klassen [`Converter`](../) och hur du använder parametrarna [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konvertera MHTML till PDF

Converter-klassen erbjuder några MHTML-specifika konverteringar till PDF. För att konvertera MHTML till PDF bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-Url som konverteringskälla. Du kan också använda standard- eller anpassad specifik [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑objekt med specifika eller standardinställningar. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett PDF‑resultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till PDF‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) som konverterar MHTML till PDF med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standard‑PdfSaveOptions‑objekt
      var options = new PdfSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Konvertera MHTML‑källa som presenteras via inmatningsström till bild. Resultatet är bildfil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Konvertera MHTML‑källa som presenteras via fullständig filsökväg. Resultatet är bildfil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Se även

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Konvertera MHTML‑källa som anges med URL. Resultatet är en bildfil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Konvertera MHTML‑källa som presenteras via inmatningsström till bild. Resultatet är bildfil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Konvertera MHTML‑källa som presenteras via fullständig filsökväg. Resultatet är bildfil som bildas av utskriftsfilens sökväg.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Konvertera MHTML‑källa som anges med URL. Resultatet är en bildfil som skapas av utdatans filsökväg.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Fullständig bildfilssökväg som utdata för konverteringsresultatet. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Konvertera MHTML‑källan som anges med fullständig filsökväg till bild. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Konvertera MHTML‑källa som presenteras via URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Känd (se [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) eller anpassad implementering av gränssnittet [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Konvertera MHTML‑källa som presenteras via inmatningsström. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | MHTML‑konverteringsinmatningsdatastream. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Initiera konverteringsprocessen
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Konvertera MHTML‑källan som anges med fullständig filsökväg till bild. Resultatet är utdata som bildas av [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourcePath | String | Fullständig filsökväg för MHTML‑källa. |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementering av [` interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få en utström. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions();

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Konvertera MHTML‑källa som presenteras via URL. Resultatet är utdata som bildas av implementeringen av gränssnittet [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceUrl | Url | MHTML‑källdokument‑URL – tillhandahåller en objektrepresentation av en universell identifierare (URL). |
| configuration | Configuration | Miljökonfigurationen. Representerar [`configuration`](../../../com.aspose.html/configuration/) kontextobjektet som används för att ställa in miljöinställningarna för applikationen. |
| options | ImageSaveOptions | Användning av objektet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) gör att du kan finjustera renderingsprocessen. Du kan specificera [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implementering av [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), som kommer att användas för att få ett utdataflöde. |

## Anmärkningar

MHTML‑konverterare

Filer med [MHTML](https://docs.fileformat.com/web/mhtml/)‑extension representerar ett webbsidesarkivformat som ett antal olika program kan skapa. Formatet är känt som arkivformat eftersom det sparar webbsidans HTML‑kod och tillhörande resurser i en enda fil. Dessa resurser inkluderar allt som är länkat till webbsidan såsom bilder, appletar, animationer, ljudfiler osv. MHTML‑filer kan öppnas i olika program som Internet Explorer och Microsoft Word. De faktiska specifikationerna för formatet beskrivs i detalj av [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Se artikeln där du hittar information om hur du konverterar MHTML till bilder i olika format med hjälp av ConvertMHTML()-metoderna i Converter‑klassen och hur du använder [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) och [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parametrar.

Konvertera MHTML till bild

Converter‑klassen erbjuder några MHTML‑specifika konverteringar till bilder. Stödda format är [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) och [TIFF](https://docs.fileformat.com/image/tiff/). För att konvertera MHTML till bild bör du följa ett av de enkla scenarierna som består av några steg:

Konverteringskälla. Upptäck en befintlig lokal MHTML (.mht)-fil eller fjärr-`Url` som konverteringskälla. Du kan också använda standard‑ eller anpassad specifik stream som källa. Konverteringsresultat. Definiera resultatets utdatafilssökväg eller använd en känd eller anpassad [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) gränssnittimplementation som utdata‑buffer. Skapa ett nytt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑objekt med specifika eller standardinställningar. Standardbildformat är PNG. Du kan även lägga till configuration som alternativparameter. Använd ConvertMHTML()-metoden i Converter‑klassen för att spara MHTML som ett bildresultat med tre eller fler parametrar beroende på användarscenariot. Online MHTML‑konverterare

Aspose.HTML erbjuder en gratis online [MHTML till JPEG‑konverterare](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) som konverterar MHTML till jpeg‑fil med hög kvalitet, enkelt och snabbt. Ladda bara upp, konvertera dina filer och få resultat på några sekunder!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulär resultatfilssökväg
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definiera standardobjektet ImageSaveOptions
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Använd en av ICreateStreamProvider-implementeringarna
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initiera konverteringsprocessen med standardkonfiguration
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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
