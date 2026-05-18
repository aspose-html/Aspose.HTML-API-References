---
title: "PdfPermissions Enum"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions enum. Dieses Enum repräsentiert die Benutzerberechtigungen für ein PDF."
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
| PrintDocument | `4` | (Security handlers of revision 2) Dokument drucken. (Security handlers of revision 3 or greater) Dokument drucken (möglicherweise nicht in höchster Qualität, abhängig davon, ob PrintingQuality ebenfalls gesetzt ist). |
| ModifyContent | `8` | Den Inhalt des Dokuments durch Vorgänge ändern, die nicht von ModifyTextAnnotations, FillForm und 11 gesteuert werden. |
| ExtractContent | `10` | Security handlers of revision 2) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren, einschließlich des Extrahierens von Text und Grafiken (zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder zu anderen Zwecken). (Security handlers of revision 3 or greater) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren durch Vorgänge, die nicht von ExtractContentWithDisabilities gesteuert werden. |
| ModifyTextAnnotations | `20` | Textanmerkungen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, wenn ModifyContent ebenfalls gesetzt ist, interaktive Formularfelder (einschließlich Signaturfelder) erstellen oder ändern. |
| FillForm | `100` | (Security handlers of revision 3 or greater) Vorhandene interaktive Formularfelder ausfüllen (einschließlich Signaturfelder), selbst wenn ModifyTextAnnotations nicht gesetzt ist. |
| ExtractContentWithDisabilities | `200` | (Security handlers of revision 3 or greater) Text und Grafiken extrahieren (zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen oder zu anderen Zwecken). |
| AssembleDocument | `400` | (Security handlers of revision 3 or greater) Das Dokument zusammenstellen (Seiten einfügen, drehen oder löschen und Lesezeichen oder Miniaturbilder erstellen), selbst wenn ModifyContent nicht gesetzt ist. |
| PrintingQuality | `800` | (Security handlers of revision 3 or greater) Das Dokument zu einer Darstellung drucken, aus der eine getreue digitale Kopie des PDF-Inhalts erzeugt werden kann. Wenn dieses Bit nicht gesetzt ist (und Bit 3 gesetzt ist), ist das Drucken auf eine niedrigstufige Darstellung des Erscheinungsbildes beschränkt, möglicherweise von verminderter Qualität. |

### Siehe auch

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
