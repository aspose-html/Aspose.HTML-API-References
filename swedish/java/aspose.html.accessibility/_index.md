---
title: "com.aspose.html.accessibility"
second_title: "Aspose.HTML för Java API-referens"
description: "Paketet com.aspose.html.accessibility är för alla webbtillgänglighetsrelaterade manipulationer. Följer internationella standarder från W3C Web Accessibility Initiative"
type: docs

url: /sv/java/com.aspose.html.accessibility/
---
Paketet **com.aspose.html.accessibility** är avsett för all webbåtkomlighet relaterad manipulation. Följer de internationella standarderna W3C Web Accessibility Initiative.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Snabbreferens till Web Content Accessibility Guidelines (WCAG) 2-krav (framgångskriterier) och tekniker. Innehåller en lista över principer. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | Validator-klassen hanterar snabbreferensregler. Innehåller en Validate-metod för att kontrollera tillgänglighet. |
| [Criterion](./criterion/) | Verifierbara framgångskriterier tillhandahålls för varje rekommendation, så att WCAG 2.0 kan tillämpas i områden där efterlevnadstestning krävs. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Riktlinjer – nästa nivå efter principer. De är inte testbara, men beskriver ramverk och allmänna mål som hjälper författare att förstå framgångskriterier och bättre tillämpa teknikerna. Riktlinjer är en lista över accepteringskriterier med typen RuleDirectory{Criterion}. |
| [Principle](./principle/) | Tillgänglighetsprincip – De högsta nivåerna som utgör grunden för webbtillgänglighet, innehåller en lista över riktlinjer med typen RuleCollection{Guideline}. Objektet får inte skapas utanför samlingen. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | En abstrakt klass som definierar egenskaperna för en Rule och implementerar gränssnittet IRule |
| [Target](./target/) | Klassen innehåller ett objekt av ett html- eller css-element där felet hittades. |
| [ValidationBuilder](./validationbuilder/) | Klassen ValidationBuilder tillhandahåller konkreta implementationer av konfigurationsstegen. Definierar metoder och inställningar för klassen ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Objekt till Web Content Accessibility Guidelines (WCAG) 2-krav (framgångskriterier) och tekniker. https://www.w3.org/WAI/WCAG21/quickref/ |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IError](./ierror/) | Gränssnittet beskriver valideringsfelet |
| [IRule](./irule/) | Gränssnitt som beskriver huvudegenskaperna för reglerna. |
| [ITechniqueResult](./itechniqueresult/) | Beskriver resultatet av teknikkontrollen. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [TargetTypes](./targettypes/) | Enum för typer av det resulterande objektet från HTML-dokumentet som innehåller felet. |
