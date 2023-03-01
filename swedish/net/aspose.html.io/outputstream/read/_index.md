---
title: OutputStream.Read
second_title: Aspose.HTML för .NET API Referens
description: OutputStream metod. Läser en sekvens av byte från den lindade utdataströmmen och flyttar fram positionen i strömmen med antalet lästa byte.
type: docs
weight: 100
url: /sv/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

Läser en sekvens av byte från den lindade utdataströmmen och flyttar fram positionen i strömmen med antalet lästa byte.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | Byte[] | En uppsättning byte. När den här metoden återvänder innehåller bufferten den specificerade byte-matrisen med värdena mellan offset och (offset + count - 1) ersatta av byten som läses från den omslutna utströmmen. |
| offset | Int32 | Den nollbaserade byteförskjutningen i bufferten för att börja lagra data read från den omslutna utströmmen. |
| count | Int32 | Det maximala antalet byte som ska läsas från den lindade utströmmen. |

### Returvärde

Det totala antalet byte som läses in i bufferten. Detta kan vara mindre än antalet av byte som begärts om så många byte inte är tillgängliga för närvarande, eller noll (0) om slutet av strömmen har nåtts.

### Se även

* class [OutputStream](../)
* namnutrymme [Aspose.Html.IO](../../outputstream/)
* hopsättning [Aspose.HTML](../../../)


