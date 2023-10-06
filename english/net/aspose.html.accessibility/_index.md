---
title: Aspose.Html.Accessibility
second_title: Aspose.HTML for .NET API Reference
description: The Aspose.Html.Dom.Accessibility namespace is for all Web Accessibility related manipulations. complies with international standards W3C Web Accessibility Initiative
type: docs
weight: 20
url: /net/aspose.html.accessibility/
---
The **Aspose.Html.Dom.Accessibility** namespace is for all Web Accessibility related manipulations. complies with international standards W3C Web Accessibility Initiative

## Classes

| Class | Description |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Quick reference to Web Content Accessibility Guidelines (WCAG) 2 requirements (success criteria) and techniques. Contain a list of Principle. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | The validator class handles quick reference rules. Contains a Validate method to check accessibility. |
| [Criterion](./criterion/) | Verifiable success criteria are provided for each recommendation, so WCAG 2.0 can be applied in areas where compliance testing is required. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Guidelines - the next level after principles. There are not testable, but outline frameworks and general goals that help authors understand success criteria and better apply the techniques. Guidelines are a list of acceptance criteria with type RuleDirectory/. |
| [Principle](./principle/) | Accessibility Principle - The highest levels that provide the foundation of web accessibility, contain a list of Guidelines with type RuleCollection/. The object is not allowed to be created outside the assembly. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Target](./target/) | Class contains item of html or css element where the error was found. |
| [ValidationBuilder](./validationbuilder/) | The ValidationBuilder class provides concrete implementations of the configuration steps. Defines methods and settings for a class ValidationSettings. |
| [WebAccessibility](./webaccessibility/) | Object to Web Content Accessibility Guidelines (WCAG) 2 requirements (success criteria) and techniques. https://www.w3.org/WAI/WCAG21/quickref/ |
## Interfaces

| Interface | Description |
| --- | --- |
| [IError](./ierror/) | The interface describes the error of the validation |
| [IRule](./irule/) | Interface describing the main properties of the rules. |
| [ITechniqueResult](./itechniqueresult/) | Describes the result of the technique validation. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [TargetTypes](./targettypes/) | Enum of types of the resulting object from the html document containing the error.. |
