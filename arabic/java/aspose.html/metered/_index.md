---
title: "فئة Metered"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.Metered. توفر طرقًا لتعيين المفتاح المتقن"
type: docs

url: /ar/java/com.aspose.html/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقيس.

```java
public class Metered
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered/)() | يُنشئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | يضبط المفتاح العام والخاص للترخيص المتقن. إذا قمت بشراء ترخيص متقن، عند بدء التطبيق يجب استدعاء هذه الواجهة البرمجية، عادةً يكون ذلك كافيًا. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم؛ لتجنب ذلك، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | تحقق مما إذا كان المتري مرخصًا |

## الأمثلة

في هذا المثال، سيتم محاولة تعيين المفتاح العام والخاص للمتري

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

ملف jar الخاص بالمكوّن:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### انظر أيضًا

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
