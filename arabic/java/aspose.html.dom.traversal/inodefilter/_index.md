---
title: "واجهة INodeFilter"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.dom.traversal.INodeFilter. الفلاتر هي كائنات تعرف كيفية تصفية العقد. إذا تم إعطاء NodeIterator أو TreeWalker كائن NodeFilter فإنه يطبق الفلتر قبل أن يُعيد العقدة التالية. إذا قال الفلتر بقبول العقدة، فإن منطق التجوال يُعيدها؛ وإلا يبحث التجوال عن العقدة التالية ويتظاهر بأن العقدة التي رُفضت غير موجودة."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

الفلاتر هي كائنات تعرف كيفية "تصفية" العقد. إذا تم إعطاء NodeIterator أو TreeWalker كائن NodeFilter، فإنه يطبق الفلتر قبل أن يُعيد العقدة التالية. إذا قال الفلتر بقبول العقدة، فإن منطق التصفح يُعيدها؛ وإلا، يبحث التصفح عن العقدة التالية ويتظاهر بأن العقدة المرفوضة لم تكن موجودة.

لا يوفر DOM أي فلاتر. NodeFilter هو مجرد واجهة يمكن للمستخدمين تنفيذها لتوفير فلاترهم الخاصة.

لا تحتاج NodeFilters إلى معرفة كيفية التجوال من عقدة إلى أخرى، ولا تحتاج إلى معرفة أي شيء عن بنية البيانات التي يتم تجوالها. هذا يجعل كتابة الفلاتر سهلة جداً، حيث أن الشيء الوحيد الذي يجب أن تعرفه هو تقييم عقدة واحدة. يمكن استخدام فلتر واحد مع عدد من أنواع التجوال المختلفة، مما يشجع على إعادة استخدام الشيفرة.

انظر أيضاً إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | اختبر ما إذا كانت عقدة محددة مرئية في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. (مع ذلك يمكنك القيام بذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك.) |

### انظر أيضًا

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
