---
title: Interface IBlob
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.IO.IBlob gränssnitt. Ett Blobobjekt hänvisar till en bytesekvens och har ett storleksattribut som är det totala antalet byte i bytesekvensen och ett typattribut som är en ASCIIkodad sträng med gemener som representerar mediatypen för bytesekvensen .
type: docs
weight: 3700
url: /sv/net/aspose.html.io/iblob/
---
## IBlob interface

Ett Blob-objekt hänvisar till en bytesekvens och har ett storleksattribut som är det totala antalet byte i bytesekvensen och ett typattribut, som är en ASCII-kodad sträng med gemener som representerar mediatypen för bytesekvensen .

```csharp
public interface IBlob
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | Returnerar storleken på bytesekvensen i antal byte. När användaragenter hämtar måste överensstämmande användaragenter returnera det totala antalet byte som kan läsas av ett FileReader eller FileReaderSync-objekt, eller 0 om Bloben inte har några byte att läsa . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | Den ASCII-kodade strängen med små bokstäver som representerar mediatypen för Blob. När användaragenter hämtar, måste användaragenter returnera typen av Blob som en ASCII-kodad sträng med gemener, så att när den konverteras till en byte sekvens är det en parserbar MIME-typ, eller den tomma strängen – 0 byte – om typen inte kan fastställas. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | Returnerar ett nytt Blob-objekt med bytes som sträcker sig från den valfria startparametern upp till men inte inklusive den valfria slutparametern, och med ett typattribut som är värdet för den valfria parametern contentType. |

### Se även

* namnutrymme [Aspose.Html.IO](../../aspose.html.io/)
* hopsättning [Aspose.HTML](../../)


