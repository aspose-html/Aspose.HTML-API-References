---
title: OutputStream.Read
second_title: Aspose.HTML voor .NET API-referentie
description: OutputStream methode. Leest een reeks bytes uit de ingepakte uitvoerstroom en schuift de positie binnen de stroom op met het aantal gelezen bytes.
type: docs
weight: 100
url: /nl/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

Leest een reeks bytes uit de ingepakte uitvoerstroom en schuift de positie binnen de stroom op met het aantal gelezen bytes.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | Byte[] | Een reeks bytes. Wanneer deze methode terugkeert, bevat de buffer de gespecificeerde byte-array waarbij de waarden tussen offset en (offset + count - 1) zijn vervangen door de bytes die zijn gelezen uit de ingepakte uitvoerstroom. |
| offset | Int32 | De op nul gebaseerde byte-offset in de buffer waarop moet worden begonnen met het opslaan van de gegevens read uit de ingepakte uitvoerstroom. |
| count | Int32 | Het maximale aantal bytes dat moet worden gelezen uit de ingepakte uitvoerstroom. |

### Winstwaarde

Het totale aantal bytes dat in de buffer is gelezen. Dit kan minder zijn dan het aantal gevraagde bytes als dat aantal bytes momenteel niet beschikbaar is, of nul (0) als het einde van de stream is bereikt.

### Zie ook

* class [OutputStream](../)
* naamruimte [Aspose.Html.IO](../../outputstream/)
* montage [Aspose.HTML](../../../)


