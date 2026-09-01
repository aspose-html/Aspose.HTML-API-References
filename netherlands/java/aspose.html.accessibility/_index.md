---
title: "com.aspose.html.accessibility"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Het com.aspose.html.accessibility-pakket is voor alle webtoegankelijkheidsgerelateerde manipulaties. Voldoet aan internationale normen van de W3C Web Accessibility Initiative."
type: docs

url: /nl/java/com.aspose.html.accessibility/
---
Het **com.aspose.html.accessibility**-pakket is bedoeld voor alle Web Accessibility-gerelateerde manipulaties en voldoet aan de internationale normen van de W3C Web Accessibility Initiative.

## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Snelle referentie naar de Web Content Accessibility Guidelines (WCAG) 2 vereisten (succescriteria) en technieken. Bevat een lijst van principes. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | De validatorklasse behandelt snelle referentieregels. Bevat een Validate-methode om toegankelijkheid te controleren. |
| [Criterion](./criterion/) | Verifieerbare succescriteria worden verstrekt voor elke aanbeveling, zodat WCAG 2.0 kan worden toegepast in gebieden waar compliance-testing vereist is. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Richtlijnen - het volgende niveau na principes. Ze zijn niet testbaar, maar schetsen kaders en algemene doelen die auteurs helpen de succescriteria te begrijpen en de technieken beter toe te passen. Richtlijnen zijn een lijst van acceptatiecriteria met type RuleDirectory{Criterion}. |
| [Principle](./principle/) | Toegankelijkheidsprincipe - De hoogste niveaus die de basis vormen van webtoegankelijkheid, bevatten een lijst van richtlijnen met type RuleCollection{Guideline}. Het object mag niet buiten de assembly worden aangemaakt. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Een abstracte klasse die de kenmerken van een Rule definieert en de interface IRule implementeert. |
| [Target](./target/) | Klasse bevat een item van een html- of css-element waar de fout is gevonden. |
| [ValidationBuilder](./validationbuilder/) | De ValidationBuilder-klasse biedt concrete implementaties van de configuratiestappen. Definieert methoden en instellingen voor de klasse ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Object naar Web Content Accessibility Guidelines (WCAG) 2 vereisten (succescriteria) en technieken. https://www.w3.org/WAI/WCAG21/quickref/ |
## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [IError](./ierror/) | De interface beschrijft de fout van de validatie. |
| [IRule](./irule/) | Interface die de belangrijkste eigenschappen van de regels beschrijft. |
| [ITechniqueResult](./itechniqueresult/) | Beschrijft het resultaat van de validatie van de techniek. |
## Enumeratie

| Enumeratie | Beschrijving |
| --- | --- |
| [TargetTypes](./targettypes/) | Enumeratie van typen van het resulterende object uit het html-document dat de fout bevat.. |
