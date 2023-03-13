---
title: Interface ICSSRule
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Css.ICSSRule واجهه المستخدم. واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من عبارات CSS. يتضمن هذا كلاً من مجموعات القواعد و atrules. من المتوقع أن يحافظ التطبيق على جميع القواعد المحددة في ورقة أنماط CSS  حتى إذا لم يتعرف المحلل اللغوي على القاعدة. يتم تمثيل القواعد غير المعترف بها باستخدامICSSUnknownRule الواجهة .
type: docs
weight: 470
url: /ar/net/aspose.html.dom.css/icssrule/
---
## ICSSRule interface

واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من عبارات CSS. يتضمن هذا كلاً من مجموعات القواعد و at-rules. من المتوقع أن يحافظ التطبيق على جميع القواعد المحددة في ورقة أنماط CSS ، حتى إذا لم يتعرف المحلل اللغوي على القاعدة. يتم تمثيل القواعد غير المعترف بها باستخدام!:ICSSUnknownRule الواجهة .

```csharp
public interface ICSSRule
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssrule/csstext/) { get; set; } | التمثيل النصي القابل للتحليل للقاعدة. هذا يعكس الحالة الحالية للقاعدة وليس قيمتها الأولية. |
| [ParentRule](../../aspose.html.dom.css/icssrule/parentrule/) { get; } | إذا تم احتواء هذه القاعدة داخل قاعدة أخرى (مثل قاعدة نمط داخل كتلةmedia) ، فهذه هي القاعدة الحاوية. إذا لم تكن هذه القاعدة متداخلة داخل أي قواعد أخرى ، فسيتم إرجاع قيمة خالية. |
| [ParentStyleSheet](../../aspose.html.dom.css/icssrule/parentstylesheet/) { get; } | ورقة الأنماط التي تحتوي على هذه القاعدة . |
| [Type](../../aspose.html.dom.css/icssrule/type/) { get; } | نوع القاعدة ، كما هو محدد أعلاه. التوقع هو أنه يمكن استخدام طرق الصب الخاصة بالربط للتخلص من مثيل لواجهة CSSRule إلى الواجهة المشتقة المحددة التي يتضمنها النوع. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* المجسم [Aspose.HTML](../../)


