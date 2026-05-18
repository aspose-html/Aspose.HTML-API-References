---
title: "Converter.ConvertHTML"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Converter-Methode. Konvertiere die von HTMLDocument bereitgestellte HTML-Quelle. Ergebnis ist eine docx-Datei, die durch den Ausgabepfad erstellt wird."
type: docs

url: /de/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

Konvertiere die von [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellte HTML-Quelle. Ergebnis ist eine docx-Datei, die durch den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Instanz als Konvertierungsquelle. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// Formular-Quelldateipfad
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // Standard‑Konfigurationsobjekt instanziieren
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// Ausgabedateipfad festlegen
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// Standard‑DocSaveOptions‑Objekt festlegen
        var options = new DocSaveOptions();
         
		// Konvertierungsprozess mit Standard‑Konfigurationsobjekt starten
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

Konvertiere die per URL bereitgestellte HTML-Quelle. Das Ergebnis ist eine DOCX-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

Konvertiere die per URL bereitgestellte HTML-Quelle. Das Ergebnis ist eine DOCX-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // URL basierend auf Eingabedateipfad erstellen
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess mit Standard‑Konfigurationsobjekt starten
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu DOCX. Das Ergebnis ist eine DOCX-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu DOCX. Das Ergebnis ist eine DOCX-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formular-Quelldateipfad
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formular‑Ergebnisdateipfad
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // Standard‑DocSaveOptions‑Objekt festlegen
   var options = new DocSaveOptions();

   // Konvertierungsprozess mit Standardkonfiguration starten
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird. Ergebnis ist eine docx-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// Standard‑DocSaveOptions‑Objekt festlegen
   	var options = new DocSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird. Ergebnis ist eine docx-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// Standard‑DocSaveOptions‑Objekt festlegen
   	var options = new DocSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

Konvertiere die HTML‑Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Definiere Inline‑HTML‑Inhalt
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// Standard‑Konfigurationsobjekt instanziieren
      	var configuration = new Configuration();

      	// Erstelle ein HTML‑Dokument auf eine von mehreren Arten
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// Definiere den Ergebnisdateipfad ohne Erweiterung
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// Verwende eine Implementierung von ICreateStreamProvider
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// Standard‑DocSaveOptions‑Objekt festlegen
			var options = new DocSaveOptions();

        	// Konvertierungsprozess starten
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

Konvertiere die HTML‑Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // Formular für Quell‑URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Definiere den Ergebnisdateipfad ohne Erweiterung
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine bekannte ICreateStreamProvider‑Implementierung
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

Konvertiere die HTML‑Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // Formular für Quell‑URL
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Definiere den Ergebnisdateipfad ohne Erweiterung
   var resultPath = Path.Combine(OutputFolder, "result");

   // Verwende eine bekannte ICreateStreamProvider‑Implementierung
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Standard‑DocSaveOptions‑Objekt festlegen
   var options = new DocSaveOptions();

   // Konvertierungsprozess mit Standardkonfiguration starten
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

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

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

Konvertiere die HTML‑Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular für Quell‑HTML‑Dateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Definiere den Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende die Standard‑ICreateStreamProvider‑Implementierung
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

Konvertiere die HTML‑Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formular für Quell‑HTML‑Dateipfad
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Definiere den Ergebnisdateipfad
   var resultPath = Path.Combine(OutputFolder, "result");

   // Verwende die Standard‑ICreateStreamProvider‑Implementierung
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Standard‑DocSaveOptions‑Objekt festlegen
   var options = new DocSaveOptions();

   // Konvertierungsprozess mit Standard‑Konfigurationsobjekt starten
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

Konvertiere die HTML‑Quelle, die durch Inline‑Inhalt bereitgestellt wird, zu DOCX. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // Formular für HTML‑Inline‑Inhalt
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // Definiere den Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine bekannte, dateiorientierte ICreateStreamProvider‑Implementierung
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Instanziiere das Standard‑DocSaveOptions‑Objekt
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

Konvertiere die HTML‑Quelle, die durch Inline‑Inhalt bereitgestellt wird, zu DOCX. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objektnutzung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

Wie man HTML in DOCX konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

DOCX-Konvertierung

Eine DOCX‑Datei ist ein Microsoft‑Word‑Dokument, das typischerweise den Text enthält, aber eine breite Palette von Daten umfassen kann, einschließlich Tabellen, Raster‑ und Vektorgrafiken, Video, Sounds und Diagramme. Die DOCX‑Datei ist hochgradig editierbar, einfach zu benutzen und in der Größe handhabbar. Dieses Format ist beliebt wegen der Vielzahl von Optionen, die es Benutzern bietet, um jede Art von Dokumenten zu erstellen. Dieses Dateiformat ist eines der am weitesten verbreiteten und über zahlreiche Programme verfügbar.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in DOCX konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Pfad der Ausgabedatei für das Ergebnis oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können ebenfalls [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertHTML()-Methode der Converter‑Klasse, um HTML als DOCX‑Ergebnis zu speichern, wobei drei oder mehr Parameter je nach Anwendungsszenario erforderlich sind. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑DOCX‑Konverter](https://products.aspose.app/html/en/conversion/html-to-docx), der HTML mit hoher Qualität, einfach und schnell in DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // Formular für HTML‑Inline‑Inhalt
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // Definiere den Ergebnisdateipfad
   var resultPath = Path.Combine(OutputFolder, "result");

   // Verwende eine bekannte, dateiorientierte ICreateStreamProvider‑Implementierung
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Instanziiere das Standard‑DocSaveOptions‑Objekt
   var options = new DocSaveOptions();

   // Konvertierungsprozess mit Standardkonfiguration starten
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





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

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

Konvertiere die HTML‑Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. Das Ergebnis ist eine PDF‑Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Standard‑Konfigurationsobjekt instanziieren
      var configuration = new Configuration();

      // Erstellen Sie ein HTML‑Dokument auf eine von mehreren Arten
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// Formular‑Ergebnisdateipfad
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
        var options = new PdfSaveOptions();

		// Instanziieren Sie den Konvertierungsprozess
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

Konvertiere HTML-Quelle, die über eine URL bereitgestellt wird. Ergebnis ist eine pdf-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // Erstellen Sie eine dateibasierte Quell‑URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertHTML(sourceUrl, options, resultPath);
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

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

Konvertiere HTML-Quelle, die über eine URL bereitgestellt wird. Ergebnis ist eine pdf-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // Erstellen Sie eine dateibasierte Quell‑URL
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formular‑Ergebnisdateipfad
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
   var options = new PdfSaveOptions();

   // Konvertierungsprozess mit Standard‑Konfigurationsobjekt starten
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu PDF. Das Ergebnis ist eine PDF-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Formular-Quelldateipfad
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formular‑Ergebnisdateipfad
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
   var options = new PdfSaveOptions();

   // Konvertierungsprozess starten
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu PDF. Das Ergebnis ist eine PDF-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Formular-Quelldateipfad
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Formular‑Ergebnisdateipfad
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
  var options = new PdfSaveOptions();

  // Konvertierungsprozess mit Standardkonfiguration starten
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu PDF. Ergebnis ist eine pdf-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Definieren Sie das Standard‑PdfSaveOptions‑Objekt
   	var options = new PdfSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu PDF. Ergebnis ist eine pdf-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Definieren Sie das Standard‑PdfSaveOptions‑Objekt
  	var options = new PdfSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

Konvertieren Sie die HTML‑Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird, in PDF. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Definiere Inline‑HTML‑Inhalt
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// Standard‑Konfigurationsobjekt instanziieren
   	var configuration = new Configuration();

   	// Erstelle ein HTML‑Dokument auf eine von mehreren Arten
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// Definiere den Ergebnisdateipfad ohne Erweiterung
		var resultPath = Path.Combine(OutputFolder, "result");

		// Verwende eine Implementierung von ICreateStreamProvider
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// Definieren Sie das Standard‑PdfSaveOptions‑Objekt
		var options = new PdfSaveOptions();

		// Konvertierungsprozess starten
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

Konvertiere die HTML‑Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // URL basierend auf Eingabedateipfad erstellen
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formular‑Ergebnisdateipfad
   var resultPath = Path.Combine(OutputFolder, "result");

   // Verwende eine Implementierung von ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
   var options = new PdfSaveOptions();

   // Konvertierungsprozess starten
   Converter.ConvertHTML(sourceUrl, options, provider);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

Konvertiere die HTML‑Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // URL basierend auf Eingabedateipfad erstellen
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Formular‑Ergebnisdateipfad
   var resultPath = Path.Combine(OutputFolder, "result ");

   // Verwende eine Implementierung von ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
   var options = new PdfSaveOptions();

   // Konvertierungsprozess mit Standardkonfiguration starten
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

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

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

Konvertieren Sie die HTML‑Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, in PDF. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Erstellen Sie den Quell‑Dateipfad
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Formular‑Ergebnisdateipfad
   var resultPath = Path.Combine(OutputFolder, "result");

   // Verwende eine Implementierung von ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
   var options = new PdfSaveOptions();

   // Konvertierungsprozess starten
   Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

Konvertieren Sie die HTML‑Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, in PDF. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Erstellen Sie den Quell‑Dateipfad
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Formular‑Ergebnisdateipfad
  var resultPath = Path.Combine(OutputFolder, "result");

  // Verwende eine Implementierung von ICreateStreamProvider
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
  var options = new PdfSaveOptions();

  // Konvertierungsprozess mit Standardkonfiguration starten
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

Konvertieren Sie die HTML‑Quelle, die durch Inline‑Inhalt bereitgestellt wird, in PDF. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Verwende eine Implementierung von ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definieren Sie das Standard‑PdfSaveOptions‑Objekt
  	var options = new PdfSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

Konvertieren Sie die HTML‑Quelle, die durch Inline‑Inhalt bereitgestellt wird, in PDF. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in PDF konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

PDF-Konvertierung

Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Der Zweck dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Eine PDF‑Datei ist eine Menge von Bytes, die gemäß den Syntaxregeln, die in den PDF‑Spezifikationen definiert sind, zu Tokens gruppiert werden können. Sobald ein oder mehrere Tokens zu höherstufigen syntaktischen Entitäten, hauptsächlich Objekten, kombiniert werden, bilden diese die grundlegenden Datenwerte, aus denen ein PDF‑Dokument aufgebaut ist.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Weitere beliebte Formatkonvertierungen

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in PDF konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf), der HTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Verwende eine Implementierung von ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definieren Sie das Standard‑PdfSaveOptions‑Objekt
 	var options = new PdfSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
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

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

Konvertieren Sie die HTML‑Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. Das Ergebnis ist eine mhtml‑(.mht)‑Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Vollständiger mhtml‑(.mht)‑Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in MHTML konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

MHTML-Konvertierung

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in MHTML konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als MHTML‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml), der HTML mit hoher Qualität, einfach und schnell in MHTML konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Erstellen Sie ein HTML‑Dokument
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Erstelle ein HTML‑Dokument auf eine von mehreren Arten
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// Definieren Sie das Standard-MHTMLSaveOptions-Objekt
 		var options = new MHTMLSaveOptions();

		// Formular‑Ergebnisdateipfad
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// Konvertierungsprozess starten
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

