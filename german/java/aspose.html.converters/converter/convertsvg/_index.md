---
title: "`Converter.ConvertSVG`"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Converter‑Methode. Konvertieren Sie die SVG‑Quelle, die durch SVGDocument dargestellt wird. Das Ergebnis ist Ausgabedaten, die durch eine Implementierung der ICreateStreamProvider‑Schnittstelle erzeugt werden."
type: docs

url: /de/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Konvertieren Sie die SVG‑Quelle, die durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SVGDocument | Konvertierungsquelle, dargestellt durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG‑Dokument als Konvertierungsquelle erstellen
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Konvertierungsprozess mit Standardkonfiguration starten
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Konvertieren Sie die SVG‑Quelle, die durch einen vollständigen Dateipfad dargestellt wird, zu XPS. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Konvertieren Sie die SVG‑Quelle, die durch einen vollständigen Dateipfad dargestellt wird, zu XPS. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird, zu XPS. Das Ergebnis ist Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird, zu XPS. Das Ergebnis ist Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Konvertieren Sie die SVG-Quelle, die durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) bereitgestellt wird. Das Ergebnis ist eine DOCX-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | SVGDocument | Konvertierungsquelle, dargestellt durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // SVG‑Dokument als Konvertierungsquelle erstellen
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Konvertierungsprozess mit Standardkonfiguration starten
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Konvertieren Sie die SVG-Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine DOCX-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Konvertieren Sie die SVG-Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine DOCX-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Konvertieren Sie die SVG-Quelle, die über den vollständigen Dateipfad angegeben wird, nach DOCX. Ergebnis ist eine DOCX-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Konvertieren Sie die SVG-Quelle, die über den vollständigen Dateipfad angegeben wird, nach DOCX. Ergebnis ist eine DOCX-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird. Ergebnis ist eine DOCX-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Inline‑SVG‑Inhalt
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird. Ergebnis ist eine DOCX-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Inline‑SVG‑Inhalt
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Konvertieren Sie die SVG‑Quelle, die durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SVGDocument | Konvertierungsquelle, dargestellt durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG‑Dokument als Konvertierungsquelle erstellen
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Konvertierungsprozess mit Standardkonfiguration starten
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Konvertieren Sie die SVG-Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine DOCX-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Konvertieren Sie die SVG-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Konvertieren Sie die SVG-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Konvertieren Sie die SVG-Quelle, die als Inline‑Inhalt bereitgestellt wird, zu DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Konvertieren Sie die SVG-Quelle, die als Inline‑Inhalt bereitgestellt wird, zu DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) , in dem Sie Informationen darüber finden, wie Sie SVG zu [DOCX](https://docs.fileformat.com/word-processing/docx/) mit den ConvertSVG()-Methoden der Converter‑Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu DOCX konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu DOCX. Um SVG zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑DOCX‑Konverter](https://products.aspose.app/svg/en/conversion/svg), der SVG mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Konvertieren Sie die SVG-Quelle, die durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) bereitgestellt wird, zu PDF. Das Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | SVGDocument | Konvertierungsquelle, dargestellt durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // SVG‑Dokument als Konvertierungsquelle erstellen
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Konvertierungsprozess mit Standardkonfiguration starten
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Konvertieren Sie die SVG-Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Konvertieren Sie die SVG-Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Konvertieren Sie die SVG-Quelle, die über den vollständigen Dateipfad angegeben wird, nach PDF. Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Konvertieren Sie die SVG-Quelle, die über den vollständigen Dateipfad angegeben wird, nach PDF. Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird, zu PDF. Ergebnis ist eine PDF-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Inline‑SVG‑Inhalt
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird, zu PDF. Ergebnis ist eine PDF-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Inline‑SVG‑Inhalt
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Konvertieren Sie die SVG-Quelle, die durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) bereitgestellt wird, zu PDF. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SVGDocument | Konvertierungsquelle, dargestellt durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG‑Dokument als Konvertierungsquelle erstellen
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Konvertierungsprozess mit Standardkonfiguration starten
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Konvertieren Sie die SVG-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu PDF. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Konvertieren Sie die SVG-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu PDF. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Konvertieren Sie die SVG-Quelle, die als Inline‑Inhalt bereitgestellt wird, zu PDF. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Konvertieren Sie die SVG-Quelle, die als Inline‑Inhalt bereitgestellt wird, zu PDF. Das Ergebnis sind Ausgabedaten, die durch die Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) , in dem Sie Informationen darüber finden, wie Sie SVG zu PDF mit den ConvertSVG()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu PDF konvertieren

