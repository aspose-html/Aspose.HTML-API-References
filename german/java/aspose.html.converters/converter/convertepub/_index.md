---
title: "Converter.ConvertEPUB"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Converter‑Methode. Konvertieren Sie die EPUB‑Quelle, die durch einen Eingabestream bereitgestellt wird. Das Ergebnis ist eine Datei, die über den Ausgabepfad erstellt wird."
type: docs

url: /de/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Konvertieren Sie die EPUB-Quelle, bereitgestellt durch einen Dateneingabestream. Das Ergebnis ist eine Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| options | ImageSaveOptions | Neue Bildoptionen wie Format, Auflösung usw. Siehe die Klasse [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) und die [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Definieren Sie die URL basierend auf der vorhandenen EPUB-Datei am angegebenen Pfad. Definieren Sie den Ausgabedateipfad. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen außerdem ImageSaveOptions und das Configuration‑Objekt an die Bildkonvertierung übergeben. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Öffnen Sie die vorhandene Datei zum Lesen als Stream
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Ausgabedateipfad definieren
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definieren Sie die Standardoptionen‑Instanz
var options = new ImageSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Konvertieren Sie die EPUB-Quelle, die durch einen vollständigen Dateipfad bereitgestellt wird. Ergebnis ist eine Bilddatei, die durch den Ausgabedateipfad erzeugt wird. Das Bildformat wird durch das Objekt ImageSaveOptions angegeben.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad als Eingabeparameter. |
| options | ImageSaveOptions | Die Verwendung von ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/) und den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Definieren Sie die URL basierend auf der vorhandenen EPUB-Datei am angegebenen Pfad. Definieren Sie den Ausgabedateipfad. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen außerdem ImageSaveOptions und das Configuration‑Objekt an die Bildkonvertierung übergeben. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definieren Sie die Standard‑ImageSaveOptions‑Objektinstanz
var options = new ImageSaveOptions(); 

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Konvertieren Sie die EPUB-Quelle, die durch eine URL definiert ist. Ergebnis ist eine Bilddatei, die durch den Ausgabedateipfad erzeugt wird. Das Bildformat wird durch das Objekt ImageSaveOptions angegeben.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | ImageSaveOptions | Die Verwendung des ImageSaveOptions‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe die Klasse [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Definieren Sie die URL basierend auf der vorhandenen EPUB-Datei am angegebenen Pfad. Definieren Sie den Ausgabedateipfad. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen außerdem ImageSaveOptions und das Configuration‑Objekt an die Bildkonvertierung übergeben. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Url basierend auf Eingabedateipfad erstellen
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definieren Sie die Standardoptionen‑Instanz
var options = new ImageSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Konvertieren Sie die EPUB-Quelle, die durch einen Dateneingabestream bereitgestellt wird. Ergebnis ist eine Bilddatei, die durch den Ausgabedateipfad erzeugt wird. Das Bildformat wird durch das Objekt ImageSaveOptions angegeben.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung von ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/) und den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Definieren Sie die URL basierend auf der vorhandenen EPUB-Datei am angegebenen Pfad. Definieren Sie den Ausgabedateipfad. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen außerdem ImageSaveOptions und das Configuration‑Objekt an die Bildkonvertierung übergeben. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Öffnen Sie die vorhandene Datei zum Lesen als Stream
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Ausgabedateipfad definieren
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Definieren Sie die Standardoptionen‑Instanz
var options = new ImageSaveOptions();

// Konvertierungsprozess mit dem Standard‑Konfigurationsobjekt starten
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Konvertieren Sie die EPUB-Quelle, die durch einen vollständigen Dateipfad bereitgestellt wird. Ergebnis ist eine Bilddatei, die durch den Ausgabedateipfad erzeugt wird. Das Bildformat wird durch das Objekt ImageSaveOptions angegeben.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad als Eingabeparameter. |
| configuration | Configuration | Die Umgebungskonfiguration. Stellt das [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) Kontextobjekt dar, das verwendet wird, um die Umgebungs‑einstellungen für die Anwendung einzurichten. |
| options | ImageSaveOptions | Die Verwendung des ImageSaveOptions‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe die Klasse [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Definieren Sie die URL basierend auf der vorhandenen EPUB-Datei am angegebenen Pfad. Definieren Sie den Ausgabedateipfad. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen außerdem ImageSaveOptions und das Configuration‑Objekt an die Bildkonvertierung übergeben. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Definieren Sie die Standard‑ImageSaveOptions‑Objektinstanz
var options = new ImageSaveOptions(); 

// Konvertierungsprozess mit dem Standard‑Konfigurationsobjekt starten
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Konvertieren Sie die EPUB-Quelle, die durch eine URL definiert ist. Ergebnis ist eine Bilddatei, die durch den Ausgabedateipfad erzeugt wird. Das Bildformat wird durch das Objekt ImageSaveOptions angegeben.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des ImageSaveOptions‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin) und [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype) festlegen usw. Siehe die Klasse [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions). |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Definieren Sie die URL basierend auf der vorhandenen EPUB-Datei am angegebenen Pfad. Definieren Sie den Ausgabedateipfad. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen außerdem ImageSaveOptions und das Configuration‑Objekt an die Bildkonvertierung übergeben. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Url basierend auf Eingabedateipfad erstellen
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Ausgabedateipfad definieren
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Definieren Sie die Standardoptionen‑Instanz
var options = new ImageSaveOptions(); 

