---
title: Interface IBlob
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.IO.IBlob koppel. Ein BlobObjekt bezieht sich auf eine Bytefolge und hat ein Größenattribut das die Gesamtzahl der Bytes in der Bytefolge ist und ein Typattribut das eine ASCIIcodierte Zeichenfolge in Kleinbuchstaben ist die den Medientyp der Bytefolge darstellt .
type: docs
weight: 3700
url: /de/net/aspose.html.io/iblob/
---
## IBlob interface

Ein Blob-Objekt bezieht sich auf eine Bytefolge und hat ein Größenattribut, das die Gesamtzahl der Bytes in der Bytefolge ist, und ein Typattribut, das eine ASCII-codierte Zeichenfolge in Kleinbuchstaben ist, die den Medientyp der Bytefolge darstellt .

```csharp
public interface IBlob
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | Gibt die Größe der Bytefolge in Bytes zurück. Beim Abrufen müssen konforme Benutzeragenten die Gesamtzahl der Bytes zurückgeben, die von einem FileReader oder FileReaderSync-Objekt gelesen werden können, oder 0, wenn das Blob keine zu lesenden Bytes hat . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | Der ASCII-codierte String in Kleinbuchstaben, der den Medientyp des Blobs darstellt. Beim Abrufen müssen Benutzeragenten den Typ eines Blobs als ASCII-codierten String in Kleinbuchstaben zurückgeben, so dass er in ein Byte konvertiert wird Sequenz, es ist ein parsbarer MIME-Typ, oder die leere Zeichenfolge – 0 Bytes – wenn der Typ nicht bestimmt werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | Gibt ein neues Blob-Objekt mit Bytes zurück, die vom optionalen Startparameter bis zum optionalen Endparameter (ohne diesen) reichen, und mit einem Typattribut, das dem Wert des optionalen contentType-Parameters entspricht. |

### Siehe auch

* namensraum [Aspose.Html.IO](../../aspose.html.io/)
* Montage [Aspose.HTML](../../)


