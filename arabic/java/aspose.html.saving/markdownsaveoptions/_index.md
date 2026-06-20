---
title: "فئة MarkdownSaveOptions"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.saving.MarkdownSaveOptions. تمثل خيارات حفظ Markdown. على سبيل المثال يمكنك ضبط نمط تنسيق markdown باستخدام خيارات متوافقة مسبقًا مع GitLab Flavored Markdown وتكوين معالجة الموارد. راجع المزيد من المعلومات في المقالة"
type: docs

url: /ar/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

يمثل خيارات حفظ Markdown. على سبيل المثال، يمكنك تعيين نمط تنسيق markdown، واستخدام خيارات متوافقة مسبقًا مع GitLab Flavored Markdown وتكوين معالجة الموارد. راجع المزيد من المعلومات في [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | ينشئ مثيلًا جديدًا من الفئة `MarkdownSaveOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) يُرجع مجموعة من الخيارات المتوافقة مع وثائق Markdown الافتراضية. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) يُرجع مجموعة من الخيارات المتوافقة مع GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) يحصل على كائن [`ResourceHandlingOptions`](../resourcehandlingoptions/) يُستخدم لتكوين معالجة الموارد. |

## ملاحظات

يمكنك العثور على أمثلة كاملة وملفات بيانات على [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // جهّز مسار لحفظ الملف المحوّل
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // جهّز كود HTML واحفظه في الملف
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // أنشئ مثيلًا من SaveOptions واضبط القاعدة: 
      // - فقط عناصر <a> و <p> سيتم تحويلها إلى Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // استدعِ طريقة ConvertHTML لتحويل HTML إلى Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
