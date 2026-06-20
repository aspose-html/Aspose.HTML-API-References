---
title: "com.aspose.html.accessibility"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Le package com.aspose.html.accessibility est destiné à toutes les manipulations liées à l'accessibilité Web. Il est conforme aux normes internationales de la W3C Web Accessibility Initiative."
type: docs

url: /fr/java/com.aspose.html.accessibility/
---
Le package **com.aspose.html.accessibility** est destiné à toutes les manipulations liées à l'accessibilité Web. Il est conforme aux normes internationales de l'Initiative d'accessibilité Web du W3C.

## Classes

| Classe | Description |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Référence rapide aux exigences (critères de succès) et techniques des Web Content Accessibility Guidelines (WCAG) 2. Contient une liste de principes. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | La classe validator gère les règles de référence rapide. Contient une méthode Validate pour vérifier l'accessibilité. |
| [Criterion](./criterion/) | Des critères de succès vérifiables sont fournis pour chaque recommandation, afin que la WCAG 2.0 puisse être appliquée dans les zones où des tests de conformité sont requis. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Directives - le niveau suivant après les principes. Elles ne sont pas testables, mais définissent des cadres et des objectifs généraux qui aident les auteurs à comprendre les critères de succès et à mieux appliquer les techniques. Les directives sont une liste de critères d'acceptation avec le type RuleDirectory{Criterion}. |
| [Principle](./principle/) | Principe d'accessibilité - Les niveaux les plus élevés qui constituent la base de l'accessibilité Web, contenant une liste de Directives avec le type RuleCollection{Guideline}. L'objet ne peut pas être créé en dehors de l'assembly. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Une classe abstraite qui définit les caractéristiques d'une Rule et implémente l'interface IRule. |
| [Target](./target/) | La classe contient l'élément HTML ou CSS où l'erreur a été trouvée. |
| [ValidationBuilder](./validationbuilder/) | La classe ValidationBuilder fournit des implémentations concrètes des étapes de configuration. Définit les méthodes et les paramètres pour la classe ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Objet aux exigences (critères de succès) et techniques des Web Content Accessibility Guidelines (WCAG) 2. https://www.w3.org/WAI/WCAG21/quickref/ |
## Interfaces

| Interface | Description |
| --- | --- |
| [IError](./ierror/) | L'interface décrit l'erreur de la validation. |
| [IRule](./irule/) | Interface décrivant les principales propriétés des règles. |
| [ITechniqueResult](./itechniqueresult/) | Décrit le résultat de la validation de la technique. |
## Énumération

| Énumération | Description |
| --- | --- |
| [TargetTypes](./targettypes/) | Énumération des types de l'objet résultant du document HTML contenant l'erreur. |
