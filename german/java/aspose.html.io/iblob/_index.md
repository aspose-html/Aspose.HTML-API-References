---
title: "IBlob Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.io.IBlob Schnittstelle. Ein Blob-Objekt verweist auf eine Bytesequenz und besitzt ein size-Attribut, das die Gesamtzahl der Bytes in der Bytesequenz angibt, sowie ein type-Attribut, das ein ASCII‑kodierter String in Kleinbuchstaben ist und den Medientyp der Bytesequenz darstellt."
type: docs

url: /de/java/com.aspose.html.io/iblob/
---
## IBlob interface

Ein Blob-Objekt bezieht sich auf eine Byte‑Sequenz und hat ein Größenattribut, das die Gesamtzahl der Bytes in der Sequenz angibt, sowie ein Typ‑Attribut, das ein ASCII‑kodierter String in Kleinbuchstaben ist und den Medientyp der Byte‑Sequenz darstellt.

```java
public interface IBlob
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) Gibt die Größe der Bytesequenz in Bytes zurück. Beim Abrufen müssen konforme User Agents die Gesamtzahl der Bytes zurückgeben, die von einem FileReader‑ oder FileReaderSync‑Objekt gelesen werden können, oder 0, wenn das Blob keine lesbaren Bytes enthält. |
| [getType](../../com.aspose.html.io/iblob/type/) Der ASCII‑kodierte String in Kleinbuchstaben, der den Medientyp des Blob darstellt. Beim Abrufen müssen User Agents den Typ eines Blob als ASCII‑kodierten String in Kleinbuchstaben zurückgeben, sodass er bei Umwandlung in eine Bytesequenz ein parsbarer MIME‑Typ ist, oder den leeren String – 0 Bytes – wenn der Typ nicht ermittelt werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | Gibt ein neues Blob-Objekt zurück, dessen Bytes vom optionalen start‑Parameter bis (aber ohne) den optionalen end‑Parameter reichen, und dessen type‑Attribut den Wert des optionalen contentType‑Parameters hat. |

### Siehe auch

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
