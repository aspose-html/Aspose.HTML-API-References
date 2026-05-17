---
title: "تعداد HTMLSaveFormat"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "التعداد com.aspose.html.saving.HTMLSaveFormat. يحدد الصيغة التي يُحفظ بها المستند. يمكنك العثور على مزيد من المعلومات حول حفظ HTMLDocument في المقالة"
type: docs

url: /ar/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

يحدد الصيغة التي يُحفظ بها المستند. يمكنك العثور على مزيد من المعلومات حول حفظ [`HTMLDocument`](../../com.aspose.html/htmldocument/) في [المقالة](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Original | `0` | سيتم حفظ المستند بصيغته الأصلية. |
| Markdown | `1` | سيتم حفظ المستند كـ Markdown. |
| MHTML | `2` | سيتم حفظ المستند كـ MHTML. |

## ملاحظات

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // تحضير مسار إخراج لحفظ المستند
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // تحضير كود HTML
  var html_code = "<H2>Hello World!</H2>";
   
  // تهيئة مستند من المتغيّر String
  using (var document = new HTMLDocument(html_code, "."))
  {
    // احفظ المستند كملف Markdown
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### انظر أيضًا

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
