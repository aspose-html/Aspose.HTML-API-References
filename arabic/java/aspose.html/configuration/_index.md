---
title: "Configuration فئة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.Configuration class. يمثل كائن سياق التكوين الذي يُستخدم لإعداد إعدادات البيئة للتطبيق. من خلال إدارة التكوين يمكنك تجاوز نمط المستند بتطبيق ورقة أنماط مخصصة للمستخدم أو معالجة أي طلبات ويب من التطبيق بالإضافة إلى تكوين سياسة السكريبتات. التفاصيل موجودة في دليل تكوين البيئة."
type: docs

url: /ar/java/com.aspose.html/configuration/
---
## Configuration class

يمثل كائن سياق التكوين الذي يُستخدم لإعداد إعدادات البيئة للتطبيق. من خلال إدارة التكوين يمكنك تجاوز نمط المستند بتطبيق ورقة أنماط مخصصة للمستخدم، أو معالجة أي طلبات ويب من التطبيق بالإضافة إلى تكوين سياسة السكريبتات. التفاصيل موجودة في [دليل تكوين البيئة](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Configuration](configuration/)() | ينشئ مثيلًا جديدًا من `class`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | إنشاء وتكوين مثيل كائن Configuration. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | إنشاء وتكوين مثيل كائن Configuration. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | يُجري مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | يحصل على الخدمة المطلوبة. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | يحصل على الخدمة المطلوبة. |

## ملاحظات

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // يقوم معالج الرسائل هذا بطباعة رسالة حول بدء وإنهاء معالجة الطلب.
    public class LogMessageHandler : MessageHandler
    {
      // تجاوز طريقة Invoke()
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // استدعاء معالج الرسائل التالي في السلسلة.
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // إنشاء نسخة من الفئة Configuration
      using var configuration = new Configuration();

      // إضافة LogMessageHandler إلى سلسلة معالجات الرسائل الموجودة
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // تحضير المسار إلى ملف وثيقة المصدر
      String documentPath = Path.Combine(DataDir, "input.htm");

      // تهيئة مستند HTML باستخدام التكوين المحدد
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.net;
import com.aspose.html.saving;
import com.aspose.html.services;
import System;
import System.Collections.Generic;
import System.IO;
import System.Net;
import System.Text;

public void SandboxingSample()
    {
      // جهّز كود HTML واحفظه في ملف
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // إنشاء نسخة من Configuration
      using (var configuration = new Configuration())
      {
        // وضع علامة 'scripts' كمورد غير موثوق
        configuration.Security |= Sandbox.Scripts;

        // تهيئة مستند HTML باستخدام التكوين المحدد
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // تحويل HTML إلى PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### انظر أيضًا

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
