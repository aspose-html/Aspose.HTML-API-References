---
title: "فئة MHTMLSaveOptions"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.saving.MHTMLSaveOptions. تمثل خيارات حفظ MHTML. من خلال تعيين خصائص محددة يمكنك إدارة معالجة الموارد مثل أقصى عمق معالجة وما إلى ذلك. لمزيد من المعلومات راجع مقالة الوثائق."
type: docs

url: /ar/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

يمثل خيارات حفظ MHTML. من خلال تعيين خصائص محددة يمكنك إدارة معالجة الموارد مثل الحد الأقصى لعمق المعالجة وما إلى ذلك. لمزيد من المعلومات راجع الوثائق [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
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
	 // قم بإعداد شفرة HTML مع رابط إلى ملف آخر واحفظها في الملف باسم 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // قم بإعداد شفرة HTML واحفظها في الملف باسم 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // غيّر قيمة عمق ربط الموارد إلى 1 لتحويل المستند مع الموارد المرتبطة مباشرة
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // تحويل HTML إلى MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
