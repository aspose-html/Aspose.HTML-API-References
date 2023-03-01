---
title: Interface ITraversal
second_title: Aspose.HTML لمرجع .NET API
description: Aspose.Html.Dom.Traversal.ITraversal واجهه المستخدم. يتم استخدام التكرارات للدخول إلى مجموعة من العقد  على سبيل المثال مجموعة العقد في NodeList  أو الشجرة الفرعية للمستند التي تحكمها عقدة معينة  أو نتائج استعلام  أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد المراد تكرارها من خلال تنفيذ لـ NodeIterator. يحدد DOM المستوى 2 تنفيذ NodeIterator الفردي لأمر المستندات اجتياز الشجرة الفرعية للمستند. يتم إنشاء مثيلات هذه التكرارات عن طريق استدعاء DocumentTraversal .createNodeIterator  .
type: docs
weight: 2510
url: /ar/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

يتم استخدام التكرارات للدخول إلى مجموعة من العقد ، على سبيل المثال مجموعة العقد في NodeList ، أو الشجرة الفرعية للمستند التي تحكمها عقدة معينة ، أو نتائج استعلام ، أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد المراد تكرارها من خلال تنفيذ لـ NodeIterator. يحدد DOM المستوى 2 تنفيذ NodeIterator الفردي لأمر المستندات اجتياز الشجرة الفرعية للمستند. يتم إنشاء مثيلات هذه التكرارات عن طريق استدعاء DocumentTraversal .createNodeIterator () .

انظر أيضا[نموذج كائن المستند (DOM) المستوى 2 الاجتياز وتحديد النطاق](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @ منذ DOM المستوى 2

```csharp
public interface ITraversal : IDisposable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | NodeFilter المستخدم لفحص العقد. |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | العقدة الجذرية لـ NodeIterator ، كما هو محدد عند إنشاء it . |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | تحدد هذه السمة أنواع العقدة التي يتم تقديمها عبر مكرر . يتم تحديد مجموعة الثوابت المتاحة في واجهة NodeFilter. العقد التي لم يتم قبولها by سيتم تخطي whatToShow ، ولكن لا يزال من الممكن اعتبار أطفالهم . لاحظ أن هذا التخطي له الأسبقية على عامل التصفية ، إن وجد. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* المجسم [Aspose.HTML](../../)