Konvertiere die per URL bereitgestellte HTML-Quelle. Das Ergebnis ist eine MHTML‑Datei (.mht), die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Vollständiger mhtml‑(.mht)‑Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in MHTML konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

MHTML-Konvertierung

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in MHTML konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als MHTML‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml), der HTML mit hoher Qualität, einfach und schnell in MHTML konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Definieren Sie das Standard-MHTMLSaveOptions-Objekt
	var options = new MHTMLSaveOptions();

	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

Konvertiere die per URL bereitgestellte HTML-Quelle. Das Ergebnis ist eine MHTML‑Datei (.mht), die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Vollständiger mhtml‑(.mht)‑Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in MHTML konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

MHTML-Konvertierung

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in MHTML konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als MHTML‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml), der HTML mit hoher Qualität, einfach und schnell in MHTML konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Definieren Sie das Standard-MHTMLSaveOptions-Objekt
	var options = new MHTMLSaveOptions();

	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu MHTML. Das Ergebnis ist eine MHTML‑Datei (.mht), die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Vollständiger mhtml‑(.mht)‑Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in MHTML konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

MHTML-Konvertierung

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in MHTML konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als MHTML‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml), der HTML mit hoher Qualität, einfach und schnell in MHTML konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Definieren Sie das Standard-MHTMLSaveOptions-Objekt
	var options = new MHTMLSaveOptions();

	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu MHTML. Das Ergebnis ist eine MHTML‑Datei (.mht), die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Vollständiger mhtml‑(.mht)‑Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in MHTML konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

