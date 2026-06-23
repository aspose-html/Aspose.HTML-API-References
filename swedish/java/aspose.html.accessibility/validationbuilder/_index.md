---
title: "ValidationBuilder klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.accessibility.ValidationBuilder klass. ValidationBuilder-klassen tillhandahåller konkreta implementationer av konfigurationsstegen. Definierar metoder och inställningar för en klass ValidationSettings"
type: docs

url: /sv/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

Klassen ValidationBuilder tillhandahåller konkreta implementationer av konfigurationsstegen. Definierar metoder och inställningar för klassen ValidationSettings.

```java
public class ValidationBuilder
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) Inkluderar alla nivåer och alla teknologiers inställningar |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) Standardinställningar: endast General-teknologier används och för lägsta kriterienivå |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) Inga inställningar – inga av parametrarna är specificerade. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | En metod som sätter alla kriterienivåer. Och indikerar att dokumentet kommer att kontrolleras enligt kriterierna för alla tre nivåer. |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | En metod som sätter alla teknologier för testkriteriet |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | Lista över html-taggar att kontrollera. Om taggarna inte specificeras explicit, är taggarrayen tom och kontrollen går igenom alla. |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | En metod som inkluderar CSS-teknologier i en uppsättning regler |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | En metod som inkluderar Fel i en uppsättning regler |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | En metod som inkluderar General-teknologier i en uppsättning regler |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Använd högsta nivå AAA av kriteriet i regler |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | En metod som inkluderar HTML-teknologier i en uppsättning regler |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Använd lägsta nivå A av kriteriet i regler |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Använd mellannivå AA av kriteriet i regler |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | En metod som inkluderar ClientSideScript-teknologier i en uppsättning regler |

### Se även

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
