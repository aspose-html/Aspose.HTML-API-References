---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML لمرجع .NET API
description: ملف Aspose.html.Dom.Traversalتحتوي مساحة الاسم على الأساليب التي إنشاء مكررات وممرات شجرية للتنقل بين العناصر و اجتياز عقدة وأفرادها بترتيب المستند.
type: docs
weight: 170
url: /ar/net/aspose.html.dom.traversal/
---
ملف **Aspose.html.Dom.Traversal**تحتوي مساحة الاسم على الأساليب التي إنشاء مكررات وممرات شجرية للتنقل بين العناصر و اجتياز عقدة وأفرادها بترتيب المستند.

## واجهات

| واجهه المستخدم | وصف |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal) | يحتوي DocumentTraversal على طرق تنشئ تكرارات و مسارات شجرية لاجتياز عقدة وتوابعها بترتيب المستند (العمق أولاً ، اجتياز الطلب المسبق ، وهو ما يعادل الترتيب الذي تظهر به علامات البدء في تمثيل النص لـ المستند). في DOMs التي تدعم ميزة الاجتياز ، سيتم تنفيذ DocumentTraversal بواسطة نفس الكائنات التي تنفذ واجهة المستند. |
| [IElementTraversal](./ielementtraversal) | واجهة ElementTraversal هي مجموعة من سمات القراءة فقط التي تسمح للمؤلف بالتنقل بسهولة بين العناصر في المستند. في توافق عمليات تنفيذ Element Traversal ، يجب على جميع الكائنات التي تنفذ Element أيضًا تنفيذ واجهة ElementTraversal . |
| [INodeFilter](./inodefilter) | المرشحات هي كائنات تعرف كيفية "تصفية" العقد. إذا تم إعطاء NodeIterator أو TreeWalker NodeFilter ، فإنه يطبق عامل التصفية قبل إرجاع العقدة التالية . إذا طلب عامل التصفية قبول العقدة ، فسيعيد منطق الاجتياز it؛ وبخلاف ذلك ، يبحث الاجتياز عن العقدة التالية ويتظاهر بأن العقدة التي تم رفضها لم تكن موجودة. |
| [INodeIterator](./inodeiterator) | يتم استخدام التكرارات للدخول إلى مجموعة من العقد ، على سبيل المثال مجموعة العقد في NodeList ، أو الشجرة الفرعية للمستند التي تحكمها عقدة معينة ، أو نتائج استعلام ، أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد المراد تكرارها من خلال تنفيذ لـ NodeIterator. يحدد المستوى 2 من DOM تنفيذًا منفردًا لـ NodeIterator من أجل اجتياز ترتيب المستندات لشجرة المستند الفرعية. يتم إنشاء مثيلات هذه التكرارات عن طريق استدعاء DocumentTraversal .createNodeIterator () . |
| [ITraversal](./itraversal) | يتم استخدام التكرارات للدخول إلى مجموعة من العقد ، على سبيل المثال مجموعة العقد في NodeList ، أو الشجرة الفرعية للمستند التي تحكمها عقدة معينة ، أو نتائج استعلام ، أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد المراد تكرارها من خلال تنفيذ لـ NodeIterator. يحدد المستوى 2 من DOM تنفيذًا منفردًا لـ NodeIterator من أجل اجتياز ترتيب المستندات لشجرة المستند الفرعية. يتم إنشاء مثيلات هذه التكرارات عن طريق استدعاء DocumentTraversal .createNodeIterator () . |
| [ITreeWalker](./itreewalker) | يتم استخدام كائنات TreeWalker للتنقل في شجرة مستند أو شجرة فرعية باستخدام طريقة عرض المستند المحددة بواسطة علامات ومرشح whatToShow (إن وجد). أي وظيفة تؤدي إلى التنقل باستخدام TreeWalker ستدعم تلقائيًا أي طريقة عرض محددة بواسطة TreeWalker . |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->