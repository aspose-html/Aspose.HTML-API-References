---
title: Class License
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.License فصل. يوفر طرقًا لترخيص المكون.
type: docs
weight: 3810
url: /ar/net/aspose.html/license/
---
## License class

يوفر طرقًا لترخيص المكون.

```csharp
public class License
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [License](license/)() | تهيئة مثيل جديد لهذه الفئة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense)(Stream) | تراخيص المكون . |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense_1)(string) | تراخيص المكون . |

### أمثلة

في هذا المثال ، سيتم إجراء محاولة للعثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على  المكون ، في المجلد الذي يحتوي على التجميع الاستدعاء ، في مجلد تجميع الإدخال ثم في الموارد المضمنة لتجميع الاستدعاء.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

ملف جرة المكون:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### أنظر أيضا

* مساحة الاسم [Aspose.Html](../../aspose.html/)
* المجسم [Aspose.HTML](../../)