MHTML-Konvertierung

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in MHTML konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als MHTML‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml), der HTML mit hoher Qualität, einfach und schnell in MHTML konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Definieren Sie das Standard-MHTMLSaveOptions-Objekt
	var options = new MHTMLSaveOptions();

	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu MHTML. Ergebnis ist eine mhtml (.mht)-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Vollständiger mhtml‑(.mht)‑Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in MHTML konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

MHTML-Konvertierung

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in MHTML konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als MHTML‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml), der HTML mit hoher Qualität, einfach und schnell in MHTML konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
  	var options = new MHTMLSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu MHTML. Ergebnis ist eine mhtml (.mht)-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Vollständiger mhtml‑(.mht)‑Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

Wie man HTML in MHTML konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

MHTML-Konvertierung

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML in MHTML konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als MHTML‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml), der HTML mit hoher Qualität, einfach und schnell in MHTML konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
 	var options = new MHTMLSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

Konvertieren Sie die HTML‑Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. Das Ergebnis ist eine Markdown‑(.md)‑Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Vollständiger md-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu Markdown konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Markdown‑Konvertierung

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu Markdown konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Markdown‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑Markdown](https://products.aspose.app/html/en/conversion/html-to-md) Dienst, der HTML mit hoher Qualität, einfach und schnell in MD konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Formular-Quelldateipfad
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// Formular‑Ergebnisdateipfad
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// Definieren Sie eine Instanz des Speicheroptions‑Objekts
			var options = new MarkdownSaveOptions();

			// Konvertierungsprozess starten
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

Konvertiere die per URL bereitgestellte HTML-Quelle. Das Ergebnis ist eine Markdown‑Datei (.md), die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Vollständiger md-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu Markdown konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Markdown‑Konvertierung

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu Markdown konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Markdown‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑Markdown](https://products.aspose.app/html/en/conversion/html-to-md) Dienst, der HTML mit hoher Qualität, einfach und schnell in MD konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// Formular‑Ergebnisdateipfad
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new MarkdownSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

Konvertiere die per URL bereitgestellte HTML-Quelle. Das Ergebnis ist eine Markdown‑Datei (.md), die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Vollständiger md-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu Markdown konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Markdown‑Konvertierung

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu Markdown konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Markdown‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑Markdown](https://products.aspose.app/html/en/conversion/html-to-md) Dienst, der HTML mit hoher Qualität, einfach und schnell in MD konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// Formular‑Ergebnisdateipfad
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new MarkdownSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu Markdown. Das Ergebnis ist eine Markdown‑Datei (.md), die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Vollständiger md-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu Markdown konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Markdown‑Konvertierung

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu Markdown konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Markdown‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑Markdown](https://products.aspose.app/html/en/conversion/html-to-md) Dienst, der HTML mit hoher Qualität, einfach und schnell in MD konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// Formular‑Ergebnisdateipfad
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new MarkdownSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu Markdown. Das Ergebnis ist eine Markdown‑Datei (.md), die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Vollständiger md-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu Markdown konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Markdown‑Konvertierung

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu Markdown konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Markdown‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑Markdown](https://products.aspose.app/html/en/conversion/html-to-md) Dienst, der HTML mit hoher Qualität, einfach und schnell in MD konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// Formular‑Ergebnisdateipfad
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new MarkdownSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu Markdown. Ergebnis ist eine mhtml (.mht)-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Vollständiger md-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu Markdown konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Markdown‑Konvertierung

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu Markdown konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Markdown‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑Markdown](https://products.aspose.app/html/en/conversion/html-to-md) Dienst, der HTML mit hoher Qualität, einfach und schnell in MD konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
  	var options = new MarkdownSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu Markdown. Ergebnis ist eine mhtml (.mht)-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Vollständiger md-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu Markdown konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Markdown‑Konvertierung

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Weitere beliebte Formatkonvertierungen

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu Markdown konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Markdown‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑Markdown](https://products.aspose.app/html/en/conversion/html-to-md) Dienst, der HTML mit hoher Qualität, einfach und schnell in MD konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
 	var options = new MarkdownSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

Konvertieren Sie die HTML‑Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. Das Ergebnis ist eine XPS‑Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Formular-Quelldateipfad
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// Formular‑Ergebnisdateipfad
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// Erstelle ein HTML‑Dokument auf eine von mehreren Arten
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
        	var options = new XpsSaveOptions();

        	// Konvertierungsprozess starten
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

Konvertiere HTML-Quelle, die über eine URL bereitgestellt wird. Ergebnis ist eine xps-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formular‑Ergebnisdateipfad
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new XpsSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourceUrl, options, outputPath);
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

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

