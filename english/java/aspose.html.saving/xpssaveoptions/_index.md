---
title: XpsSaveOptions Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.XpsSaveOptions class. Specific options data class provides few properties to manage conversion result. For example PageSetup specifies page characteristics. Refer to documentation article
type: docs
weight: 4730
url: /java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Specific options data class provides few properties to manage conversion result. For example [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specifies page characteristics. Refer to documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gets a [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
[getHorizontalResolution]
[setHorizontalResolution] Sets or gets horizontal resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gets a page setup object is used for configuration output page-set. |
[getVerticalResolution]
[setVerticalResolution] Sets or gets vertical resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

## Remarks

You can find complete examples and data files on [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import com.aspose.html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Prepare HTML code and save it to a file
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Initialize an HTML Document from the html file
      using var document = new HTMLDocument(documentPath);
       
      // Set up the page-size, margins and change the background color to AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Convert HTML to XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### See Also

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
