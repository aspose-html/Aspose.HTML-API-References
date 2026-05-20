---
title: "PdfPermissions Enum"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions enum. Denna enum representerar användarbehörigheter för en pdf"
type: docs

url: /sv/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Denna enum representerar användarens behörigheter för en PDF.

```java
[Flags]
public enum PdfPermissions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PrintDocument | `4` | (Security handlers of revision 2) Print the document. (Security handlers of revision 3 or greater) Print the document (possibly not at the highest quality level, depending on whether PrintingQuality is also set). |
| ModifyContent | `8` | Modifiera dokumentets innehåll genom operationer som inte styrs av ModifyTextAnnotations, FillForm och 11. |
| ExtractContent | `10` | Security handlers of revision 2) Kopiera eller på annat sätt extrahera text och grafik från dokumentet, inklusive extrahering av text och grafik (i stöd för tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål). (Security handlers of revision 3 or greater) Kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte styrs av ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Lägg till eller ändra textanteckningar, fyll i interaktiva formulärfält och, om ModifyContent också är aktiverat, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| FillForm | `100` | (Security handlers of revision 3 or greater) Fill in existing interactive form fields (including signature fields), even if ModifyTextAnnotations is clear. |
| ExtractContentWithDisabilities | `200` | (Security handlers of revision 3 or greater) Extract text and graphics (in support of accessibility to users with disabilities or for other purposes). |
| AssembleDocument | `400` | (Security handlers of revision 3 or greater) Assemble the document (insert, rotate, or delete pages and create bookmarks or thumbnail images), even if ModifyContent is clear. |
| PrintingQuality | `800` | (Security handlers of revision 3 or greater) Print the document to a representation from which a faithful digital copy of the PDF content could be generated. When this bit is clear (and bit 3 is set), printing is limited to a low-level representation of the appearance, possibly of degraded quality. |

### Se även

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