// Konvertierungsprozess mit dem Standard‑Konfigurationsobjekt starten
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Epub‑Quelle, die durch einen Eingabe‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) bereitgestellt wird, in ein Bild konvertieren. Das Ergebnis ist eine Bilddatei, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces entsteht.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| options | ImageSaveOptions | Die Verwendung des ImageSaveOptions‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe die Klasse [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Im Beispiel verwenden wir die Methode OpenRead() der Klasse System.IO.FileStream, um eine EPUB‑Datei aus dem Dateisystem am angegebenen Pfad zu öffnen und zu lesen. Verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)‑Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen den EPUB‑inputStream, ImageSaveOptions und den Ausgabestream an die ConvertEPUB()-Methode übergeben, um EPUB in ein Bild zu konvertieren. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new ImageSaveOptions();    

// Starten Sie den Konvertierungsprozess  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Konvertieren Sie die EPUB‑Quelle, die durch einen Dateipfad angegeben wird, in ein Bild. Das Ergebnis ist eine Bilddatei, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces entsteht.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | ImageSaveOptions | Neue Bildoptionen wie Format, Auflösung usw. Siehe die Klasse [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) und die [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Weitere Informationen zu den Anbietern finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Im Beispiel verwenden wir die Methode OpenRead() der Klasse System.IO.FileStream, um eine EPUB‑Datei aus dem Dateisystem am angegebenen Pfad zu öffnen und zu lesen. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider‑Interface‑Implementierung als Ausgabedatenpuffer. Erstellen Sie ein neues ImageSaveOptions‑Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen den EPUB‑inputStream, ImageSaveOptions und den Ausgabestream an die ConvertEPUB()-Methode übergeben, um EPUB in ein Bild zu konvertieren. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

EPUB zu JPG mit zwei Codezeilen

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Öffnen Sie eine vorhandene EPUB‑Datei zum Lesen.
import var stream = File.OpenRead(DataDir + "input.epub");

// Rufen Sie die ConvertEPUB-Methode auf, um den EPUB-Code in ein JPG-Bild zu konvertieren      
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Konvertieren Sie die EPUB-Quelle, die per URL bereitgestellt wird, in ein Bild. Das Ergebnis ist eine Bilddatei, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces entsteht.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | ImageSaveOptions | Die Verwendung des ImageSaveOptions‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe die Klasse [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Weitere Informationen zu den Anbietern finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Im Beispiel verwenden wir die Methode OpenRead() der Klasse System.IO.FileStream, um eine EPUB‑Datei aus dem Dateisystem am angegebenen Pfad zu öffnen und zu lesen. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider‑Interface‑Implementierung als Ausgabedatenpuffer. Erstellen Sie ein neues ImageSaveOptions‑Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen den EPUB‑inputStream, ImageSaveOptions und den Ausgabestream an die ConvertEPUB()-Methode übergeben, um EPUB in ein Bild zu konvertieren. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  

// Url basierend auf Eingabedateipfad erstellen
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new ImageSaveOptions();

// Starten Sie den Konvertierungsprozess  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Epub‑Quelle, die durch einen Eingabe‑[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) bereitgestellt wird, in ein Bild konvertieren. Das Ergebnis ist eine Bilddatei, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interfaces entsteht.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung von ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/) und den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| Anbieter | ICreateStreamProvider | Implementierung des Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Im Beispiel verwenden wir die Methode OpenRead() der Klasse System.IO.FileStream, um eine EPUB‑Datei aus dem Dateisystem am angegebenen Pfad zu öffnen und zu lesen. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider‑Interface‑Implementierung als Ausgabedatenpuffer. Erstellen Sie ein neues ImageSaveOptions‑Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen den EPUB‑inputStream, ImageSaveOptions und den Ausgabestream an die ConvertEPUB()-Methode übergeben, um EPUB in ein Bild zu konvertieren. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Erstellen Sie die Standardoptionen‑Instanz  
var options = new ImageSaveOptions();    


// Starten Sie den Konvertierungsprozess mit der Standardkonfiguration  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Konvertieren Sie die EPUB-Quelle, die über einen Dateipfad bereitgestellt wird, in ein Bild. Das Ergebnis ist eine Bilddatei, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces entsteht.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB-Quelle, definiert durch einen Dateipfad. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung von ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/) und den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Siehe das ICreateStreamProvider-Implementierungsbeispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Im Beispiel verwenden wir die Methode OpenRead() der Klasse System.IO.FileStream, um eine EPUB‑Datei aus dem Dateisystem am angegebenen Pfad zu öffnen und zu lesen. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider‑Interface‑Implementierung als Ausgabedatenpuffer. Erstellen Sie ein neues ImageSaveOptions‑Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen den EPUB‑inputStream, ImageSaveOptions und den Ausgabestream an die ConvertEPUB()-Methode übergeben, um EPUB in ein Bild zu konvertieren. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Definieren Sie die Standard‑ImageSaveOptions‑Objektinstanz
var options = new ImageSaveOptions(); 

// Konvertierungsprozess mit dem Standard‑Konfigurationsobjekt starten
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Konvertiere die EPUB-Quelle, die über eine URL bereitgestellt wird, in ein Bild. Das Ergebnis ist eine Bilddatei, die durch die Implementierung des [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider)-Interfaces entsteht.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung von ImageSaveOptions ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/) und den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Siehe das ICreateStreamProvider-Implementierungsbeispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Hinweise

