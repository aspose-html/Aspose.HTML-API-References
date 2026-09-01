---
title: "PdfPermissions Enum"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions enum. Deze enum vertegenwoordigt gebruikerspermissies voor een pdf"
type: docs

url: /nl/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Deze enum vertegenwoordigt de gebruikersrechten voor een pdf.

```java
[Flags]
public enum PdfPermissions
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| PrintDocument | `4` | (Beveiligingshandlers van revisie 2) Druk het document af. (Beveiligingshandlers van revisie 3 of hoger) Druk het document af (mogelijk niet op het hoogste kwaliteitsniveau, afhankelijk van of PrintingQuality ook is ingesteld). |
| ModifyContent | `8` | Wijzig de inhoud van het document door bewerkingen die niet worden beheerst door ModifyTextAnnotations, FillForm en 11. |
| ExtractContent | `10` | (Beveiligingshandlers van revisie 2) Kopieer of extraheer tekst en afbeeldingen uit het document, inclusief het extraheren van tekst en afbeeldingen (ter ondersteuning van toegankelijkheid voor gebruikers met een beperking of voor andere doeleinden). (Beveiligingshandlers van revisie 3 of hoger) Kopieer of extraheer tekst en afbeeldingen uit het document via bewerkingen die niet worden beheerst door ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Voeg tekstannotaties toe of wijzig ze, vul interactieve formuliervelden in, en, indien ModifyContent ook is ingesteld, maak of wijzig interactieve formuliervelden (inclusief handtekeningvelden). |
| FillForm | `100` | (Beveiligingshandlers van revisie 3 of hoger) Vul bestaande interactieve formuliervelden in (inclusief handtekeningvelden), zelfs als ModifyTextAnnotations is uitgeschakeld. |
| ExtractContentWithDisabilities | `200` | (Beveiligingshandlers van revisie 3 of hoger) Extraheer tekst en afbeeldingen (ter ondersteuning van toegankelijkheid voor gebruikers met een beperking of voor andere doeleinden). |
| AssembleDocument | `400` | (Beveiligingshandlers van revisie 3 of hoger) Stel het document samen (voeg pagina's in, roteer of verwijder ze en maak bladwijzers of miniatuurafbeeldingen), zelfs als ModifyContent is uitgeschakeld. |
| PrintingQuality | `800` | (Beveiligingshandlers van revisie 3 of hoger) Druk het document af naar een representatie waaruit een getrouwe digitale kopie van de PDF-inhoud kan worden gegenereerd. Wanneer dit bit is uitgeschakeld (en bit 3 is ingesteld), is afdrukken beperkt tot een laag-niveau representatie van het uiterlijk, mogelijk van verminderde kwaliteit. |

### Zie ook

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
