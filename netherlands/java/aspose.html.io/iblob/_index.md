---
title: "IBlob-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.io.IBlob interface. Een Blob-object verwijst naar een byte‑reeks en heeft een size‑attribuut dat het totale aantal bytes in de byte‑reeks aangeeft, en een type‑attribuut dat een ASCII‑gecodeerde String in kleine letters is die het mediatype van de byte‑reeks weergeeft."
type: docs

url: /nl/java/com.aspose.html.io/iblob/
---
## IBlob interface

Een Blob-object verwijst naar een bytevolgorde en heeft een size-atribuut dat het totale aantal bytes in de bytevolgorde aangeeft, en een type-atribuut, dat een ASCII-gecodeerde string in kleine letters is die het mediatype van de bytevolgorde weergeeft.

```java
public interface IBlob
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) Retourneert de grootte van de byte‑reeks in aantal bytes. Bij ophalen moeten conforme user agents het totale aantal bytes retourneren dat gelezen kan worden door een FileReader‑ of FileReaderSync‑object, of 0 als de Blob geen bytes heeft om te lezen. |
| [getType](../../com.aspose.html.io/iblob/type/) De ASCII‑gecodeerde String in kleine letters die het mediatype van de Blob weergeeft. Bij ophalen moeten user agents het type van een Blob retourneren als een ASCII‑gecodeerde String in kleine letters, zodanig dat wanneer deze wordt omgezet naar een byte‑reeks, het een parseerbaar MIME‑type is, of de lege String – 0 bytes – als het type niet kan worden bepaald. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | Retourneert een nieuw Blob-object met bytes die variëren van de optionele start‑parameter tot, maar exclusief, de optionele end‑parameter, en met een type‑attribuut dat de waarde van de optionele contentType‑parameter is. |

### Zie ook

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
