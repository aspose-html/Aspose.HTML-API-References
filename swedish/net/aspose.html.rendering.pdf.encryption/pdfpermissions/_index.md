---
title: Enum PdfPermissions
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions uppräkning. Denna uppräkning representerar användarens behörigheter för en pdf.
type: docs
weight: 4420
url: /sv/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Denna uppräkning representerar användarens behörigheter för en pdf.

```csharp
[Flags]
public enum PdfPermissions
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| PrintDocument | `4` | (Säkerhetshanterare av revision 2) Skriv ut dokumentet. (Säkerhetshanterare av version 3 eller högre) Skriv ut dokumentet (möjligen inte på högsta kvalitetsnivå, beroende på om PrintingQuality också är inställd). |
| ModifyContent | `8` | Ändra innehållet i dokumentet med andra operationer än de som kontrolleras av ModifyTextAnnotations, FillForm och 11. |
| ExtractContent | `10` | Säkerhetshanterare för revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive extrahering av text och grafik (till stöd för tillgänglighet för användare med funktionsnedsättning eller för andra ändamål). (Säkerhetshanterare av version 3 eller högre) Kopia eller på annat sätt extrahera text och grafik från dokumentet genom andra operationer än de som kontrolleras av ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Lägg till eller ändra textkommentarer, fyll i interaktiva formulärfält och, om ModifyContent också är inställt, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| FillForm | `100` | (Säkerhetshanterare av version 3 eller senare) Fyll i befintliga interaktiva formulärfält (inklusive signaturfält), även om ModifyTextAnnotations är tydligt. |
| ExtractContentWithDisabilities | `200` | (Säkerhetshanterare av version 3 eller senare) Extrahera text och grafik (till stöd för tillgänglighet för användare med funktionshinder eller för andra ändamål). |
| AssembleDocument | `400` | (Säkerhetshanterare av version 3 eller senare) Sätt ihop dokumentet (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder), även om ModifyContent är tydligt. |
| PrintingQuality | `800` | (Säkerhetshanterare av version 3 eller högre) Skriv ut dokumentet till en representation från vilken en trogen digital kopia av PDF-innehållet kan genereras. När denna bit är klar (och bit 3 är inställd) begränsas utskriften till en låg -nivårepresentation av utseendet, möjligen av försämrad kvalitet. |

### Se även

* namnutrymme [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* hopsättning [Aspose.HTML](../../)


