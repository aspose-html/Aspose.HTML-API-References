---
title: "Converter.ConvertTemplate"
second_title: "Aspose.HTML for Java API 参考"
description: "Converter 方法。将通过 HTMLDocument 提供的模板源与模板数据 XML JSON 合并。结果是由输出文件路径生成的 html 文件。"
type: docs

url: /zh/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

将通过 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的模板源与模板数据 (XML, JSON) 合并。结果是由输出文件路径生成的 html 文件。

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| template | HTMLDocument | 合并由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的源骨架。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单骨架 HTML 源文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 将表单 HTML 文档设为转换来源
      var document = new HTMLDocument(sourcePath, new Configuration());

      // 启动转换过程
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // 清除资源
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

合并由 [`URL`](../../../com.aspose.html/url/) 提供的模板 HTML 源与模板数据（XML，JSON）。结果为由输出文件路径生成的 HTML 文件。

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 合并由 [`URL`](../../../com.aspose.html/url/) 提供的 HTML 源骨架。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单骨架 HTML 源 URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 启动转换过程
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

合并由 [`URL`](../../../com.aspose.html/url/) 提供的模板 HTML 源与模板数据（XML，JSON）。结果为由输出文件路径生成的 HTML 文件。

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 合并由 [`URL`](../../../com.aspose.html/url/) 提供的 HTML 源骨架。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单骨架 HTML 源 URL
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例 
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 另请参阅

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

将通过完整文件路径呈现的模板 HTML 源与模板数据（XML、JSON）合并。结果是通过输出文件路径生成的 html 文件。

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | 合并由完整文件路径提供的 HTML 源骨架。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单骨架 HTML 源文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 启动转换过程
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 另请参阅

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

将通过完整文件路径呈现的模板 HTML 源与模板数据（XML、JSON）合并。结果是通过输出文件路径生成的 html 文件。

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | 合并由完整文件路径提供的 HTML 源骨架。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单骨架 HTML 源文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 使用默认配置启动转换过程
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

将通过内联内容呈现的模板 HTML 源与模板数据（XML、JSON）合并。结果是通过输出文件路径生成的 html 文件。

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 合并由内联字符串内容提供的 HTML 源骨架。 |
| baseUrl | String | HTML 模板的基础 URI。它将与当前目录路径组合形成绝对 URL。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // 将内联源内容设为模板
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
       
      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 将表单输出设为合并结果 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();
	  
      // 启动转换过程
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

### 另请参阅

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

将通过内联内容呈现的模板 HTML 源与模板数据（XML、JSON）合并。结果是通过输出文件路径生成的 html 文件。

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 合并由内联字符串内容提供的 HTML 源骨架。 |
| baseUrl | String | HTML 模板的基础 URI。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |
| outputPath | String | 完整 html 文件路径作为输出转换结果。 |

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // 将内联源内容设为模板
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
    
   // 表单 XML（JSON）模板数据文件路径
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // 定义 TemplateData 对象实例
   var templateData = new TemplateData(templateDataPath);

   // 将表单输出设为合并结果 
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // 定义 configuration 对象实例
   var configuration = new Configuration();

   // 定义默认 TemplateLoadOptions 对象
   var options = new TemplateLoadOptions();

   // 使用默认配置启动转换过程
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

以下是要与源合并的模板数据文件

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

### 另请参阅

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

将由[`HTMLDocument`](../../../com.aspose.html/htmldocument/)呈现的模板源与模板数据（XML、JSON）合并。结果是新生成的HTMLDocument，可保存为文件。

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| template | HTMLDocument | 合并由 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 提供的源骨架。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单骨架 HTML 源文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();
      
      // 将表单 HTML 文档设为转换来源
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // 启动转换过程
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // 保存结果并带有链接资源
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

将由[`URL`](../../../com.aspose.html/url/)呈现的模板HTML源与模板数据（XML、JSON）合并。结果是新生成的[`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可保存为文件。

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 合并由 [`URL`](../../../com.aspose.html/url/) 提供的 HTML 源骨架。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 将URL形成骨架HTML源文件
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 启动转换过程
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // 保存结果并带有链接资源
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

将由[`URL`](../../../com.aspose.html/url/)呈现的模板HTML源与模板数据（XML、JSON）合并。结果是新生成的[`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可保存为文件。

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 合并由 [`URL`](../../../com.aspose.html/url/) 提供的 HTML 源骨架。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 将URL形成骨架HTML源文件
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 使用默认配置启动转换过程
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // 保存结果并带有链接资源
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

将通过完整文件路径呈现的模板HTML源与模板数据（XML、JSON）合并。结果是新生成的[`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可保存为文件。

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | 合并由完整文件路径提供的 HTML 源骨架。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单骨架 HTML 源文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 启动转换过程
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // 保存结果并带有链接资源
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

将通过完整文件路径呈现的模板HTML源与模板数据（XML、JSON）合并。结果是新生成的[`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可保存为文件。

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | String | 合并由完整文件路径提供的 HTML 源骨架。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 表单骨架 HTML 源文件路径
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 表单结果文件路径
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 使用默认配置启动转换过程
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // 保存结果并带有链接资源
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

将通过内联内容呈现的模板HTML源与模板数据（XML、JSON）合并。结果是新生成的[`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可保存为文件。

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 合并由内联字符串内容提供的 HTML 源骨架。 |
| baseUrl | String | HTML 模板的基础 URI。它将与当前目录路径组合形成绝对 URL。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 将内联源内容设为模板
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

      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 将表单输出设为合并结果 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 启动转换过程并保存结果
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

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

将通过内联内容呈现的模板HTML源与模板数据（XML、JSON）合并。结果是新生成的[`HTMLDocument`](../../../com.aspose.html/htmldocument/)，可保存为文件。

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 合并由内联字符串内容提供的 HTML 源骨架。 |
| baseUrl | String | HTML 模板的基础 URI。它将与当前目录路径组合形成绝对 URL。 |
| configuration | Configuration | 环境配置。表示用于为应用程序设置环境设置的 [`configuration`](../../../com.aspose.html/configuration/) 上下文对象。 |
| 数据 | TemplateData | 用于合并的模板数据 - 替换（XML，JSON）。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 对象实例。它用于确定模板和数据项名称是否匹配，是否区分大小写（选项）。 |

### 返回值

新生成的 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) 作为转换结果，可通过输出文件路径保存。

## 备注

模板合并器

模板合并的理念是基于 HTML 模板创建 HTML 文档，并从数据源填充内容。Aspose.HTML 提供内联表达式语法来处理模板和各种数据源类型，例如 XML 和 JSON。请参阅 [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/)，在那里您可以找到有关模板合并以及使用 ConvertTemplate() 方法的更多信息。

转换（合并）步骤

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

模板来源。通过文件、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) 对象实例或甚至内联内容来定义 HTML 模板来源。转换结果。您可以直接获取生成的 HTMLDocument，或根据方法签名定义结果输出文件路径。创建 [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) 实例。使用 Converter 类的 ConvertTemplate() 方法将模板与数据合并。您也可以将 [`configuration`](../../../com.aspose.html/configuration/) 作为可选参数添加。源代码

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 将内联源内容设为模板
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
       
      // 表单 XML（JSON）模板数据文件路径
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // 定义 TemplateData 对象实例
      var templateData = new TemplateData(templateDataPath);

      // 将表单输出设为合并结果 
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // 定义 configuration 对象实例
      var configuration = new Configuration();

      // 定义默认 TemplateLoadOptions 对象
      var options = new TemplateLoadOptions();

      // 启动转换过程并保存结果
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

### 另请参阅

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
