---
title: aspose.html.accessibility
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/aspose.html.accessibility/
is_root: false
---

The **Aspose.Html.Accessibility**  namespace is for all Web Accessibility related manipulations.
complies with international standards W3C Web Accessibility Initiative

### Classes
| Class | Description |
| :- | :- |
| [`AccessibilityRules`](/html/python-net/aspose.html.accessibility/accessibilityrules) | Quick reference to Web Content Accessibility Guidelines (WCAG) 2 requirements (success criteria) and techniques.<br/>Contain a list of Principle.  <br/><br/>https://www.w3.org/WAI/WCAG21/quickref/ |
| [`AccessibilityValidator`](/html/python-net/aspose.html.accessibility/accessibilityvalidator) | The validator class handles quick reference rules. Contains a Validate method to check accessibility. |
| [`Criterion`](/html/python-net/aspose.html.accessibility/criterion) | Verifiable success criteria are provided for each recommendation, so WCAG 2.0 can be applied in areas where compliance testing is required.<br/><br/>https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [`Guideline`](/html/python-net/aspose.html.accessibility/guideline) | Guidelines - the next level after principles. <br/>There are not testable, but outline frameworks and general goals that help authors understand success criteria and better apply the techniques.<br/><br/>Guidelines are a list of acceptance criteria with type RuleDirectory{Criterion}. |
| [`IError`](/html/python-net/aspose.html.accessibility/ierror) | The interface describes the error of the validation |
| [`IRule`](/html/python-net/aspose.html.accessibility/irule) | Interface describing the main properties of the rules. |
| [`ITechniqueResult`](/html/python-net/aspose.html.accessibility/itechniqueresult) | Describes the result of the technique validation. |
| [`Principle`](/html/python-net/aspose.html.accessibility/principle) | Accessibility Principle - The highest levels that provide the foundation of web accessibility, contain a list of Guidelines with type RuleCollection{Guideline}.<br/>The object is not allowed to be created outside the assembly.<br/><br/>https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [`Rule`](/html/python-net/aspose.html.accessibility/rule) | An abstract class that defines the characteristics of a Rule and implements interface IRule |
| [`Target`](/html/python-net/aspose.html.accessibility/target) | Class contains item of html or css element where the error was found. |
| [`ValidationBuilder`](/html/python-net/aspose.html.accessibility/validationbuilder) | The ValidationBuilder class provides concrete implementations of the configuration steps.<br/>Defines methods and settings for a class ValidationSettings. |
| [`WebAccessibility`](/html/python-net/aspose.html.accessibility/webaccessibility) | Object to Web Content Accessibility Guidelines (WCAG) 2 requirements (success criteria) and techniques. <br/>https://www.w3.org/WAI/WCAG21/quickref/ |


### Enumerations
| Enumeration | Description |
| :- | :- |
| [`TargetTypes`](/html/python-net/aspose.html.accessibility/targettypes) | Enum of types of the resulting object from the html document containing the error.. |


