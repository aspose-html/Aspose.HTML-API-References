---
title: ValidationBuilder Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Accessibility.ValidationBuilder class. The ValidationBuilder class provides concrete implementations of the configuration steps. Defines methods and settings for a class ValidationSettings
type: docs
weight: 150
url: /net/aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

The ValidationBuilder class provides concrete implementations of the configuration steps. Defines methods and settings for a class ValidationSettings.

```csharp
public class ValidationBuilder
```

## Public Members
## Properties

| Name | Description |
| --- | --- |
| static [All](../../aspose.html.accessibility/validationbuilder/all/) { get; } | Includes all levels and all technologies settings |
| static [Default](../../aspose.html.accessibility/validationbuilder/default/) { get; } | Default settings: only General technologies is used and for Lowest criterion level |
| static [None](../../aspose.html.accessibility/validationbuilder/none/) { get; } | None settings - none of the parameters are specified. |

## Public Members
## Methods

| Name | Description |
| --- | --- |
| [AllLevels](../../aspose.html.accessibility/validationbuilder/alllevels/)() | A method that sets all criteria levels. And indicates that the document will be checked according to the criteria of all three levels. |
| [AllTechnologies](../../aspose.html.accessibility/validationbuilder/alltechnologies/)() | A method that sets all technologies to test criterion |
| [SetHTMLTags](../../aspose.html.accessibility/validationbuilder/sethtmltags/)(*params string[]*) | List of html tags to check If the tags are not specified explicitly, then the tags array is empty and the check passes through all |
| [UseCSS](../../aspose.html.accessibility/validationbuilder/usecss/)() | A method that includes CSS technologies in a set of rules |
| [UseFailures](../../aspose.html.accessibility/validationbuilder/usefailures/)() | A method that includes Failures in a set of rules |
| [UseGeneral](../../aspose.html.accessibility/validationbuilder/usegeneral/)() | A method that includes General technologies in a set of rules |
| [UseHighestLevel](../../aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Use Highest Level AAA of Criterion in Rules |
| [UseHTML](../../aspose.html.accessibility/validationbuilder/usehtml/)() | A method that includes HTML technologies in a set of rules |
| [UseLowestLevel](../../aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Use Lowest Level A of Criterion in Rules |
| [UseMiddleLevel](../../aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Use Middle Level AA of Criterion in Rules |
| [UseScript](../../aspose.html.accessibility/validationbuilder/usescript/)() | A method that includes ClientSideScript technologies in a set of rules |

### See Also

* namespace [Aspose.Html.Accessibility](../../aspose.html.accessibility/)
* assembly [Aspose.HTML](../../)
