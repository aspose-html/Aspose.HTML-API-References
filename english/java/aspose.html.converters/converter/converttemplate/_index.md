---
title: Converter.ConvertTemplate
second_title: Aspose.HTML for Java API Reference
description: Converter method. Merge template source presented by HTMLDocument with template data XML JSON. Result is html file formed by output file path
type: docs
weight: 60
url: /java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Merge template source presented by [`HTMLDocument`](../../../com.aspose.html/htmldocument/) with template data (XML, JSON). Result is html file formed by output file path.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| template | HTMLDocument | Merging source skeleton presented by [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form skeleton html source file path
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Form HTML document as conversion source
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Initiate conversion process
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Clear resources
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Merge template HTML source presented by [`URL`](../../../com.aspose.html/url/) with template data (XML, JSON). Result is html file formed by output file path.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Merging HTML source skeleton presented by [`URL`](../../../com.aspose.html/url/). |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form skeleton html source Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Merge template HTML source presented by [`URL`](../../../com.aspose.html/url/) with template data (XML, JSON). Result is html file formed by output file path.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Merging HTML source skeleton presented by [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form skeleton html source Url
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance 
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Merge template HTML source presented by full file path with template data (XML, JSON). Result is html file formed by output file path.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | Merging HTML source skeleton presented by full file path. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form skeleton html source file path
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Merge template HTML source presented by full file path with template data (XML, JSON). Result is html file formed by output file path.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | Merging HTML source skeleton presented by full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form skeleton html source file path
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process with default configuration
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Merge template HTML source presented by inline content with template data (XML, JSON). Result is html file formed by output file path.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | Merging HTML source skeleton presented by inline String content. |
| baseUrl | String | Base URI of the html template. It will be combined with the current directory path to form an absolute URL. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
	  // Form inline source content as template
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form output as merging result 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();
	  
      // Initiate conversion process
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### See Also

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Merge template HTML source presented by inline content with template data (XML, JSON). Result is html file formed by output file path.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | Merging HTML source skeleton presented by inline String content. |
| baseUrl | String | Base URI of the html template. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |
| outputPath | String | Full html file path as output conversion result. |

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
   // Form inline source content as template
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // Form xml (json) template data file path
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Define TemplateData object instance
   var templateData = new TemplateData(templateDataPath);

   // Form output as merging result 
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Define configuration object instance
   var configuration = new Configuration();

   // Define default TemplateLoadOptions object
   var options = new TemplateLoadOptions();

   // Initiate conversion process with default configuration
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Below is data file to merge with source as template

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### See Also

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Merge template source presented by [`HTMLDocument`](../../../com.aspose.html/htmldocument/) with template data (XML, JSON). Result is new formed HTMLDocument which can be saved as file.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| template | HTMLDocument | Merging source skeleton presented by [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form skeleton html source file path
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();
      
      // Form HTML document as conversion source
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Initiate conversion process
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Save result with linked resources
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Merge template HTML source presented by [`URL`](../../../com.aspose.html/url/) with template data (XML, JSON). Result is new formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved as file.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Merging HTML source skeleton presented by [`URL`](../../../com.aspose.html/url/). |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form Url to skeleton html source file
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Save result with linked resources
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Merge template HTML source presented by [`URL`](../../../com.aspose.html/url/) with template data (XML, JSON). Result is new formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved as file.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | Merging HTML source skeleton presented by [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form Url to skeleton html source file
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process with default configuration
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Save result with linked resources
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

Merge template HTML source presented by full file path with template data (XML, JSON). Result is new formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved as file.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | Merging HTML source skeleton presented by full file path. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form skeleton html source file path
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Save result with linked resources
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Merge template HTML source presented by full file path with template data (XML, JSON). Result is new formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved as file.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sourcePath | String | Merging HTML source skeleton presented by full file path. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form skeleton html source file path
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form result file path
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process with default configuration
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Save result with linked resources
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Merge template HTML source presented by inline content with template data (XML, JSON). Result is new formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved as file.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | Merging HTML source skeleton presented by inline String content. |
| baseUrl | String | Base URI of the html template. It will be combined with the current directory path to form an absolute URL. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form inline source content as template
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form output as merging result 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process and save result
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Merge template HTML source presented by inline content with template data (XML, JSON). Result is new formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) which can be saved as file.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | Merging HTML source skeleton presented by inline String content. |
| baseUrl | String | Base URI of the html template. It will be combined with the current directory path to form an absolute URL. |
| configuration | Configuration | The environment configuration. Represents the [`configuration`](../../../com.aspose.html/configuration/) context object that is used to set up the environment settings for the application. |
| data | TemplateData | Template data for merging - substitution (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) object instance. It used to determine whether the template and data item names match, regardless of case or not (options). |

### Return Value

New formed [`HTMLDocument`](../../../com.aspose.html/htmldocument/) as conversion result which can be saved through output file path.

## Remarks

Template Merger

The idea of template merging is to create an HTML document based on a html template and populate it from a data source. Aspose.HTML provides the inline expressions syntax to work with templates and various data source types, such as XML and JSON. Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) where you can find more info about template merging and using ConvertTemplate() method.

Conversion (Merging) steps

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Template source. Define HTML template source by file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) object instance or even by inline content.Conversion result. You can obtain directly resulting HTMLDocument or define result output file path depend of method signature.Create instance of [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/).Use the ConvertTemplate() method of the Converter class to merge template with data. You can add also [`configuration`](../../../com.aspose.html/configuration/) as option parameter.Source code

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import System.IO;
import com.aspose.html.IO;
import com.aspose.html.Saving;  
import com.aspose.html.Converters;  
...
      // Form inline source content as template
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Form xml (json) template data file path
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Define TemplateData object instance
      var templateData = new TemplateData(templateDataPath);

      // Form output as merging result 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Define configuration object instance
      var configuration = new Configuration();

      // Define default TemplateLoadOptions object
      var options = new TemplateLoadOptions();

      // Initiate conversion process and save result
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### See Also

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.Converters](../../converter/)
* package [Aspose.HTML](../../../)
