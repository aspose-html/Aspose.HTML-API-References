---
title: Save
second_title: Aspose.HTML für .NET-API-Referenz
description: Speichert das Dokument in der durch angegebenen lokalen DateiURL Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert dessen Name wie folgt aufgebaut ist output_file_name  _files.
type: docs
weight: 90
url: /de/net/aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

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

* class [Url](../../../aspose.html/url)
* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
* Montage [Aspose.HTML](../../../)

---

## Save(string) {#save_6}

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

* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
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
* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
* Montage [Aspose.HTML](../../../)

---

## Save(string, SVGSaveFormat) {#save_7}

Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`Weg` ist kein gültiger lokaler Dateipfad. |

### Siehe auch

* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
* Montage [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStorage | IOutputStorage | Der Ausgangsspeicher[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Siehe auch

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
* Montage [Aspose.HTML](../../../)

---

## Save(string, SVGSaveOptions) {#save_8}

Speichert das Dokument in der durch angegebenen lokalen Datei`Weg` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Lokaler Pfad zur Ausgabedatei. |
| saveOptions | SVGSaveOptions | SVG-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`Weg` ist kein gültiger lokaler Dateipfad. |

### Siehe auch

* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
* Montage [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

Speichert den Dokumentinhalt und die Ressourcen im Ausgabespeicher.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputStorage | IOutputStorage | Der Ausgangsspeicher[`IOutputStorage`](../../../aspose.html.io/ioutputstorage). |
| saveOptions | SVGSaveOptions | SVG-Speicheroptionen. |

### Siehe auch

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
* Montage [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveFormat | SVGSaveFormat | Format, in dem das Dokument gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`URL` ist keine gültige lokale Datei-URL. |

### Siehe auch

* class [Url](../../../aspose.html/url)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat)
* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
* Montage [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Speichert das Dokument in der durch angegebenen lokalen Datei`URL` Alle in diesem Dokument verwendeten Ressourcen werden in im angrenzenden Ordner gespeichert, dessen Name wie folgt aufgebaut ist: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Lokale URL zur Ausgabedatei. |
| saveOptions | SVGSaveOptions | SVG-Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn angegeben`URL` ist keine gültige lokale Datei-URL. |

### Siehe auch

* class [Url](../../../aspose.html/url)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions)
* class [SVGDocument](../../svgdocument)
* namensraum [Aspose.Html.Dom.Svg](../../svgdocument)
* Montage [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
