---
title: "ValidationBuilder Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.accessibility.ValidationBuilder Klasse. Die ValidationBuilder-Klasse bietet konkrete Implementierungen der Konfigurationsschritte. Definiert Methoden und Einstellungen für die Klasse ValidationSettings"
type: docs

url: /de/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

Die ValidationBuilder‑Klasse liefert konkrete Implementierungen der Konfigurationsschritte. Definiert Methoden und Einstellungen für die Klasse ValidationSettings.

```java
public class ValidationBuilder
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) Enthält alle Ebenen und alle Technologieeinstellungen |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) Standard-Einstellungen: Es werden nur allgemeine Technologien verwendet und das niedrigste Kriteriumsniveau |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) Keine Einstellungen – es sind keine Parameter angegeben. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | Eine Methode, die alle Kriterienstufen festlegt. Und anzeigt, dass das Dokument gemäß den Kriterien aller drei Stufen geprüft wird. |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | Eine Methode, die alle Technologien für das Testkriterium festlegt |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | Liste der zu prüfenden HTML-Tags. Wenn die Tags nicht explizit angegeben sind, ist das Tag-Array leer und die Prüfung erfolgt über alle. |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | Eine Methode, die CSS-Technologien in einen Regel‑Satz einschließt |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | Eine Methode, die Fehler in einen Regel‑Satz einschließt |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | Eine Methode, die allgemeine Technologien in einen Regel‑Satz einschließt |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Verwende das höchste Niveau AAA des Kriteriums in den Regeln |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | Eine Methode, die HTML-Technologien in einen Regel‑Satz einschließt |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Verwende das niedrigste Niveau A des Kriteriums in den Regeln |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Verwende das mittlere Niveau AA des Kriteriums in den Regeln |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | Eine Methode, die ClientSideScript-Technologien in einen Regel‑Satz einschließt |

### Siehe auch

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
