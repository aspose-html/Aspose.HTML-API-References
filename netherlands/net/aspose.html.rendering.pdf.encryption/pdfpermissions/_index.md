---
title: Enum PdfPermissions
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions opsomming. Deze opsomming vertegenwoordigt de machtigingen van de gebruiker voor een pdf.
type: docs
weight: 4420
url: /nl/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Deze opsomming vertegenwoordigt de machtigingen van de gebruiker voor een pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| PrintDocument | `4` | (Beveiligingshandlers van revisie 2) Druk het document af. (Beveiligingshandlers van revisie 3 of hoger) Druk het document af (mogelijk niet op het hoogste kwaliteitsniveau, afhankelijk van of ook PrintingQuality is ingesteld). |
| ModifyContent | `8` | Wijzig de inhoud van het document met andere bewerkingen dan die worden beheerd door ModifyTextAnnotations, FillForm en 11. |
| ExtractContent | `10` | Beveiligingshandlers van revisie 2) Kopieer of extraheer tekst en afbeeldingen uit het document, inclusief het extraheren van tekst en afbeeldingen (ter ondersteuning van toegankelijkheid voor gebruikers met een handicap of voor andere doeleinden). (Beveiligingshandlers van revisie 3 of hoger) Kopiëren of op een andere manier tekst en afbeeldingen uit het document extraheren met andere bewerkingen dan die worden beheerd door ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Voeg tekstannotaties toe of wijzig ze, vul interactieve formuliervelden in en, als ModifyContent ook is ingesteld, maak of wijzig interactieve formuliervelden (inclusief handtekeningvelden). |
| FillForm | `100` | (Beveiligingshandlers van revisie 3 of hoger) Vul bestaande interactieve formuliervelden in (inclusief handtekeningvelden), zelfs als ModifyTextAnnotations duidelijk is. |
| ExtractContentWithDisabilities | `200` | (Beveiligingshandlers van revisie 3 of hoger) Extraheer tekst en afbeeldingen (ter ondersteuning van toegankelijkheid voor gebruikers met een handicap of voor andere doeleinden). |
| AssembleDocument | `400` | (Beveiligingshandlers van revisie 3 of hoger) Stel het document samen (pagina's invoegen, roteren of verwijderen en bladwijzers of miniatuurafbeeldingen maken), zelfs als ModifyContent duidelijk is. |
| PrintingQuality | `800` | (Beveiligingshandlers van revisie 3 of hoger) Druk het document af naar een weergave waaruit een getrouwe digitale kopie van de PDF-inhoud kan worden gegenereerd. Wanneer dit bit vrij is (en bit 3 is ingesteld), is afdrukken beperkt tot een laag weergave op -niveau van het uiterlijk, mogelijk van verminderde kwaliteit. |

### Zie ook

* naamruimte [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* montage [Aspose.HTML](../../)


