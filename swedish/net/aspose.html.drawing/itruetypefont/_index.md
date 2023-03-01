---
title: Interface ITrueTypeFont
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Drawing.ITrueTypeFont gränssnitt. Deklarerar metoder för att arbeta med TrueTypeteckensnitt.
type: docs
weight: 2760
url: /sv/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Deklarerar metoder för att arbeta med TrueType-teckensnitt.

```csharp
public interface ITrueTypeFont
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | Returnerar storleken på teckensnittsdata i bytes |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | Hämta namnet på teckensnittsfamiljen. |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | Detta bör vara en kombination av "FamilyName" och "SubFamilyName". Undantag: om teckensnittet är "Regular" som anges i "SubFamilyName", använd endast efternamnet i "FamilyName". Ett undantag från definitionen ovan av Fullständigt teckensnittsnamn är för Microsoft-plattformssträngar för CFF OpenType-teckensnitt: i det här fallet måste strängen Fullständigt teckensnittsnamn vara identisk med PostScript FontName i CFF Name INDEX. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | Teckensnittets underfamiljsnamn särskiljer teckensnittet i en grupp med samma teckensnittsfamiljsnamn. Detta antas ta upp stil (kursiv, snett) och vikt (lätt, fet, svart, etc.). Ett teckensnitt utan speciella skillnader i vikt eller stil (t.ex. medelvikt, inte kursiv och fsSelection bit 6 set) bör ha strängen "Regular" lagrad i denna position. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | Returnerar stigningen i poäng. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | Öppna flödet med teckensnittsdata. Den som ringer är ansvarig för att slänga strömmen. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | Returnerar nedstigningen i poäng. |

### Se även

* namnutrymme [Aspose.Html.Drawing](../../aspose.html.drawing/)
* hopsättning [Aspose.HTML](../../)


