---
title: "Converter.ConvertTemplate"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Converter-Methode. Füge die Vorlagenquelle, die durch ein HTMLDocument bereitgestellt wird, mit den Vorlagendaten XML JSON zusammen. Ergebnis ist eine HTML-Datei, die über den Ausgabepfad erstellt wird."
type: docs

url: /de/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Füge die Vorlagenquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird, mit den Vorlagendaten (XML, JSON) zusammen. Ergebnis ist eine HTML-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| template | HTMLDocument | Zusammenführen des Quellgerüsts, das durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Skeleton‑HTML‑Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Formular‑HTML‑Dokument als Konvertierungsquelle
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Konvertierungsprozess starten
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Ressourcen freigeben
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Führen Sie die Vorlagen‑HTML‑Quelle, die über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist eine HTML‑Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Zusammenführen des HTML‑Skeletons, das über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Skeleton‑HTML‑Quell‑URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess starten
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Führen Sie die Vorlagen‑HTML‑Quelle, die über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist eine HTML‑Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Zusammenführen des HTML‑Skeletons, das über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Skeleton‑HTML‑Quell‑URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess mit der Standard‑Konfiguration starten
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Siehe auch

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Füge die HTML-Vorlagenquelle zusammen, die über einen vollständigen Dateipfad bereitgestellt wird, mit den Vorlagendaten (XML, JSON). Ergebnis ist eine html-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Zusammenführen des HTML‑Skeletons, das über den vollständigen Dateipfad bereitgestellt wird. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Skeleton‑HTML‑Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess starten
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Siehe auch

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Füge die HTML-Vorlagenquelle zusammen, die über einen vollständigen Dateipfad bereitgestellt wird, mit den Vorlagendaten (XML, JSON). Ergebnis ist eine html-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Zusammenführen des HTML‑Skeletons, das über den vollständigen Dateipfad bereitgestellt wird. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Skeleton‑HTML‑Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess mit der Standard‑Konfiguration starten
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Füge die HTML-Vorlagenquelle zusammen, die durch Inline-Inhalt bereitgestellt wird, mit den Vorlagendaten (XML, JSON). Ergebnis ist eine html-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zusammenführen des HTML‑Skeletons, das über Inline‑String‑Inhalt bereitgestellt wird. |
| baseUrl | String | Basis‑URI der HTML‑Vorlage. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Formular‑Inline‑Quellinhalt als Vorlage
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
       
      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formularausgabe als Zusammenführungsergebnis
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();
	  
      // Konvertierungsprozess starten
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

### Siehe auch

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Füge die HTML-Vorlagenquelle zusammen, die durch Inline-Inhalt bereitgestellt wird, mit den Vorlagendaten (XML, JSON). Ergebnis ist eine html-Datei, die über den Ausgabepfad erstellt wird.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zusammenführen des HTML‑Skeletons, das über Inline‑String‑Inhalt bereitgestellt wird. |
| baseUrl | String | Basis‑URI der HTML‑Vorlage. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |
| outputPath | String | Vollständiger HTML-Dateipfad als Ausgabekonvertierungsergebnis. |

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Formular‑Inline‑Quellinhalt als Vorlage
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
    
   // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Definieren Sie eine TemplateData‑Objektinstanz
   var templateData = new TemplateData(templateDataPath);

   // Formularausgabe als Zusammenführungsergebnis
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Definieren Sie eine configuration‑Objektinstanz
   var configuration = new Configuration();

   // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
   var options = new TemplateLoadOptions();

   // Konvertierungsprozess mit der Standard‑Konfiguration starten
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Unten ist die Datendatei, die mit der Quelle als Vorlage zusammengeführt werden soll

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

### Siehe auch

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Führen Sie die Vorlagenquelle, die durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dargestellt wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist ein neu erstelltes HTMLDocument, das als Datei gespeichert werden kann.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| template | HTMLDocument | Zusammenführen des Quellgerüsts, das durch [`HTMLDocument`](../../../com.aspose.html/htmldocument/) bereitgestellt wird. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Skeleton‑HTML‑Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();
      
      // Formular‑HTML‑Dokument als Konvertierungsquelle
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Konvertierungsprozess starten
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Ergebnis mit verknüpften Ressourcen speichern
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Führen Sie die Vorlagen‑HTML‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist ein neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das als Datei gespeichert werden kann.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Zusammenführen des HTML‑Skeletons, das über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Erstellen Sie eine URL zur Skelett‑HTML‑Quelldatei
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess starten
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Ergebnis mit verknüpften Ressourcen speichern
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Führen Sie die Vorlagen‑HTML‑Quelle, die durch [`URL`](../../../com.aspose.html/url/) dargestellt wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist ein neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das als Datei gespeichert werden kann.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Zusammenführen des HTML‑Skeletons, das über [`URL`](../../../com.aspose.html/url/) bereitgestellt wird. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Erstellen Sie eine URL zur Skelett‑HTML‑Quelldatei
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess mit der Standard‑Konfiguration starten
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Ergebnis mit verknüpften Ressourcen speichern
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Siehe auch

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

