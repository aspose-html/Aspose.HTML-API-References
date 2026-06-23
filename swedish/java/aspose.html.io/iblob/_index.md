---
title: "IBlob-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.io.IBlob-gränssnitt. Ett Blob-objekt refererar till en byte-sekvens och har ett size-attribut som är det totala antalet byte i sekvensen samt ett type-attribut som är en ASCII-kodad String i gemener som representerar mediatypen för byte-sekvensen."
type: docs

url: /sv/java/com.aspose.html.io/iblob/
---
## IBlob interface

Ett Blob-objekt refererar till en byte-sekvens och har ett size-attribut som är det totala antalet byte i byte-sekvensen, samt ett type-attribut som är en ASCII-kodad sträng i gemener som representerar mediatypen för byte-sekvensen.

```java
public interface IBlob
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) Returnerar storleken på byte-sekvensen i antal byte. Vid hämtning måste kompatibla användaragenter returnera det totala antalet byte som kan läsas av ett FileReader- eller FileReaderSync-objekt, eller 0 om Blob:en inte har några byte att läsa. |
| [getType](../../com.aspose.html.io/iblob/type/) Den ASCII‑kodade Stringen i gemener som representerar Blob:ens mediatyp. Vid hämtning måste användaragenter returnera typen av en Blob som en ASCII‑kodad String i gemener, så att när den konverteras till en byte‑sekvens blir den en parsbar MIME‑typ, eller den tomma Stringen – 0 byte – om typen inte kan bestämmas. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | Returnerar ett nytt Blob-objekt med byte‑sekvensen från det valfria start‑parametern upp till men utan det valfria slut‑parametern, samt med ett type‑attribut som är värdet på den valfria contentType‑parametern. |

### Se även

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
