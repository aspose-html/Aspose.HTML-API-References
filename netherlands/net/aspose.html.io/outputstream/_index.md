---
title: Class OutputStream
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.IO.OutputStream klas. Een surrogaatstroom omhult de echte uitvoerstroom en regelt de toegang ertoe. OutputStream bevat URIgegevens die de locatie van de uitvoerstroom beschrijven.
type: docs
weight: 3750
url: /nl/net/aspose.html.io/outputstream/
---
## OutputStream class

Een surrogaatstroom omhult de echte uitvoerstroom en regelt de toegang ertoe. `OutputStream` bevat URI-gegevens die de locatie van de uitvoerstroom beschrijven.

```csharp
public class OutputStream : Stream
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | Initialiseert een nieuw exemplaar van het`OutputStream` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | Krijgt een waarde die aangeeft of de ingepakte uitvoerstroom lezen ondersteunt. |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | Krijgt een waarde die aangeeft of de verpakte uitvoerstroom zoeken ondersteunt. |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | Krijgt een waarde die aangeeft of de ingepakte uitvoerstroom schrijven ondersteunt. |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | Krijgt de lengte in bytes van de ingepakte uitvoerstroom. |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | Haalt of stelt de positie binnen de verpakte uitvoerstroom in. |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | Krijgt de URI van streamlocatie. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | Sluit de ingepakte uitvoerstroom en huidige stroom. |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | Wist alle buffers voor de ingepakte uitvoerstroom en zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | Leest een reeks bytes uit de ingepakte uitvoerstroom en schuift de positie binnen de stroom op met het aantal gelezen bytes. |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | Stelt de positie in binnen de verpakte uitvoerstroom. |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | Stelt de lengte van de ingepakte uitvoerstroom in. |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | Schrijft een reeks bytes naar de ingepakte output stream en verhoogt de huidige positie binnen deze stream met het aantal geschreven bytes. |

### Zie ook

* naamruimte [Aspose.Html.IO](../../aspose.html.io/)
* montage [Aspose.HTML](../../)