Die Converter‑Klasse bietet mehrere SVG-spezifische Konvertierungen zu PDF. Um SVG zu PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung der Schnittstelle [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekt. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑PDF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-pdf), der SVG mit hoher Qualität, einfach und schnell zu PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Konvertieren Sie die SVG-Quelle, die durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) bereitgestellt wird. Das Ergebnis ist eine Bilddatei, die durch den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | SVGDocument | Konvertierungsquelle, dargestellt durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // SVG‑Dokument als Konvertierungsquelle erstellen
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Konvertierungsprozess mit Standardkonfiguration starten
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine Bilddatei, die durch den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine Bilddatei, die durch den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Konvertieren Sie die SVG-Quelle, die über den vollständigen Dateipfad angegeben wird, in ein Bild. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Konvertieren Sie die SVG-Quelle, die über den vollständigen Dateipfad angegeben wird, in ein Bild. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird, zu einem Bild. Ergebnis ist eine Bilddatei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Inline‑SVG‑Inhalt
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird, zu einem Bild. Ergebnis ist eine Bilddatei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular für Inline‑SVG‑Inhalt
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Konvertieren Sie die SVG‑Quelle, die durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SVGDocument | Konvertierungsquelle, dargestellt durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG‑Dokument als Konvertierungsquelle erstellen
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Konvertierungsprozess starten
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Konvertieren Sie die SVG‑Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, in ein Bild. Das Ergebnis sind Ausgabedaten, die durch eine Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt werden.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Konvertieren Sie die SVG‑Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, in ein Bild. Das Ergebnis sind Ausgabedaten, die durch eine Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt werden.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Konvertieren Sie die SVG‑Quelle, die durch Inline‑Inhalt bereitgestellt wird, in ein Bild. Das Ergebnis sind Ausgabedaten, die durch eine Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt werden.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Konvertieren Sie die SVG‑Quelle, die durch Inline‑Inhalt bereitgestellt wird, in ein Bild. Das Ergebnis sind Ausgabedaten, die durch eine Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt werden.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), in dem Sie Informationen darüber finden, wie Sie SVG mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) nach JPG konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden. Weitere Artikel zu gängigen Bildformaten: [SVG‑zu‑PNG‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [SVG‑zu‑BMP‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [SVG‑zu‑GIF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) und [SVG‑zu‑TIFF‑Konvertierung](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

SVG in Bild konvertieren

Die Klasse Converter bietet mehrere SVG‑spezifische Konvertierungen in Bildformate an, die in gängigen Formaten verfügbar sind. Um SVG in ein Bild zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch ein [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Quelle definieren oder sogar Inline‑SVG‑Inhalt, der als String‑Quelle bereitgestellt wird, verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Beachten Sie, dass das Standard‑Bildformat PNG ist. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertSVG() der Klasse Converter, um SVG mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als Bild zu speichern. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[SVG‑zu‑JPG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-jpg), der SVG mit hoher Qualität, einfach und schnell in JPG konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Weitere beliebte Bildkonverter für verschiedene Formate finden Sie hier: [SVG‑zu‑PNG‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-png), [SVG‑zu‑BMP‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [SVG‑zu‑GIF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-gif) und [SVG‑zu‑TIFF‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Konvertieren Sie die SVG‑Quelle, die durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) bereitgestellt wird. Das Ergebnis ist eine XPS‑Datei, die durch den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | SVGDocument | Konvertierungsquelle, dargestellt durch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // SVG‑Dokument als Konvertierungsquelle erstellen
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Konvertierungsprozess mit Standardkonfiguration starten
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine XPS‑Datei, die durch den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf dem Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Konvertieren Sie die SVG‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine XPS‑Datei, die durch den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | SVG‑Quelldokument [`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Konvertieren Sie die SVG-Quelle, die über den vollständigen Dateipfad angegeben wird, nach XPS. Ergebnis ist eine XPS-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Konvertieren Sie die SVG-Quelle, die über den vollständigen Dateipfad angegeben wird, nach XPS. Ergebnis ist eine XPS-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der SVG‑Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird, zu XPS. Ergebnis ist eine XPS-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular für Inline‑SVG‑Inhalt
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Konvertieren Sie die SVG-Quelle, die als Inline-Inhalt bereitgestellt wird, zu XPS. Ergebnis ist eine XPS-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | String als Inline‑SVG‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des Objekts [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

SVG‑Konverter

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), in dem Sie Informationen darüber finden, wie Sie SVG zu XPS mit den ConvertSVG()-Methoden der Klasse [`Converter`](../) konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

SVG zu XPS konvertieren

Die Converter‑Klasse bietet mehrere SVG‑spezifische Konvertierungen zu XPS. Um SVG zu XPS zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale SVG‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) als Konvertierungsquelle definieren oder sogar Inline‑SVG‑Inhalt verwenden, der als String‑Quelle bereitgestellt wird. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertSVG()-Methode der Converter‑Klasse, um SVG als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑SVG‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[SVG‑zu‑XPS‑Konverter](https://products.aspose.app/svg/en/conversion/svg-to-xps), der SVG mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular für Inline‑SVG‑Inhalt
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
