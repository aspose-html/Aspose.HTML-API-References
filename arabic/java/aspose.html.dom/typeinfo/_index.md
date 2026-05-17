---
title: "فئة TypeInfo"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.dom.TypeInfo فئة. تمثل TypeInfo نوعًا مشارًا إليه من عقد Element أو Attr المحددة في المخططات المرتبطة بالمستند"
type: docs

url: /ar/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

تمثل TypeInfo نوعًا مُشارًا إليه من عقد Element أو Attr، محددًا في المخططات المرتبطة بالمستند.

```java
public class TypeInfo : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) اسم النوع المعلن للعنصر أو السمة المرتبطة، أو null إذا كان غير معروف. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) يحصل على حزمة النوع. حزمة النوع المعلن للعنصر أو السمة المرتبطة أو null إذا لم يكن للعنصر إعلان أو إذا لم تتوفر معلومات عن الحزمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | هذه الطريقة تُعيد ما إذا كان هناك اشتقاق بين تعريف نوع المرجع، أي TypeInfo الذي تُستدعى منه الطريقة، وتعريف النوع الآخر، أي الذي يُمرَّر كمعامل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | إذا كان مخطط المستند مخطط XML [XML Schema Part 1]، فإن هذا الثابت يمثل الاشتقاق عبر الامتداد. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | إذا كان مخطط المستند مخطط XML [XML Schema Part 1]، فإن هذا الثابت يمثل القائمة. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | إذا كان مخطط المستند مخطط XML [XML Schema Part 1]، فإن هذا الثابت يمثل الاشتقاق عبر التقييد إذا كانت الأنواع المعقدة متضمنة، أو تقييد إذا كانت الأنواع البسيطة متضمنة. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | إذا كان مخطط المستند مخطط XML [XML Schema Part 1]، فإن هذا الثابت يمثل الاتحاد إذا كانت الأنواع البسيطة متضمنة. |

### انظر أيضًا

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
