---
title: Interface ICSSStyleDeclaration
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration واجهه المستخدم. تمثل واجهة CSSStyleDeclusion كتلة إعلان CSS واحدة. يمكن استخدام هذه الواجهة لتحديد خصائص النمط المعينة حاليًا في كتلة أو لتعيين خصائص النمط بشكل صريح داخل الكتلة.
type: docs
weight: 490
url: /ar/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

تمثل واجهة CSSStyleDeclusion كتلة إعلان CSS واحدة. يمكن استخدام هذه الواجهة لتحديد خصائص النمط المعينة حاليًا في كتلة أو لتعيين خصائص النمط بشكل صريح داخل الكتلة.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | التمثيل النصي القابل للتحليل لكتلة الإعلان (باستثناء الأقواس المتعرجة المحيطة). سيؤدي تعيين هذه السمة إلى تحليل القيمة الجديدة وإعادة تعيين جميع الخصائص في قالب الإعلان بما في ذلك إزالة الخصائص أو إضافتها. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | يُستخدم لاسترداد الخصائص التي تم تعيينها صراحةً في كتلة الإعلان هذه. لا يجب أن يكون ترتيب الخصائص التي تم استردادها باستخدام هذه الطريقة هو الترتيب الذي تم تعيينها به. يمكن استخدام هذه الطريقة لتكرار جميع الخصائص في قالب الإعلان هذا. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | عدد الخصائص التي تم تعيينها صراحةً في قالب الإعلان هذا. نطاق المؤشرات الصالحة هو من 0 إلى الطول -1 ضمناً . |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | قاعدة CSS التي تحتوي على كتلة الإعلان هذه أو فارغة إذا لم يتم إرفاق إعلان CSSStyle هذا بقاعدة CSSRule. |

## طُرق

| اسم | وصف |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | تُستخدم لاسترداد تمثيل الكائن لقيمة خاصية CSS إذا تم تعيينها صراحةً ضمن كتلة الإعلان هذه. ترجع هذه الطريقة فارغة إذا كانت الخاصية خاصية مختصرة. لا يمكن الوصول إلى قيم خاصية الاختزال وتعديلها إلا كسلاسل ، باستخدام أساليب getPropertyValue و setProperty. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | تُستخدم لاسترداد أولوية خاصية CSS (على سبيل المثال ، المؤهل "المهم") إذا تم تعيين الخاصية صراحةً في كتلة الإعلان هذه. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | يُستخدم لاسترداد قيمة خاصية CSS إذا تم تعيينها صراحةً ضمن كتلة الإعلان هذه. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | تُستخدم لإزالة خاصية CSS إذا تم تعيينها صراحةً ضمن كتلة الإعلان هذه. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | تُستخدم لتعيين قيمة خاصية ذات أولوية افتراضية ضمن كتلة الإعلان هذه. الأولوية الافتراضية ليست "مهمة" ، أي String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | يُستخدم لتعيين قيمة الخاصية والأولوية ضمن كتلة الإعلان هذه. |

### أنظر أيضا

* interface [ICSS2Properties](../icss2properties/)
* مساحة الاسم [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* المجسم [Aspose.HTML](../../)


