---
title: MHTMLSaveOptions Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.MHTMLSaveOptions class. Represents MHTML save options. By assigning specific properties you can manage resource processing such as max handling depth and so on. More info see in documentation article
type: docs
weight: 4840
url: /java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Represents MHTML save options. By assigning specific properties you can manage resource processing such as max handling depth and so on. More info see in documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Gets a [`ResourceHandlingOptions`](../resourcehandlingoptions/) object which is used for configuration of resources handling. |

## Remarks

You can find complete examples and data files on [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Prepare HTML code with a link to another file and save it to the file as 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Prepare HTML code and save it to the file as 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Change the value of the resource linking depth to 1 in order to convert document with directly linked resources
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // Convert HTML to MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### See Also

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
