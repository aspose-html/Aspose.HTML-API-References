---
title: "فئة License"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.License. توفر طرقاً لترخيص المكوّن"
type: docs

url: /ar/java/com.aspose.html/license/
---
## License class

يوفر طرقًا لترخيص المكوّن.

```java
public class License
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license/)() | يُنشئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | يرخص المكوّن. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | يرخص المكوّن. |

## الأمثلة

في هذا المثال، سيُجرى محاولة للعثور على ملف الترخيص المسمى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

ملف jar الخاص بالمكوّن:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### انظر أيضًا

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