Wie man EPUB in ein Bild konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Veröffentlichungsformat bereitstellt. Es wurde vom International Digital Publishing Forum (IDPF) erstellt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt.

Die Konvertierung von EPUB‑Dateien in das PNG‑Format kann hilfreich sein, wenn Sie Dateien in eine PowerPoint‑Präsentation einbinden oder per E‑Mail versenden müssen. Konvertieren Sie sie bitte in das Bildformat und verwenden Sie sie nach Bedarf! Sie können zusätzliche Konvertierungsparameter verwenden, um das gewünschte Ergebnis zu erzielen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe einer Converter‑Klasse, die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im EPUB‑Converter‑Leitfaden finden Sie die folgenden Artikel:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB in Bild konvertieren

Um EPUB in ein Bilddateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Im Beispiel verwenden wir die Methode OpenRead() der Klasse System.IO.FileStream, um eine EPUB‑Datei aus dem Dateisystem am angegebenen Pfad zu öffnen und zu lesen. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider‑Interface‑Implementierung als Ausgabedatenpuffer. Erstellen Sie ein neues ImageSaveOptions‑Objekt mit dem erforderlichen ImageFormat. Standardmäßig ist die Format‑Eigenschaft PNG. Verwenden Sie die Methode ConvertEPUB() der Klasse Converter, um EPUB als Bild zu speichern. Sie müssen den EPUB‑inputStream, ImageSaveOptions und den Ausgabestream an die ConvertEPUB()-Methode übergeben, um EPUB in ein Bild zu konvertieren. Online EPUB‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑zu‑PNG](https://products.aspose.app/html/en/conversion/epub-to-png)‑Konverter, der EPUB in ein PNG‑Bild mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Vielleicht sind Sie auch an einer speziellen Bildformatkonvertierung interessiert

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Erstellen Sie die Quell-URL anhand des Eingabedateipfads
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new ImageSaveOptions();

// Konvertierungsprozess mit der Standard‑Konfiguration starten
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Konvertieren Sie die epub-Quelle, die durch einen Eingabestream bereitgestellt wird, zu xps. Ergebnis ist eine xps-Datei, die durch den vollständigen Pfad definiert ist.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabestream als Konvertierungsquelle. Siehe die Stream-Spezifikation in der [offiziellen Quelle](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Konvertierungsoptionen. Die Verwendung des [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objekts ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die Seitengröße, Ränder, CSS usw. festlegen. |
| outputPath | String | Vollständiger .xps-Dateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Zum Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider-Interfaces als Ausgabedatenpuffer. Als einfachere Alternative können wir den Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Rändern, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen die EPUB-Quelldaten, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Online EPUB‑zu‑XPS‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Öffnen Sie eine vorhandene EPUB-Datei zum Lesen
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Bereiten Sie einen Pfad vor, um die konvertierte Datei zu speichern 
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Erstellen Sie eine Instanz von XpsSaveOptions. Legen Sie die Seitengröße fest und ändern Sie die Hintergrundfarbe zu LightGray 
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // Rufen Sie die ConvertEPUB-Methode auf, um EPUB nach XPS zu konvertieren
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Konvertieren Sie die epub-Quelle, die durch einen Eingabe-EPUB-Dateipfad bereitgestellt wird, zu xps. Ergebnis ist eine xps-Datei, die durch den vollständigen Pfad definiert ist.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | XpsSaveOptions | Konvertierungsoptionen. Die Verwendung des [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objekts ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger .xps-Dateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Zum Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider-Interfaces als Ausgabedatenpuffer. Als einfachere Alternative können wir den Ergebnis-Ausgabedateipfad nutzen. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Rändern, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen die EPUB-Quelldaten, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Online EPUB‑zu‑XPS‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Konvertierungsprozess mit der Standard‑Konfiguration starten
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Konvertieren Sie die epub-Quelle, die durch eine URL bereitgestellt wird, zu einer xps-Datei, die durch den vollständigen Pfad definiert ist. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | XpsSaveOptions | Konvertierungsoptionen. Die Verwendung des [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objekts ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger .xps-Dateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider-Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten.

Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Erstellen Sie die Quell-URL anhand des Eingabedateipfads
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Konvertieren Sie die epub-Quelle, die durch einen Eingabe-[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) bereitgestellt wird, zu xps. Ergebnis ist eine xps-Datei, die durch den vollständigen Pfad definiert ist.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Konvertierungsoptionen. Die Verwendung des [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objekts ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger .xps-Dateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider-Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Öffnen Sie eine vorhandene EPUB-Datei zum Lesen
import var stream = File.OpenRead(DataDir + "input.epub");

// Bereiten Sie einen Pfad für das Speichern der konvertierten Datei vor
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Initialisieren Sie XpsSaveOptions
var options = new XpsSaveOptions();
   
// Rufen Sie die ConvertEPUB-Methode auf, um EPUB nach XPS zu konvertieren
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Konvertieren Sie die epub-Quelle, die durch einen Eingabe-EPUB-Dateipfad bereitgestellt wird, zu xps. Ergebnis ist eine xps-Datei, die durch den vollständigen Pfad definiert ist.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungskonfiguration. Stellt das [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) Kontextobjekt dar, das verwendet wird, um die Umgebungs‑einstellungen für die Anwendung einzurichten. |
| options | XpsSaveOptions | Konvertierungsoptionen. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) Objektverwendung ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die Seitengröße, Ränder, CSS usw. festlegen. |
| outputPath | String | Vollständiger .xps-Dateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider-Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Konvertierungsprozess mit der Standard‑Konfiguration starten
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Konvertieren Sie die epub-Quelle, die durch eine URL bereitgestellt wird, zu einer xps-Datei, die durch den vollständigen Pfad definiert ist. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungskonfiguration. Stellt das [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) Kontextobjekt dar, das verwendet wird, um die Umgebungs‑einstellungen für die Anwendung einzurichten. |
| options | XpsSaveOptions | Konvertierungsoptionen. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) Objektverwendung ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die Seitengröße, Ränder, CSS usw. festlegen. |
| outputPath | String | Vollständiger .xps-Dateipfad als Ergebnis der Konvertierung. |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider-Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Erstellen Sie die Quell-URL anhand des Eingabedateipfads
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Starten Sie den Konvertierungsprozess mit der Standardkonfiguration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Konvertieren Sie die EPUB-Quelle, die durch den Eingabe-[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) bereitgestellt wird, zu XPS. Das Ergebnis ist XPS-Ausgabedaten, definiert durch eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interface-Implementierung.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| options | XpsSaveOptions | Konvertierungsoptionen. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe das ICreateStreamProvider-Implementierungsbeispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider-Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Erstellen Sie eine Instanz von MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Öffnen Sie eine vorhandene EPUB-Datei zum Lesen
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Bereiten Sie einen Pfad vor, um die konvertierte Datei zu speichern 
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Konvertieren Sie EPUB zu XPS mithilfe der MemoryStreamProvider-Klasse
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Greifen Sie auf den Memory-Stream zu, der die Ergebnisdaten enthält
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Schreiben Sie die Ergebnisdaten in die Ausgabedatei
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Konvertieren Sie die EPUB-Quelle, die durch den Eingabe-EPUB-Dateipfad bereitgestellt wird, zu XPS. Das Ergebnis sind XPS-Ausgabedaten, definiert durch eine bekannte oder benutzerdefinierte [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/) Interface-Implementierung.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | XpsSaveOptions | Konvertierungsoptionen. [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) Objektverwendung ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die Seitengröße, Ränder, CSS usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Zum Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider-Interfaces als Ausgabedatenpuffer. Als einfachere Alternative können wir den Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Rändern, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen die EPUB-Quelldaten, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Online EPUB‑zu‑XPS‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Konvertierungsprozess mit der Standard‑Konfiguration starten
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Konvertieren Sie die EPUB-Quelle, die über eine URL bereitgestellt wird, zu einer XPS-Datei, die durch den vollständigen Pfad definiert ist. Das Ergebnis sind XPS-Ausgabedaten, definiert durch eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interface-Implementierung.

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | XpsSaveOptions | Konvertierungsoptionen. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die Seitengröße, Ränder, CSS usw. festlegen. Siehe die [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Erstellen Sie die Quell-URL anhand des Eingabedateipfads
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourceUrl, options, sp);
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

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Konvertieren Sie die EPUB-Quelle, die durch den Eingabe-[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) bereitgestellt wird, zu XPS. Das Ergebnis ist XPS-Ausgabedaten, definiert durch eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interface-Implementierung.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Konvertierungsoptionen. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Konvertierungsprozess mit der Standard‑Konfiguration starten
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Konvertieren Sie die EPUB-Quelle, die durch den Eingabe-EPUB-Dateipfad bereitgestellt wird, zu XPS. Das Ergebnis sind XPS-Ausgabedaten, definiert durch eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interface-Implementierung.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Konvertierungsoptionen. Die Verwendung des [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objekts ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die Seitengröße, Ränder, CSS usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider-Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Konvertierungsprozess mit der Standard‑Konfiguration starten
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Konvertieren Sie die EPUB-Quelle, die über eine URL bereitgestellt wird, zu einer XPS-Datei, die durch den vollständigen Pfad definiert ist. Das Ergebnis sind XPS-Ausgabedaten, definiert durch eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interface-Implementierung.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Konvertierungsoptionen. [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) Objektverwendung ermöglicht es Ihnen, den Rendering-Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe die [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Hinweise

Wie man EPUB nach XPS konvertiert

Eine XPS-Datei stellt Seitenlayout-Dateien dar, die auf den von Microsoft erstellten XML Paper Specifications basieren. Sie wurde als Ersatz des EMF-Dateiformats entwickelt und ist dem PDF-Dateiformat ähnlich, verwendet jedoch XML für Layout, Darstellung und Druckinformationen eines Dokuments.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu nutzen. Im spezifischen Leitfaden für den EPUB Converter XPS finden Sie den folgenden Artikel:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB nach XPS konvertieren

Um EPUB in das XPS-Dateiformat zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB-Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der ConvertEPUB-Methode definieren. Verwenden Sie eine bekannte oder benutzerdefinierte ICreateStreamProvider-Interface-Implementierung als Ausgabedatenpuffer. Wir können eine einfachere Alternative als Ergebnis-Ausgabedateipfad verwenden. Erstellen Sie ein neues XpsSaveOptions-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der XpsSaveOptions-Klasse zu verwenden. Verwenden Sie die ConvertEPUB()-Methode der statischen Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen das EPUB-Quelldatum, XpsSaveOptions und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB-zu-XPS-Konverter

Aspose.HTML bietet einen kostenlosen Online-[EPUB‑zu‑XPS](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in eine XPS-Datei mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Erstellen Sie die Quell-URL anhand des Eingabedateipfads
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new XpsSaveOptions();

// Konvertierungsprozess mit der Standard‑Konfiguration starten
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Konvertieren Sie die EPUB-Quelldatei, angegeben durch den vollständigen Pfad, zu DOCX. Das Ergebnis ist eine DOCX-Datei, die durch den vollständigen Pfad definiert wird.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Konvertierungsquelle, die durch den Eingabe-[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) bereitgestellt wird. |
| options | DocSaveOptions | Konvertierungsoptionen. Die Verwendung des [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Vollständiger .docx-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions();   

// Konvertierungsprozess starten
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Konvertieren Sie die EPUB-Quelle, die durch einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Ergebnis ist eine docx-Datei, die durch den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad als Eingabeparameter. |
| options | DocSaveOptions | Konvertierungsoptionen. Die Verwendung des [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Vollständiger .docx-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definieren Sie die Standardoptionen‑Instanz
var options = new DocSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Konvertieren Sie die EPUB-Quelle, die durch eine URL bereitgestellt wird. Ergebnis ist eine docx-Datei, die durch den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Verwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Vollständiger .docx-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Erstellen Sie die Quell-URL anhand des Eingabedateipfads
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definieren Sie die Standardoptionen‑Instanz
var options = new DocSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Konvertieren Sie die EPUB-Quelle, die durch einen Dateneingabestream bereitgestellt wird. Ergebnis ist eine docx-Datei, die durch den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Konvertierungsoptionen. Die Verwendung des [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Vollständiger .docx-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions();   

// Starten Sie den Konvertierungsprozess mit der Standardkonfiguration
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Konvertieren Sie die EPUB-Quelle, die durch einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Ergebnis ist eine docx-Datei, die durch den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Konvertierungsoptionen. Die Verwendung des [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions)object‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die Seitengröße, Ränder, CSS usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Vollständiger .docx-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Definieren Sie die Standardoptionen‑Instanz
var options = new DocSaveOptions();

// Konvertierungsprozess mit Standardkonfiguration starten
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Konvertieren Sie die EPUB-Quelle, die durch eine URL bereitgestellt wird. Ergebnis ist eine docx-Datei, die durch den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Verwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Vollständiger .docx-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Erstellen Sie die Quell-URL anhand des Eingabedateipfads
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Pfad der Ergebnisdatei der Formularkonvertierung
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions();

// Starten Sie den Konvertierungsprozess mit der Standardkonfiguration  
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Konvertieren Sie die EPUB-Quelle als Eingabestream zu DOCX. Das Ergebnis ist eine DOCX-Datei, die durch eine ICreateStreamProvider-Implementierung erzeugt wird.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| options | DocSaveOptions | Konvertierungsoptionen. Die Verwendung des [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions();   

// Konvertierungsprozess starten
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Konvertieren Sie die EPUB‑Quelle, die als vollständiger Dateipfad angegeben ist, nach DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung von [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) erzeugt werden.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | DocSaveOptions | Konvertierungsoptionen. Die Verwendung des [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions ();   

// Starten Sie den Konvertierungsprozess  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Konvertieren Sie die EPUB-Quelle, die durch eine URL bereitgestellt wird. Ergebnis sind Ausgabedaten, die durch die Implementierung des ICreateStreamProvider Interfaces erzeugt werden.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Verwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die Seitengröße, Ränder, Auflösungen, CSS usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues DocSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Erstellen Sie die Quell-URL anhand des Eingabedateipfads
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions ();   

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourceUrl, options, sp);





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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Konvertieren Sie die EPUB-Quelle, die durch einen Dateneingabestream bereitgestellt wird. Ergebnis sind Ausgabedaten, die durch die Implementierung des ICreateStreamProvider Interfaces erzeugt werden.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Verwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions();   

// Starten Sie den Konvertierungsprozess mit der Standardkonfiguration
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Konvertieren Sie die EPUB‑Quelle, die als vollständiger Dateipfad angegeben ist, nach DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt werden.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Konvertierungsoptionen. Die Verwendung des [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions ();   

// Starten Sie den Konvertierungsprozess  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Konvertieren Sie die EPUB‑Quelle, die über eine URL angegeben ist, nach DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt werden.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungskonfiguration. Stellt das [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) Kontextobjekt dar, das verwendet wird, um die Umgebungs‑einstellungen für die Anwendung einzurichten. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Verwendung ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces, das zum Abrufen eines Ausgabestreams verwendet wird. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Hinweise

Wie man EPUB nach DOCX konvertiert

DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Dieses Format ist beliebt, weil es eine breite Palette von Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen. DOCX‑Dateien können mit Word 2007 und späteren Versionen geöffnet werden, jedoch nicht mit den älteren Versionen von MS Word, die das DOC‑Dateiformat unterstützen. Die Konvertierung von EPUB nach DOCX ist häufig erforderlich, um das DOCX‑Format für bestimmte Benutzeraufgaben zu nutzen.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen über die unterstützten EPUB‑Konvertierungsszenarien und deren Durchführung mithilfe der Klasse [`Converter`](../), die alle Low‑Level‑Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie komfortabel und einfach zu verwenden. Im EPUB‑Converter‑DOCX‑Spezialleitfaden finden Sie den folgenden Artikel:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach DOCX konvertieren

Um das EPUB‑Dateiformat nach DOCX zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des Interfaces ICreateStreamProvider als Ausgabedatenpuffer. Alternativ können wir auch einen einfacheren Ansatz über einen Ergebnis‑Ausgabepfad nutzen. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse DocSaveOptions zu verwenden. Nutzen Sie die ConvertEPUB()-Methode der statischen Klasse Converter, um das EPUB als DOCX‑Datei zu speichern. Sie müssen das EPUB‑Quelldatum entweder als Dateipfad oder Eingabestream sowie Url, eine DocSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/)‑Kontextobjekt darstellt und zum Einrichten der Umgebungs‑Einstellungen für die Anwendung dient. Online‑EPUB‑zu‑DOCX‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps)‑Konverter, der EPUB in DOCX‑Dateien mit hoher Qualität, einfach und schnell konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Url basierend auf Eingabedateipfad erstellen
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new DocSaveOptions();   

// Starten Sie den Konvertierungsprozess mit der Standardkonfiguration
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





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

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Konvertieren Sie die EPUB-Quelle, bereitgestellt durch einen Dateneingabestream. Das Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | EPUB‑Quelldateipfad als Eingabeparameter. |
| options | PdfSaveOptions | Konvertierungsoptionen. Die Verwendung des [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Vollständiger .pdf-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Formular Ergebnisdateipfad  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new PdfSaveOptions();   

// Starten Sie den Konvertierungsprozess  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Konvertieren Sie die EPUB-Quelle, die durch einen vollständigen Dateipfad bereitgestellt wird, zu PDF. Ergebnis ist eine pdf-Datei, die durch den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | PdfSaveOptions | Konvertierungsoptionen. Die Verwendung des [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Vollständiger .pdf-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)-Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definieren Sie die Standardoptionen‑Instanz
var options = new PdfSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Konvertieren Sie die EPUB-Quelle, die durch eine URL bereitgestellt wird. Ergebnis ist eine pdf-Datei, die durch den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | PdfSaveOptions | Die Verwendung von [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/), die [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Vollständiger .pdf-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Url basierend auf Eingabedateipfad erstellen
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definieren Sie die Standardoptionen‑Instanz
var options = new com.aspose.html.saving.PdfSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Konvertieren Sie die EPUB-Quelle, bereitgestellt durch einen Dateneingabestream. Das Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Konvertierungsoptionen. Die Verwendung des [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Vollständiger .pdf-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Formular Ergebnisdateipfad  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new PdfSaveOptions();   

// Starten Sie den Konvertierungsprozess mit der Standardkonfiguration
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Konvertieren Sie die EPUB-Quelle, bereitgestellt durch einen Dateneingabestream. Das Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Konvertierungsoptionen. Die Verwendung des [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Vollständiger .pdf-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definieren Sie die Standardoptionen‑Instanz
var options = new PdfSaveOptions();

// Konvertierungsprozess mit Standardkonfiguration starten
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Konvertieren Sie die EPUB-Quelle, die durch eine URL bereitgestellt wird. Ergebnis ist eine pdf-Datei, die durch den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungskonfiguration. Stellt das [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) Kontextobjekt dar, das verwendet wird, um die Umgebungs‑einstellungen für die Anwendung einzurichten. |
| options | PdfSaveOptions | Die Verwendung von [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/), die [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Vollständiger .pdf-Dateipfad als Ergebnis der Ausgabe‑Konvertierung. |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;
import com.aspose.html.converters;
...  
// Url basierend auf Eingabedateipfad erstellen
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Erstellen Sie den Ausgabedateipfad für das Ergebnis
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Definieren Sie die Standardoptionen‑Instanz
var options = new PdfSaveOptions();

// Konvertierungsprozess mit Standardkonfiguration starten
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Konvertieren Sie die EPUB‑Quelle, die als Eingabestream bereitgestellt wird. Das Ergebnis ist ein Ausgabedatenstrom, der durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt wird.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| options | PdfSaveOptions | Konvertierungsoptionen. Die Verwendung des [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) Interface‑Implementierung. |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new PdfSaveOptions ();   

// Starten Sie den Konvertierungsprozess  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Konvertieren Sie die EPUB‑Quelle, die als vollständiger Dateipfad angegeben ist, zu PDF. Das Ergebnis ist ein Ausgabedatenstrom, der durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt wird.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| options | PdfSaveOptions | Konvertierungsoptionen. Die Verwendung des [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new PdfSaveOptions();   

// Starten Sie den Konvertierungsprozess  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Konvertieren Sie die EPUB‑Quelle, die über eine URL angegeben ist, nach DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt werden.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| options | PdfSaveOptions | Die Verwendung von [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/), die [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)-Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;   
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Url basierend auf Eingabedateipfad erstellen
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definieren Sie die Standardoptionen‑Instanz
var options = new PdfSaveOptions();

// Konvertierungsprozess starten
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Konvertieren Sie die EPUB‑Quelle, die als Eingabestream bereitgestellt wird. Das Ergebnis ist ein Ausgabedatenstrom, der durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt wird.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Strom | Eingabestream als Konvertierungsquelle. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Konvertierungsoptionen. Die Verwendung des [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das [`com.aspose.html.converters`](../)-Paket bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)-Konvertierungen in gängige Formate bereit, wie zum Beispiel [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Öffnen Sie die vorhandene Datei zum Lesen als Stream  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new PdfSaveOptions ();   

// Konvertierungsprozess mit Standard‑Konfigurationsobjekt starten  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Konvertieren Sie die EPUB-Quelle, die durch einen vollständigen Dateipfad bereitgestellt wird, zu PDF. Ergebnis sind Ausgabedaten, die durch die Implementierung des ICreateStreamProvider Interfaces erzeugt werden.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | EPUB‑Quelldateipfad. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungskonfiguration. Stellt das [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) Kontextobjekt dar, das verwendet wird, um die Umgebungs‑einstellungen für die Anwendung einzurichten. |
| options | PdfSaveOptions | Konvertierungsoptionen. Die Verwendung des [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die Seitengröße, Ränder, CSS usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)-Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formular für Quelldateipfad
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Erstellen Sie die Standardoptionen‑Instanz  
var options = new PdfSaveOptions();   

// Konvertierungsprozess mit Standard‑Konfigurationsobjekt starten 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Konvertieren Sie die EPUB‑Quelle, die über eine URL angegeben ist, nach DOCX. Das Ergebnis sind Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces erzeugt werden.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | EPUB‑Quell‑URL – liefert eine Objekt­darstellung eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungskonfiguration. Stellt das [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) Kontextobjekt dar, das verwendet wird, um die Umgebungs‑einstellungen für die Anwendung einzurichten. |
| options | PdfSaveOptions | Die Verwendung von [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen; Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), die [`margins`](../../../com.aspose.html.drawing/page/margin/), die [`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), den [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. Siehe [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider)-Interfaces, das verwendet wird, um einen Ausgabestream zu erhalten. Siehe ein erweitertes Beispiel in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Hinweise

Wie man EPUB nach PDF konvertiert

EPUB ist ein E‑Book‑Dateiformat, das ein standardisiertes digitales Publikationsformat bereitstellt. Es wurde vom International Digital Publishing Forum ([IDPF](http://idpf.org/)) entwickelt und wird heute von vielen E‑Readern und Softwareanwendungen unterstützt. Die Konvertierung von EPUB nach PDF ist häufig erforderlich, um die Vorteile des PDF‑Formats zu nutzen. Das PDF‑Dateiformat kann umfassende Informationen wie Text, Bilder, Hyperlinks, Formularfelder, Rich‑Media, Metadaten usw. enthalten. PDF‑Dateien können im Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox geöffnet werden. Sie sind für den Druck optimiert und eignen sich ideal zur Erstellung physischer Kopien Ihrer Dokumente; Sie können zudem die Sicherheitseinstellungen für PDF konfigurieren.

Das Hauptmerkmal von Aspose.HTML ist die Konvertierungsfunktion. EPUB ist ein offenes, XML‑basiertes Format für digitale Bücher und Publikationen, das auf Smartphones, Tablets und Computern angezeigt und gelesen werden kann. Das Paket com.aspose.html.converters bietet einfachen Zugriff auf Konvertierungsmethoden. Es stellt eine breite Palette von [EPUB](https://docs.fileformat.com/ebook/epub/)‑Konvertierungen in gängige Formate bereit, wie z. B. [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/) und [GIF](https://docs.fileformat.com/image/gif/).

Dieser Abschnitt liefert Informationen zur Liste der unterstützten EPUB-Konvertierungsszenarien und wie man sie mithilfe einer [`Converter`](../)-Klasse ausführt, die alle Low-Level-Konvertierungsoperationen in einer einzigen Klasse zusammenfasst, um sie bequem und einfach zu benutzen. Im spezifischen Leitfaden zum EPUB‑Converter‑PDF finden Sie den folgenden Artikel:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB nach PDF konvertieren

Um das EPUB‑Dateiformat in PDF zu konvertieren, sollten Sie einige Schritte befolgen:

Öffnen Sie eine vorhandene EPUB‑Datei. Als Beispiel können wir den Quelldateipfad als ersten Parameter der Methode ConvertEPUB festlegen. Alternativ können wir einen Eingabestream oder ein Url‑Objekt verwenden. Verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des ICreateStreamProvider‑Interfaces als Ausgabedatenpuffer. Wir können auch die einfachere Alternative eines Ergebnis‑Ausgabedateipfads nutzen. Erstellen Sie ein neues PdfSaveOptions‑Objekt mit einer Reihe bevorzugter Parameter wie Seitengröße, Ränder, CSS usw. Es ist möglich, die Standardinstanz der Klasse PdfSaveOptions zu verwenden. Verwenden Sie die Methode ConvertEPUB() der statischen Klasse Converter, um EPUB als PDF‑Datei zu speichern. Sie müssen die EPUB‑Quelldaten als Dateipfad oder Eingabestream sowie Url, eine PdfSaveOptions‑Instanz und den Ausgabedatenpuffer in beliebiger Form übergeben, um den Konvertierungsprozess zu starten. Sie können die Konfiguration verwenden, die das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt darstellt und zum Einrichten der Umgebungseinstellungen für die Anwendung verwendet wird. Online EPUB‑zu‑PDF‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[EPUB‑to‑PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf)‑Konverter, der EPUB‑Dateien mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Url basierend auf Eingabedateipfad erstellen
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Verweisen Sie auf die ICreateStreamProvider‑Interface‑Implementierung  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Definieren Sie die Standardoptionen‑Instanz
var options = new PdfSaveOptions();

// Konvertierungsprozess mit dem Standard‑Konfigurationsobjekt starten
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
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
