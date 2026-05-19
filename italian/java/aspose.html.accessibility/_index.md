---
title: "com.aspose.html.accessibility"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Il pacchetto com.aspose.html.accessibility è destinato a tutte le manipolazioni relative all'accessibilità web. Conforma gli standard internazionali W3C Web Accessibility Initiative."
type: docs

url: /it/java/com.aspose.html.accessibility/
---
Il pacchetto **com.aspose.html.accessibility** è per tutte le manipolazioni relative all'Accessibilità Web. È conforme agli standard internazionali W3C Web Accessibility Initiative

## Classi

| Classe | Descrizione |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Riferimento rapido alle linee guida per l'accessibilità dei contenuti web (WCAG) 2, requisiti (criteri di successo) e tecniche. Contiene un elenco di Principi. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | La classe validator gestisce le regole di riferimento rapido. Contiene un metodo Validate per verificare l'accessibilità. |
| [Criterion](./criterion/) | Criteri di successo verificabili sono forniti per ogni raccomandazione, così WCAG 2.0 può essere applicato nelle aree in cui è necessario il test di conformità. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Linee guida - il livello successivo ai principi. Non sono verificabili, ma delineano framework e obiettivi generali che aiutano gli autori a comprendere i criteri di successo e a applicare meglio le tecniche. Le linee guida sono un elenco di criteri di accettazione con tipo RuleDirectory{Criterion}. |
| [Principle](./principle/) | Principio di accessibilità - I livelli più alti che forniscono la base dell'accessibilità web, contengono un elenco di linee guida con tipo RuleCollection{Guideline}. L'oggetto non può essere creato al di fuori dell'assembly. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Una classe astratta che definisce le caratteristiche di una Regola e implementa l'interfaccia IRule |
| [Target](./target/) | La classe contiene l'elemento html o css in cui è stato trovato l'errore. |
| [ValidationBuilder](./validationbuilder/) | La classe ValidationBuilder fornisce implementazioni concrete dei passaggi di configurazione. Definisce metodi e impostazioni per la classe ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Oggetto per le linee guida per l'accessibilità dei contenuti web (WCAG) 2, requisiti (criteri di successo) e tecniche. https://www.w3.org/WAI/WCAG21/quickref/ |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IError](./ierror/) | L'interfaccia descrive l'errore della convalida. |
| [IRule](./irule/) | Interfaccia che descrive le proprietà principali delle regole. |
| [ITechniqueResult](./itechniqueresult/) | Descrive il risultato della convalida della tecnica. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [TargetTypes](./targettypes/) | Enum dei tipi dell'oggetto risultante dal documento html contenente l'errore. |
