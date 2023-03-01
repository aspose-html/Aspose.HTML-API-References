---
title: Interface IBlob
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.IO.IBlob koppel. Een Blobobject verwijst naar een bytereeks en heeft een kenmerk size dat het totale aantal bytes in de bytereeks is en een typekenmerk een ASCIIgecodeerde tekenreeks in kleine letters die het mediatype van de bytereeks vertegenwoordigt .
type: docs
weight: 3700
url: /nl/net/aspose.html.io/iblob/
---
## IBlob interface

Een Blob-object verwijst naar een bytereeks en heeft een kenmerk size dat het totale aantal bytes in de bytereeks is, en een typekenmerk, een ASCII-gecodeerde tekenreeks in kleine letters die het mediatype van de bytereeks vertegenwoordigt .

```csharp
public interface IBlob
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | Retourneert de grootte van de bytereeks in aantal bytes. Bij ophalen moeten conforme user-agents het totale aantal bytes retourneren dat kan worden gelezen door een FileReader of FileReaderSync-object, of 0 als de blob geen bytes heeft om te lezen . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | De ASCII-gecodeerde tekenreeks in kleine letters die het mediatype van de blob vertegenwoordigt. Bij het ophalen moeten user-agents het type van een blob retourneren als een ASCII-gecodeerde tekenreeks in kleine letters, zodat wanneer deze wordt geconverteerd naar een byte reeks, is het een ontleedbaar MIME-type, of de lege tekenreeks – 0 bytes – als het type niet kan worden bepaald. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | Retourneert een nieuw Blob-object met bytes variërend van de optionele startparameter tot maar niet inclusief de optionele eindparameter en met een typekenmerk dat de waarde is van de optionele parameter contentType. |

### Zie ook

* naamruimte [Aspose.Html.IO](../../aspose.html.io/)
* montage [Aspose.HTML](../../)


