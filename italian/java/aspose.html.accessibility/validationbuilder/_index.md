---
title: "Classe ValidationBuilder"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.accessibility.ValidationBuilder. La classe ValidationBuilder fornisce implementazioni concrete dei passaggi di configurazione. Definisce metodi e impostazioni per una classe ValidationSettings"
type: docs

url: /it/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

La classe ValidationBuilder fornisce implementazioni concrete dei passaggi di configurazione. Definisce metodi e impostazioni per la classe ValidationSettings.

```java
public class ValidationBuilder
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) Include tutti i livelli e tutte le impostazioni delle tecnologie |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) Impostazioni predefinite: solo le tecnologie Generali sono utilizzate e per il livello di criterio più basso |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) Nessuna impostazione - nessuno dei parametri è specificato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | Un metodo che imposta tutti i livelli di criteri. E indica che il documento sarà verificato secondo i criteri di tutti e tre i livelli. |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | Un metodo che imposta tutte le tecnologie per testare il criterio |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | Elenco dei tag html da controllare. Se i tag non sono specificati esplicitamente, l'array dei tag è vuoto e il controllo passa attraverso tutti. |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | Un metodo che include le tecnologie CSS in un insieme di regole |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | Un metodo che include i Fallimenti in un insieme di regole |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | Un metodo che include le tecnologie Generali in un insieme di regole |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Usa il livello più alto AAA del criterio nelle regole |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | Un metodo che include le tecnologie HTML in un insieme di regole |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Usa il livello più basso A del criterio nelle regole |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Usa il livello medio AA del criterio nelle regole |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | Un metodo che include le tecnologie ClientSideScript in un insieme di regole |

### Vedi anche

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