Konvertiere HTML-Quelle, die über eine URL bereitgestellt wird. Ergebnis ist eine xps-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formular‑Ergebnisdateipfad
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new XpsSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu XPS. Das Ergebnis ist eine XPS-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formular‑Ergebnisdateipfad
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new XpsSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu XPS. Das Ergebnis ist eine XPS-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formular‑Ergebnisdateipfad
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new XpsSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
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

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu XPS. Ergebnis ist eine xps-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
  	var options = new XpsSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu XPS. Ergebnis ist eine xps-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
 	var options = new XpsSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

Konvertiere die HTML‑Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formular‑Ergebnisdateipfad
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// Erstelle ein HTML‑Dokument auf eine von mehreren Arten
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
    	var options = new XpsSaveOptions();

		// Verwenden Sie eine bekannte ICreateStreamProvider‑Implementierung
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// Konvertierungsprozess starten
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

Konvertiere die HTML‑Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quelldokument‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formular‑Ergebnisdateipfad
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Verwende eine Implementierung von ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new XpsSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

Konvertiere die HTML‑Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quell‑URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formular‑Ergebnisdateipfad
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Verwende eine Implementierung von ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new XpsSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
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

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

Konvertieren Sie die HTML‑Quelle, die über den vollständigen Dateipfad bereitgestellt wird, zu XPS. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erstellt werden.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formular‑Ergebnisdateipfad
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Verwende eine Implementierung von ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new XpsSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

