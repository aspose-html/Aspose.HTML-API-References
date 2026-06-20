---
title: "PdfPermissions Enum"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions Enum. Dieses Enum stellt die Benutzerberechtigungen für ein PDF dar."
type: docs

url: /de/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Dieses Enum stellt die Berechtigungen des Benutzers für ein PDF dar.

```java
[Flags]
public enum PdfPermissions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| PrintDocument | `4` | (Sicherheits-Handler der Revision 2) Dokument drucken. (Sicherheits-Handler der Revision 3 oder höher) Dokument drucken (möglicherweise nicht in höchster Qualitätsstufe, abhängig davon, ob PrintingQuality ebenfalls gesetzt ist). |
| ModifyContent | `8` | Den Inhalt des Dokuments durch Vorgänge ändern, die nicht von ModifyTextAnnotations, FillForm und 11 gesteuert werden. |
| ExtractContent | `10` | (Sicherheits-Handler der Revision 2) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren, einschließlich der Extraktion von Text und Grafiken (zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder zu anderen Zwecken). (Sicherheits-Handler der Revision 3 oder höher) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren durch Vorgänge, die nicht von ExtractContentWithDisabilities gesteuert werden. |
| ModifyTextAnnotations | `20` | Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, falls ModifyContent ebenfalls gesetzt ist, interaktive Formularfelder (einschließlich Signaturfelder) erstellen oder ändern. |
| FillForm | `100` | (Sicherheits-Handler der Revision 3 oder höher) Vorhandene interaktive Formularfelder ausfüllen (einschließlich Signaturfelder), selbst wenn ModifyTextAnnotations deaktiviert ist. |
| ExtractContentWithDisabilities | `200` | (Sicherheits-Handler der Revision 3 oder höher) Text und Grafiken extrahieren (zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder zu anderen Zwecken). |
| AssembleDocument | `400` | (Sicherheits-Handler der Revision 3 oder höher) Das Dokument zusammenstellen (Seiten einfügen, drehen oder löschen und Lesezeichen oder Miniaturbilder erstellen), selbst wenn ModifyContent deaktiviert ist. |
| PrintingQuality | `800` | (Sicherheits-Handler der Revision 3 oder höher) Das Dokument so drucken, dass daraus eine getreue digitale Kopie des PDF-Inhalts erzeugt werden kann. Wenn dieses Bit deaktiviert ist (und Bit 3 gesetzt ist), ist der Druck auf eine niedrigstufige Darstellung des Erscheinungsbildes beschränkt, möglicherweise von verminderter Qualität. |

### Siehe auch

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
