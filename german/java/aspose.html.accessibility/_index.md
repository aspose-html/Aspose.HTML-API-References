---
title: "com.aspose.html.accessibility"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Das Paket com.aspose.html.accessibility dient allen webbezogenen Barrierefreiheits‑Manipulationen. Es entspricht den internationalen Standards der W3C Web Accessibility Initiative."
type: docs

url: /de/java/com.aspose.html.accessibility/
---
Das **com.aspose.html.accessibility**-Paket dient allen Web‑Accessibility‑bezogenen Manipulationen und entspricht den internationalen Standards der W3C Web Accessibility Initiative.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Kurzreferenz zu den Web Content Accessibility Guidelines (WCAG) 2 Anforderungen (Erfolgskriterien) und Techniken. Enthält eine Liste von Prinzipien. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | Die Validator‑Klasse verarbeitet Kurzreferenzregeln. Sie enthält eine Validate‑Methode, um die Barrierefreiheit zu prüfen. |
| [Criterion](./criterion/) | Verifizierbare Erfolgskriterien werden für jede Empfehlung bereitgestellt, sodass WCAG 2.0 in Bereichen angewendet werden kann, in denen Konformitätstests erforderlich sind. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Richtlinien – die nächste Ebene nach den Prinzipien. Sie sind nicht testbar, sondern skizzieren Rahmenwerke und allgemeine Ziele, die Autoren helfen, Erfolgskriterien zu verstehen und die Techniken besser anzuwenden. Richtlinien sind eine Liste von Akzeptanzkriterien vom Typ RuleDirectory{Criterion}. |
| [Principle](./principle/) | Barrierefreiheitsprinzip – die höchsten Ebenen, die die Grundlage der Web‑Barrierefreiheit bilden, enthalten eine Liste von Richtlinien vom Typ RuleCollection{Guideline}. Das Objekt darf nicht außerhalb der Assembly erstellt werden. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Eine abstrakte Klasse, die die Merkmale einer Regel definiert und das Interface IRule implementiert. |
| [Target](./target/) | Klasse enthält das Element von HTML oder CSS, in dem der Fehler gefunden wurde. |
| [ValidationBuilder](./validationbuilder/) | Die ValidationBuilder‑Klasse liefert konkrete Implementierungen der Konfigurationsschritte. Definiert Methoden und Einstellungen für die Klasse ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Objekt zu den Web Content Accessibility Guidelines (WCAG) 2 Anforderungen (Erfolgskriterien) und Techniken. https://www.w3.org/WAI/WCAG21/quickref/ |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IError](./ierror/) | Das Interface beschreibt den Validierungsfehler. |
| [IRule](./irule/) | Schnittstelle, die die Haupteigenschaften der Regeln beschreibt. |
| [ITechniqueResult](./itechniqueresult/) | Beschreibt das Ergebnis der Technikvalidierung. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [TargetTypes](./targettypes/) | Aufzählung der Typen des resultierenden Objekts aus dem HTML-Dokument, das den Fehler enthält. |