Konvertieren Sie die HTML‑Quelle, die über den vollständigen Dateipfad bereitgestellt wird, zu XPS. Das Ergebnis sind Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erstellt werden.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formular‑Ergebnisdateipfad
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Verwende eine Implementierung von ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new XpsSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

HTML-Quelle, die durch Inline-Inhalt bereitgestellt wird, in XPS konvertieren. Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces erzeugt werden.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑XPS](https://products.aspose.app/html/en/conversion/html-to-xps)‑Konverter, der HTML mit hoher Qualität, einfach und schnell in XPS umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Verwende eine Implementierung von ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
  	var options = new XpsSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

HTML-Quelle, die durch Inline-Inhalt bereitgestellt wird, in XPS konvertieren. Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces erzeugt werden.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung. |

## Hinweise

Wie man HTML zu XPS konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

XPS‑Konvertierung

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML zu XPS konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) Objekt mit benutzerdefinierten oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als XPS‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[HTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/html-to-xps), der HTML mit hoher Qualität, einfach und schnell in XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Versuchen Sie, andere beliebte Formatkonvertierungen zu verwenden

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Verwende eine Implementierung von ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
 	var options = new XpsSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
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

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

HTML-Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird, konvertieren. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// Formular-Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "source.html");

// Formular‑Ergebnisdateipfad
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Konvertierungsprozess starten
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

