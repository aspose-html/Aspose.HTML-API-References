---
title: "Converter.ConvertMHTML"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Converter‑Methode. Konvertieren Sie die MHTML‑Quelle, die durch einen Eingabestream bereitgestellt wird. Das Ergebnis ist eine XPS‑Datei, die durch den Ausgabepfad erstellt wird."
type: docs

url: /de/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Konvertiere MHTML-Quelle, die über einen Eingabe-[stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) bereitgestellt wird. Ergebnis ist eine xps-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabe‑MHTML‑(.mht)‑Datenstream. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Konvertieren Sie die MHTML-Quelle, die über den vollständigen Dateipfad angegeben wird, in XPS. Ergebnis ist eine XPS-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Standard‑XpsSaveOptions‑Objekt definieren
	var options = new XpsSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Konvertieren Sie die MHTML-Quelle, die über eine URL angegeben wird. Ergebnis ist eine XPS-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formular-Quelldateipfad
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Formular‑Ergebnisdateipfad
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Standard‑XpsSaveOptions‑Objekt definieren
	var options = new XpsSaveOptions();

	// Konvertierungsprozess starten
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Konvertieren Sie die MHTML-Quelle, die über einen Eingabe-[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) bereitgestellt wird. Ergebnis ist eine XPS-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Konvertierungsquelle MHTML (.mht) Datenstrom. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Konvertieren Sie die MHTML-Quelle, die über den vollständigen Dateipfad angegeben wird, in XPS. Ergebnis ist eine XPS-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Konvertieren Sie die MHTML-Quelle, die über eine URL angegeben wird. Ergebnis ist eine XPS-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Vollständiger XPS-Dateipfad als Ausgabe‑Konvertierungsergebnis. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formular-Quelldateipfad
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Konvertiere die MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Konvertierungsquelle MHTML (.mht) Datenstrom. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Konvertiere die MHTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu XPS. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Konvertiere die MHTML-Quelle, die über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Konvertiere die MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Konvertierungsquelle MHTML (.mht) Datenstrom. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Konvertiere die MHTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu XPS. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Konvertiere die MHTML-Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | XpsSaveOptions | Die Verwendung des [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose‑Dokumentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu [XPS](https://docs.fileformat.com/page-description-language/xps/) wird häufig benötigt, um das XPS‑Format für bestimmte Aufgaben zu nutzen. Eine XPS‑Datei stellt Seitenlayout‑Dateien dar, die auf den XML‑Paper‑Specifications basieren und von Microsoft erstellt wurden.

Siehe den [Artikel](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/), in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertHTML()-Methoden der Klasse [`Converter`](../) zu XPS konvertieren und wie Sie die Parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu XPS konvertieren

Die Klasse Converter bietet einige MHTML‑spezifische Konvertierungen zu XPS. Um MHTML zu XPS zu konvertieren, sollten Sie einem der einfachen Szenarien folgen, die aus wenigen Schritten bestehen:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Quelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabepfad der Ergebnisdatei oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)-Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)-Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Klasse Converter, um MHTML mit drei oder mehr Parametern, abhängig vom Anwendungsszenario, als XPS zu speichern. Online‑MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML‑zu‑XPS‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-xps), der MHTML mit hoher Qualität, einfach und schnell zu XPS konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie das Ergebnis in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑XpsSaveOptions‑Objekt definieren
      var options = new XpsSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Konvertiere MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Ergebnis ist eine docx-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Konvertiere MHTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Ergebnis ist eine docx-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | MHTML-Quelldateipfad. Er wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Konvertieren Sie die MHTML-Quelle, die über eine URL angegeben wird. Ergebnis ist eine DOCX-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Konvertiere MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Ergebnis ist eine docx-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Konvertiere MHTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Ergebnis ist eine docx-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Konvertiere die MHTML-Quelle, die über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist eine DOCX‑Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-[`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Vollständiger docx-Dateipfad als Ergebnis der Ausgabeumwandlung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Konvertiere die MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Konvertiere die MHTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Konvertiere die MHTML-Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-[`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Konvertiere die MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Konvertiere die MHTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird, zu DOCX. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem configuration als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Konvertiere die MHTML-Quelle, die über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-[`URL`](../../../com.aspose.html/url/) – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | DocSaveOptions | Die Verwendung des [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Infos finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu DOCX wird häufig benötigt, um das [DOCX](https://docs.fileformat.com/word-processing/docx/)-Format für bestimmte Aufgaben zu nutzen. DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Es kann eine Vielzahl von Daten enthalten, darunter Text, Tabellen, Raster‑ und Vektorgrafiken, Video, Audio und Diagramme. Dieses Format ist beliebt, weil es komplexe Formatierungsfunktionen unterstützt und den Benutzern zahlreiche Möglichkeiten bietet, jede Art von Dokument zu erstellen.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), wo Sie Informationen darüber finden, wie Sie MHTML zu DOCX mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML zu DOCX konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen zu DOCX. Um MHTML zu DOCX zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML‑(.mht)‑Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten Stream als Konvertierungsquelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces als Ausgabedatenpuffer. Erstellen Sie ein neues [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)‑Objekt mit spezifischen oder Standard‑Einstellungen. Sie können außerdem configuration als Optionsparameter hinzufügen. Verwenden Sie die ConvertMHTML()-Methode der Converter‑Klasse, um MHTML als DOCX‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Anwendungsszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online‑[MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx), der MHTML mit hoher Qualität, einfach und schnell zu DOCX konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑DocSaveOptions‑Objekt festlegen
      var options = new DocSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Konvertiere MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Ergebnis ist eine pdf-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch [`configuration`](../../../com.aspose.html/configuration/) als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Konvertieren Sie die MHTML-Quelle, die über den vollständigen Dateipfad angegeben wird, in PDF. Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Konvertieren Sie die MHTML-Quelle, die über eine URL angegeben wird. Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Konvertiere MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Ergebnis ist eine pdf-Datei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Konvertieren Sie die MHTML-Quelle, die über den vollständigen Dateipfad angegeben wird, in PDF. Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | MHTML-Quelldateipfad. Er wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Konvertieren Sie die MHTML-Quelle, die über eine URL angegeben wird. Ergebnis ist eine PDF-Datei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Vollständiger PDF-Dateipfad als Ausgabe des Konvertierungsergebnisses. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Konvertiere die MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Konvertieren Sie die MHTML-Quelle, die durch einen vollständigen Dateipfad angegeben ist, in PDF. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | MHTML-Quelldateipfad. Er wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Konvertiere die MHTML-Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Konvertiere die MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Konvertieren Sie die MHTML-Quelle, die durch einen vollständigen Dateipfad angegeben ist, in PDF. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Konvertiere die MHTML-Quelle, die über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | PdfSaveOptions | Die Verwendung des [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)‑Objekts ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Weitere Informationen finden Sie in der [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Die Konvertierung von MHTML zu PDF wird häufig benötigt, um das [PDF](https://docs.fileformat.com/pdf/)-Format für bestimmte Aufgaben zu nutzen. PDF bietet viele Vorteile, die andere Dateien nicht haben. Beispielsweise unterstützen viele Programme und Apps PDF‑Dokumente; PDF‑Dateien sind für den Druck optimiert und eignen sich ideal zum Erstellen physischer Kopien Ihrer Dokumente; Sie können die Sicherheitseinstellungen für PDF‑Dateien konfigurieren – Drucken, Bearbeiten, Verwendung einer elektronischen Signatur usw. deaktivieren.

Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), wo Sie Informationen darüber finden, wie Sie MHTML zu PDF mit den ConvertMHTML()-Methoden der [`Converter`](../)-Klasse konvertieren und wie Sie die Parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in PDF konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen nach PDF. Um MHTML in PDF zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte Url als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als PDF‑Ergebnis mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑PDF‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf), der MHTML mit hoher Qualität, einfach und schnell in PDF konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definieren Sie das Standard‑PdfSaveOptions‑Objekt
      var options = new PdfSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Konvertiere MHTML-Quelle, die über einen Eingabestream bereitgestellt wird, zu einem Bild. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Konvertiere MHTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Siehe auch

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Konvertieren Sie die MHTML-Quelle, die über eine URL angegeben wird. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Konvertiere MHTML-Quelle, die über einen Eingabestream bereitgestellt wird, zu einem Bild. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Konvertiere MHTML-Quelle, die über einen vollständigen Dateipfad bereitgestellt wird. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erstellt wird.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Konvertieren Sie die MHTML-Quelle, die über eine URL angegeben wird. Ergebnis ist eine Bilddatei, die über den Ausgabedateipfad erzeugt wird.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| outputPath | String | Vollständiger Bilddateipfad als Ergebnis der Konvertierung. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Konvertiere die MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Konvertieren Sie die MHTML-Quelle, die durch einen vollständigen Dateipfad angegeben ist, in ein Bild. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Konvertiere die MHTML-Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Bekannt (siehe [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)‑Interface‑Implementierung. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Konvertiere die MHTML-Quelle, die über einen Eingabestream bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Eingabedatenstrom für die MHTML-Konvertierung. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Konvertierungsprozess starten
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Konvertieren Sie die MHTML-Quelle, die durch einen vollständigen Dateipfad angegeben ist, in ein Bild. Das Ergebnis ist Ausgabedaten, die durch die [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung erzeugt werden.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Vollständiger Dateipfad der MHTML-Quelle. |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung der [` interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions();

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Konvertiere die MHTML-Quelle, die über eine URL bereitgestellt wird. Das Ergebnis ist Ausgabedaten, die durch die Implementierung des [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Interfaces gebildet werden.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceUrl | Url | MHTML-Quell-Dokument-URL – liefert eine Objektrepräsentation eines universellen Identifikators (URL). |
| configuration | Configuration | Die Umgebungs­konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| options | ImageSaveOptions | Die Verwendung des Objekts [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) ermöglicht es Ihnen, den Rendering‑Prozess anzupassen. Sie können die [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) usw. festlegen. |
| provider | ICreateStreamProvider | Implementierung des [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), die verwendet wird, um einen Ausgabestream zu erhalten. |

## Hinweise

MHTML‑Konverter

Dateien mit der Erweiterung [MHTML](https://docs.fileformat.com/web/mhtml/) stellen ein Webseitensicherungsformat dar, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Das Format ist als Archivformat bekannt, weil es den HTML‑Code der Webseite und zugehörige Ressourcen in einer einzigen Datei speichert. Diese Ressourcen umfassen alles, was mit der Webseite verknüpft ist, wie Bilder, Applets, Animationen, Audiodateien usw. MHTML‑Dateien können in verschiedenen Anwendungen wie Internet Explorer und Microsoft Word geöffnet werden. Die genauen Spezifikationen des Formats sind im [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) beschrieben.

Siehe den Artikel, in dem Sie Informationen darüber finden, wie Sie MHTML mit den ConvertMHTML()-Methoden der Converter‑Klasse in Bilder verschiedener Formate konvertieren und wie Sie die Parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) und [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) anwenden.

MHTML in Bild konvertieren

Die Converter‑Klasse bietet einige MHTML‑spezifische Konvertierungen in Bilder. Unterstützte Formate sind [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) und [TIFF](https://docs.fileformat.com/image/tiff/). Um MHTML in ein Bild zu konvertieren, sollten Sie einem einfachen Szenario folgen, das aus wenigen Schritten besteht:

Konvertierungsquelle. Erkennen Sie eine vorhandene lokale MHTML (.mht)-Datei oder eine entfernte [`Url`](../../../com.aspose.html/url/) als Konvertierungsquelle. Sie können auch einen Standard‑ oder benutzerdefinierten spezifischen Stream als Quelle verwenden. Konvertierungsergebnis. Definieren Sie den Ausgabedateipfad des Ergebnisses oder verwenden Sie eine bekannte oder benutzerdefinierte [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) Schnittstellenimplementierung als Ausgabedatenpuffer. Erstellen Sie ein neues [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) Objekt mit spezifischen oder Standard‑Einstellungen. Das Standard‑Bildformat ist PNG. Sie können auch configuration als Optionsparameter hinzufügen. Verwenden Sie die Methode ConvertMHTML() der Converter‑Klasse, um MHTML als Bild mit drei oder mehr Parametern zu speichern, abhängig vom Benutzerszenario. Online MHTML‑Konverter

Aspose.HTML bietet einen kostenlosen Online-[MHTML‑zu‑JPEG‑Konverter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg), der MHTML mit hoher Qualität, einfach und schnell in JPEG‑Dateien konvertiert. Laden Sie einfach Ihre Dateien hoch, konvertieren Sie sie und erhalten Sie die Ergebnisse in wenigen Sekunden!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formular‑Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result");

      // Standard‑ImageSaveOptions‑Objekt definieren
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Verwende eine Implementierung von ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Konvertierungsprozess mit Standardkonfiguration starten
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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
