---
title: IXPathEvaluator.CreateExpression
second_title: Aspose.HTML لمرجع .NET API
description: IXPathEvaluator طريقة. لتكوين تعبير XPath تم تحليله باستخدام مساحات الأسماء التي تم حلها. يعد هذا مفيدًا عندما يُعاد استخدام تعبير في أحد التطبيقات لأنه يجعل من الممكن تجميع سلسلة التعبير في نموذج داخلي أكثر كفاءة و حل جميع بادئات مساحة الاسم التي تحدث داخل التعبير.
type: docs
weight: 10
url: /ar/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

لتكوين تعبير XPath تم تحليله باستخدام مساحات الأسماء التي تم حلها. يعد هذا مفيدًا عندما يُعاد استخدام تعبير في أحد التطبيقات لأنه يجعل من الممكن تجميع سلسلة التعبير في نموذج داخلي أكثر كفاءة و حل جميع بادئات مساحة الاسم التي تحدث داخل التعبير.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| expression | String | سلسلة تعبير XPath المراد تحليلها. |
| resolver | IXPathNSResolver | ال`محلل` يسمح بترجمة جميع البادئات ، بما في ذلك`xml` بادئة مساحة الاسم ، ضمن تعبير XPath إلى مساحة الاسم المناسبة URIs. إذا تم تحديد هذا على أنه`باطل` ، سينتج عن أي مساحة اسم بادئة ضمن التعبير[`DOMException`](../../../aspose.html.dom/domexception/) يتم طرحه مع الرمز `NAMESPACE_ERR`. |

### قيمة الإرجاع

الشكل المترجم لتعبير XPath.

### استثناءات

| استثناء | حالة |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: يُرفع إذا لم يكن التعبير قانونيًا وفقًا لقواعد[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: يتم رفعه إذا كان التعبير يحتوي على مساحة اسم بادئات لا يمكن حلها بواسطة المحدد[`IXPathNSResolver`](../../ixpathnsresolver/). |

### أنظر أيضا

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* مساحة الاسم [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* المجسم [Aspose.HTML](../../../)