Konvertiere die per URL bereitgestellte HTML-Quelle. Das Ergebnis ist eine Bilddatei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quell‑URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formular‑Ergebnisdateipfad
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourceUrl, options, resultPath);
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

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

Konvertiere die per URL bereitgestellte HTML-Quelle. Das Ergebnis ist eine Bilddatei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quell‑URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formular‑Ergebnisdateipfad
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu einem Bild. Das Ergebnis ist eine Bilddatei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | ImageSaveOptions | Um mehr über die Klasse [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) zu erfahren, lesen Sie bitte den Artikel [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Formular‑Ergebnisdateipfad
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts. PNG ist standardmäßig das Bildformat.
	var options = new ImageSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

Konvertiere die über einen vollständigen Dateipfad bereitgestellte HTML-Quelle zu einem Bild. Das Ergebnis ist eine Bilddatei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Um mehr über die Klasse [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) zu erfahren, lesen Sie bitte den Artikel [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formular‑Ergebnisdateipfad
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts. PNG ist standardmäßig das Bildformat.
	var options = new ImageSaveOptions();

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu einem Bild. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | ImageSaveOptions | Neu erstellte Bildoptionen wie Format, Auflösung usw. Siehe die Klasse [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und die [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

Konvertiere HTML-Quelle, die als Inline-Inhalt bereitgestellt wird, zu einem Bild. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Neu erstellte Bildoptionen wie Format, Auflösung usw. Siehe die Klasse [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und die [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

Konvertiere die HTML‑Quelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | HTMLDocument | Konvertierungsquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result");

	// Erstelle ein HTML‑Dokument auf eine von mehreren Arten
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// Definieren Sie eine Instanz des Speicheroptions‑Objekts
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// Verwende eine Implementierung von ICreateStreamProvider
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// Konvertierungsprozess starten
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

Konvertiere die HTML‑Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quell‑URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | ImageSaveOptions | Die Verwendung des Objekts ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Formular‑Ergebnisdateipfad
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Verwende eine Implementierung von ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

Konvertiere die HTML‑Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces erzeugt werden.

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | HTML‑Quell‑URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Weitere Informationen zu Anbietern finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// URL basierend auf Eingabedateipfad erstellen
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Formular‑Ergebnisdateipfad
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Verwende eine Implementierung von ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
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

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

HTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, in ein Bild konvertieren. Ergebnis sind Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces erzeugt werden.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML‑vollständiger Quelldateipfad. |
| options | ImageSaveOptions | Die Verwendung des Objekts ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Weitere Informationen zu Anbietern finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Formular‑Ergebnisdateipfad
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Verwenden Sie eine bekannte ICreateStreamProvider‑Implementierung
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Konvertierungsprozess starten
	Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

HTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, in ein Bild konvertieren. Ergebnis sind Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces erzeugt werden.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Weitere Informationen zu Anbietern finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// Formular‑Ergebnisdateipfad
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Definieren Sie eine Instanz des Speicheroptions‑Objekts
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Verwenden Sie eine bekannte ICreateStreamProvider‑Implementierung
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

HTML-Quelle, die durch Inline-Inhalt bereitgestellt wird, in ein Bild konvertieren. Ergebnis sind Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces erzeugt werden.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | ImageSaveOptions | Die Verwendung des Objekts ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung. |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Verwenden Sie eine bekannte ICreateStreamProvider‑Implementierung
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Konvertierungsprozess starten
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

HTML-Quelle, die durch Inline-Inhalt bereitgestellt wird, in ein Bild konvertieren. Ergebnis sind Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces erzeugt werden.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zeichenkette als Inline‑HTML‑Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungskonfiguration. Stellt das [`configuration `](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), das zum Abrufen eines Ausgabestreams verwendet wird. Weitere Informationen zu Anbietern finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Hinweise

Wie man HTML in ein Bild konvertiert

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um die Vorteile verschiedener Formate für bestimmte Aufgaben zu nutzen. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von HTML-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), und [MD](https://docs.fileformat.com/word-processing/md/).

Dieser Artikel gibt Informationen zur Liste der unterstützten HTML-Konvertierungen und wie man sie mithilfe der [`Converter`](../)-Klasse ausführt, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu benutzen. Im HTML‑Converter‑Leitfaden finden Sie die folgenden Artikel:

Bildkonvertierungen

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Weitere beliebte Formatkonvertierungen

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTML in ein Bild konvertieren

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale HTML‑Datei oder eine entfernte URL als Konvertierungsquelle. Sie können sogar Inline‑HTML‑Inhalt als Konvertierungsquelle definieren oder ein HTML‑Dokument (HTMLDocument) auf beliebige Weise erstellen. Konvertergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues Objekt [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) mit dem erforderlichen [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/). Standardmäßig ist die Format‑Eigenschaft PNG. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertHTML() der Klasse Converter, um HTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online‑HTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[HTML‑zu‑PNG‑Konverter](https://products.aspose.app/html/en/conversion/html-to-png), der HTML mit hoher Qualität, einfach und schnell in Bilder umwandelt. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer spezifischen Bildformatkonvertierung interessiert

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular für Inline‑HTML‑Inhalt		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Definieren Sie das Standard‑Speicheroptions‑Objekt
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Verwenden Sie eine bekannte ICreateStreamProvider‑Implementierung
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Konvertierungsprozess mit Standardkonfiguration starten
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
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

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

Konvertiere das HTML-Dokument in Text. Das Ergebnis ist eine TXT-Datei.

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | HTMLDocument | Konvertierungsquelle. |
| Optionen | TextSaveOptions | Konvertierungsoptionen. |
| outputPath | String | Ausgabedateipfad. |

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

Konvertiere das HTML-Dokument in Text. Das Ergebnis ist eine TXT-Datei.

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Die Dokument-URL. |
| Optionen | TextSaveOptions | Konvertierungsoptionen. |
| outputPath | String | Ausgabedateipfad. |

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

Konvertiere das HTML-Dokument in Text. Das Ergebnis ist eine TXT-Datei.

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Die Dokument-URL. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration. |
| Optionen | TextSaveOptions | Konvertierungsoptionen. |
| outputPath | String | Ausgabedateipfad. |

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

Konvertiere das HTML-Dokument in Text. Das Ergebnis ist eine TXT-Datei.

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| Optionen | TextSaveOptions | Konvertierungsoptionen. |
| outputPath | String | Ausgabedateipfad. |

### Siehe auch

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

Konvertiere das HTML-Dokument in Text. Das Ergebnis ist eine TXT-Datei.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | HTML-Dateiquellpfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration. |
| Optionen | TextSaveOptions | Konvertierungsoptionen. |
| outputPath | String | Ausgabedateipfad. |

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

Konvertiere das HTML-Dokument in Text. Das Ergebnis ist eine TXT-Datei.

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Inline-String-HTML-Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| Optionen | TextSaveOptions | Konvertierungsoptionen. |
| outputPath | String | Ausgabedateipfad. |

### Siehe auch

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

Konvertiere das HTML-Dokument in Text. Das Ergebnis ist eine TXT-Datei.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Inline-String-HTML-Inhalt. |
| baseUri | String | Die Basis‑URI des Dokuments. Sie wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| Konfiguration | Konfiguration | Die Umgebungskonfiguration. |
| Optionen | TextSaveOptions | Konvertierungsoptionen. |
| outputPath | String | Ausgabedateipfad. |

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
