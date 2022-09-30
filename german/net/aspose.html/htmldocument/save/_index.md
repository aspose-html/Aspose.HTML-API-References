---
title: Save
second_title: Aspose.HTML für .NET-API-Referenz
description: Speichert das Dokument in der durch angegebenen lokalen DateiURL Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert dessen Name wie folgt aufgebaut ist output_file_name  _files.
type: docs
weight: 130
url: /de/net/aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(Url url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`URL` ist keine gültige lokale Datei-URL. |

### Siehe auch

* class [Url](../../url)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher.

```csharp
public void Save(IOutputStorage outputStorage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStorage | IOutputStorage | Der Ausgangsspeicher[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |

### Siehe auch

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(string) {#save_10}

Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`Weg` ist kein gültiger lokaler Dateipfad. |

### Siehe auch

* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveFormat) {#save_11}

Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |
| saveFormat | HTMLSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`Weg` ist kein gültiger lokaler Dateipfad. |

### Siehe auch

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveFormat | HTMLSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`URL` ist keine gültige lokale Datei-URL. |

### Siehe auch

* class [Url](../../url)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveFormat) {#save_1}

Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStorage | IOutputStorage | Der Ausgangsspeicher[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveFormat | HTMLSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Siehe auch

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveOptions) {#save_12}

Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |
| saveOptions | HTMLSaveOptions | HTML-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`Weg` ist kein gültiger lokaler Dateipfad. |

### Siehe auch

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveOptions | HTMLSaveOptions | HTML-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`URL` ist keine gültige lokale Datei-URL. |

### Siehe auch

* class [Url](../../url)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveOptions) {#save_2}

Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStorage | IOutputStorage | Der Ausgangsspeicher[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveOptions | HTMLSaveOptions | HTML-Speicheroptionen. |

### Siehe auch

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(string, MarkdownSaveOptions) {#save_13}

Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |
| saveOptions | MarkdownSaveOptions | Markdown-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`Weg` ist kein gültiger lokaler Dateipfad. |

### Siehe auch

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveOptions | MarkdownSaveOptions | Markdown-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`URL` ist keine gültige lokale Datei-URL. |

### Siehe auch

* class [Url](../../url)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MarkdownSaveOptions) {#save_3}

Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher.

```csharp
public void Save(IOutputStorage outputStorage, MarkdownSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStorage | IOutputStorage | Der Ausgangsspeicher[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveOptions | MarkdownSaveOptions | Markdown-Speicheroptionen. |

### Siehe auch

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(string, MHTMLSaveOptions) {#save_14}

Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |
| saveOptions | MHTMLSaveOptions | MHTML-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`Weg` ist kein gültiger lokaler Dateipfad. |

### Siehe auch

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveOptions | MHTMLSaveOptions | MHTML-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`URL` ist keine gültige lokale Datei-URL. |

### Siehe auch

* class [Url](../../url)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MHTMLSaveOptions) {#save_4}

Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher.

```csharp
public void Save(IOutputStorage outputStorage, MHTMLSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStorage | IOutputStorage | Der Ausgangsspeicher[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveOptions | MHTMLSaveOptions | MHTML-Speicheroptionen. |

### Siehe auch

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions)
* class [HTMLDocument](../../htmldocument)
* namensraum [Aspose.Html](../../htmldocument)
* Montage [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
