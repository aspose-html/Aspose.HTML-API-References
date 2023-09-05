---
title: ValidationBuilder Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Accessibility.ValidationBuilder class. The ValidationBuilder class provides concrete implementations of the configuration steps. Defines methods and settings for a class ValidationSettings
type: docs
weight: 130
url: /net/aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

The ValidationBuilder class provides concrete implementations of the configuration steps. Defines methods and settings for a class ValidationSettings.

```csharp
public class ValidationBuilder
```

## Methods

| Name | Description |
| --- | --- |
| [AllLevels](../../aspose.html.accessibility/validationbuilder/alllevels/)() | Method that sets all criteria levels |
| [AllTechnologies](../../aspose.html.accessibility/validationbuilder/alltechnologies/)() | A method that sets all technologies to test criterion |
| [SetHTMLTags](../../aspose.html.accessibility/validationbuilder/sethtmltags/)(params string[]) | List of html tags to check If the tags are not specified explicitly, then the tags array is empty and the check passes through all |
| [UseCSS](../../aspose.html.accessibility/validationbuilder/usecss/)() | A method that includes CSS technologies in a set of rules |
| [UseFailures](../../aspose.html.accessibility/validationbuilder/usefailures/)() | A method that includes Failures in a set of rules |
| [UseGeneral](../../aspose.html.accessibility/validationbuilder/usegeneral/)() | A method that includes General technologies in a set of rules |
| [UseHighestLevel](../../aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Use Highest Level AAA of Criterion in Rules |
| [UseHTML](../../aspose.html.accessibility/validationbuilder/usehtml/)() | A method that includes HTML technologies in a set of rules |
| [UseLowestLevel](../../aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Use Lowest Level A of Criterion in Rules |
| [UseMiddleLevel](../../aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Use Middle Level AA of Criterion in Rules |
| [UseScript](../../aspose.html.accessibility/validationbuilder/usescript/)() | A method that includes ClientSideScript technologies in a set of rules |

## Fields

| Name | Description |
| --- | --- |
| static readonly [All](../../aspose.html.accessibility/validationbuilder/all/) | Includes all levels and all technologies settings |
| static readonly [Default](../../aspose.html.accessibility/validationbuilder/default/) | Default settings: only General technologies and Failures are used The array of levels is empty and the check goes through all levels |
| static readonly [None](../../aspose.html.accessibility/validationbuilder/none/) | None settings - none of the parameters are specified. The array of levels is empty and the check goes through all levels. |

### See Also

* namespace [Aspose.Html.Accessibility](../../aspose.html.accessibility/)
* assembly [Aspose.HTML](../../)