Führen Sie die Vorlagen‑HTML‑Quelle, die durch einen vollständigen Dateipfad angegeben wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist ein neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das als Datei gespeichert werden kann.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Zusammenführen des HTML‑Skeletons, das über den vollständigen Dateipfad bereitgestellt wird. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Skeleton‑HTML‑Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess starten
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Ergebnis mit verknüpften Ressourcen speichern
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Führen Sie die Vorlagen‑HTML‑Quelle, die durch einen vollständigen Dateipfad angegeben wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist ein neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das als Datei gespeichert werden kann.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourcePath | String | Zusammenführen des HTML‑Skeletons, das über den vollständigen Dateipfad bereitgestellt wird. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Skeleton‑HTML‑Quelldateipfad
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formular für Ergebnisdateipfad
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess mit der Standard‑Konfiguration starten
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Ergebnis mit verknüpften Ressourcen speichern
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Führen Sie die Vorlagen‑HTML‑Quelle, die durch Inline‑Inhalt dargestellt wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist ein neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das als Datei gespeichert werden kann.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zusammenführen des HTML‑Skeletons, das über Inline‑String‑Inhalt bereitgestellt wird. |
| baseUrl | String | Basis‑URI der HTML‑Vorlage. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Inline‑Quellinhalt als Vorlage
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

      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formularausgabe als Zusammenführungsergebnis
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess starten und Ergebnis speichern
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

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Führen Sie die Vorlagen‑HTML‑Quelle, die durch Inline‑Inhalt dargestellt wird, mit den Vorlagendaten (XML, JSON) zusammen. Das Ergebnis ist ein neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/), das als Datei gespeichert werden kann.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Zusammenführen des HTML‑Skeletons, das über Inline‑String‑Inhalt bereitgestellt wird. |
| baseUrl | String | Basis‑URI der HTML‑Vorlage. Er wird mit dem Pfad des aktuellen Verzeichnisses kombiniert, um eine absolute URL zu bilden. |
| configuration | Configuration | Die Umgebungs‑Konfiguration. Stellt das [`configuration`](../../../com.aspose.html/configuration/) Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung festzulegen. |
| Daten | TemplateData | Vorlagendaten für das Zusammenführen – Ersetzung (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) Objektinstanz. Sie wird verwendet, um zu bestimmen, ob die Vorlagen- und Datenelementnamen übereinstimmen, unabhängig von Groß‑/Kleinschreibung (Optionen). |

### Rückgabewert

Neu erstelltes [`HTMLDocument`](../../../com.aspose.html/htmldocument/) als Konvertierungsergebnis, das über den Ausgabepfad gespeichert werden kann.

## Hinweise

Vorlagenzusammenführung

Die Idee des Zusammenführens von Vorlagen besteht darin, ein HTML‑Dokument basierend auf einer HTML‑Vorlage zu erstellen und es aus einer Datenquelle zu füllen. Aspose.HTML stellt die Syntax für Inline‑Ausdrücke bereit, um mit Vorlagen und verschiedenen Datentypen wie XML und JSON zu arbeiten. Siehe [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) , wo Sie weitere Informationen zum Zusammenführen von Vorlagen und zur Verwendung der Methode ConvertTemplate() finden.

Konvertierung (Zusammenführung) Schritte

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Vorlagenquelle. Definieren Sie die HTML‑Vorlagenquelle per Datei, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) Objektinstanz oder sogar per Inline‑Inhalt. Konvertierungsergebnis. Sie können das resultierende HTMLDocument direkt erhalten oder den Ausgabepfad für das Ergebnis abhängig von der Methodensignatur festlegen. Erstellen Sie eine Instanz von [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Verwenden Sie die Methode ConvertTemplate() der Klasse Converter, um die Vorlage mit den Daten zusammenzuführen. Sie können außerdem [`configuration`](../../../com.aspose.html/configuration/) als optionalen Parameter hinzufügen. Quellcode

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) herunterladen.

## Beispiele

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formular‑Inline‑Quellinhalt als Vorlage
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
       
      // Formular‑XML‑(JSON‑)Vorlagendaten‑Dateipfad
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Definieren Sie eine TemplateData‑Objektinstanz
      var templateData = new TemplateData(templateDataPath);

      // Formularausgabe als Zusammenführungsergebnis
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Definieren Sie eine configuration‑Objektinstanz
      var configuration = new Configuration();

      // Definieren Sie das Standard‑TemplateLoadOptions‑Objekt
      var options = new TemplateLoadOptions();

      // Konvertierungsprozess starten und Ergebnis speichern
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

### Siehe auch

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
