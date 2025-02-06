---
title: ValidationBuilder Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.accessibility.ValidationBuilder class. The ValidationBuilder class provides concrete implementations of the configuration steps. Defines methods and settings for a class ValidationSettings
type: docs
weight: 150
url: /java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

The ValidationBuilder class provides concrete implementations of the configuration steps. Defines methods and settings for a class ValidationSettings.

```java
public class ValidationBuilder
```

## Properties

| Name | Description |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) Includes all levels and all technologies settings |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) Default settings: only General technologies is used and for Lowest criterion level |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) None settings - none of the parameters are specified. |

## Methods

| Name | Description |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | A method that sets all criteria levels. And indicates that the document will be checked according to the criteria of all three levels. |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | A method that sets all technologies to test criterion |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | List of html tags to check If the tags are not specified explicitly, then the tags array is empty and the check passes through all |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | A method that includes CSS technologies in a set of rules |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | A method that includes Failures in a set of rules |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | A method that includes General technologies in a set of rules |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | Use Highest Level AAA of Criterion in Rules |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | A method that includes HTML technologies in a set of rules |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | Use Lowest Level A of Criterion in Rules |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | Use Middle Level AA of Criterion in Rules |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | A method that includes ClientSideScript technologies in a set of rules |

### See Also

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
