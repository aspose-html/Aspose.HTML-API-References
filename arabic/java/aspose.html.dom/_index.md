---
title: "com.aspose.html.dom"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "حزمة com.aspose.html.dom لنموذج كائن المستند (Document Object Model) توفر واجهة برمجة تطبيقات تمثل وتتفاعل مع أي مستندات HTML أو XML أو SVG. الـ DOM هو نموذج مستند يُحمَّل في المتصفح ويمثل المستند كشجرة عقد حيث تمثل كل عقدة جزءًا من المستند مثل عنصر أو نص أو سلسلة أو تعليق."
type: docs

url: /ar/java/com.aspose.html.dom/
---
توفر الحزمة **com.aspose.html.dom (Document Object Model)** واجهة برمجة تطبيقات تمثل وتتفاعل مع أي مستندات HTML أو XML أو SVG. الـ DOM هو نموذج مستند يُحمَّل في المتصفح ويُمثل المستند كشجرة عقد، حيث تمثل كل عقدة جزءًا من المستند (مثل عنصر، سلسلة نصية، أو تعليق).

## الفئات

| فئة | الوصف |
| --- | --- |
| [Attr](./attr/) | واجهة Attr تمثل سمة في كائن Element. عادةً ما تُحدد القيم المسموح بها للسمة في مخطط مرتبط بالمستند. |
| [CDATASection](./cdatasection/) | تُستخدم أقسام CDATA للهروب من كتل النص التي تحتوي على أحرف قد تُعتبر علامة إذا لم تُعامل كبيانات. |
| [CharacterData](./characterdata/) | تُوسّع CharacterData فئة Node بمجموعة من السمات والطرق للوصول إلى بيانات الأحرف في الـ DOM. |
| [Comment](./comment/) | تورث من CharacterData وتمثل محتوى التعليق، أي جميع الأحرف بين العلامتين '' البداية. |
| [Document](./document/) | تمثل Document المستند الكامل HTML أو XML أو SVG. مفهومياً، هي جذر شجرة المستند، وتوفر الوصول الأساسي إلى بيانات المستند. |
| [DocumentFragment](./documentfragment/) | DocumentFragment هو كائن مستند "خفيف الوزن" أو "حد أدنى". من الشائع جدًا الرغبة في استخراج جزء من شجرة المستند أو إنشاء جزء جديد من المستند. |
| [DocumentType](./documenttype/) | توفر DocumentType واجهة لقائمة الكيانات المعرفة للمستند. |
| [DOMException](./domexception/) | تمثل واجهة DOMException حدثًا غير طبيعي (يسمى استثناء) يحدث نتيجة استدعاء طريقة أو الوصول إلى خاصية في واجهة برمجة تطبيقات الويب. هذا هو الأسلوب الأساسي لوصف حالات الخطأ في واجهات برمجة تطبيقات الويب. |
| [DOMObject](./domobject/) | يُستخدم نوع DOMObject لتمثيل كائن أساسي لنموذج كائن المستند بالكامل. بالنسبة لـ Java و ECMAScript، يرتبط DOMObject بنوع Object. |
| [Element](./element/) | واجهة Element تمثل عنصرًا في مستند HTML أو XML. |
| [Entity](./entity/) | يمثل كيانًا معروفًا، إما مُحلَّلًا أو غير مُحلَّل، في مستند XML. |
| [EntityReference](./entityreference/) | قد تُستخدم عقد EntityReference لتمثيل إشارة كيان في الشجرة. |
| [EventTarget](./eventtarget/) | يتم تنفيذ واجهة EventTarget بواسطة الكائنات التي يمكنها استقبال الأحداث وقد يكون لديها مستمعون لها. بعبارة أخرى، أي هدف للأحداث ينفّذ الطرق الثلاث المرتبطة بهذه الواجهة. |
| [Node](./node/) | واجهة Node هي نوع البيانات الأساسي لكامل نموذج كائن المستند (Document Object Model). تمثل عقدة واحدة في شجرة المستند. بينما جميع الكائنات التي تنفّذ واجهة Node تكشف عن طرق للتعامل مع الأطفال، ليس كل الكائنات التي تنفّذ واجهة Node قد يكون لديها أطفال. على سبيل المثال، عقد [`Text`](../com.aspose.html.dom/text/) قد لا تكون لها أطفال، وإضافة أطفال إلى مثل هذه العقد يؤدي إلى رفع [`DOMException`](../com.aspose.html.dom/domexception/). |
| [Notation](./notation/) | يمثل تدوينًا تم إعلانه في DTD. |
| [ProcessingInstruction](./processinginstruction/) | تمثل ProcessingInstruction "تعليمة معالجة"، تُستخدم في XML كطريقة للحفاظ على معلومات خاصة بالمُعالج في نص المستند. |
| [QualifiedName](./qualifiedname/) | يمثل اسمًا مؤهلاً في HTML. |
| [ShadowRoot](./shadowroot/) | ShadowRoot هو عقدة جذر لشجرة الظل. |
| [Text](./text/) | واجهة Text ترث من CharacterData وتمثل المحتوى النصي (المعروف ببيانات الأحرف في XML) لعنصر Element أو سمة Attr. |
| [TypeInfo](./typeinfo/) | تمثل TypeInfo نوعًا مُشارًا إليه من عقد Element أو Attr، محددًا في المخططات المرتبطة بالمستند. |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | سياق التصفح هو بيئة تُعرض فيها كائنات [`Document`](../com.aspose.html.dom/document/) للمستخدم. |
| [IChildNode](./ichildnode/) | يعرّف واجهة [`IChildNode`](../com.aspose.html.dom/ichildnode/) التي يجب تنفيذها بواسطة [`Node`](../com.aspose.html.dom/node/) التي يمكن أن يكون لها أصل. |
| [IDOMImplementation](./idomimplementation/) | توفر واجهة DOMImplementation عددًا من الطرق لأداء عمليات مستقلة عن أي نسخة معينة من نموذج كائن المستند. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | يمثل واجهة يجب أن يرثها جميع العناصر التي تدعم معالجة أحداث النظام. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | يعرّف [`IChildNode`](../com.aspose.html.dom/ichildnode/) التي ليست [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | يعرّف [`IParentNode`](../com.aspose.html.dom/iparentnode/) التي ليست من نوع Element. |
| [IParentNode](./iparentnode/) | يعرّف واجهة [`IParentNode`](../com.aspose.html.dom/iparentnode/) التي يتم تنفيذها بواسطة أي من الآباء المحتملين. |
| [IStorage](./istorage/) | توفر هذه الواجهة من واجهة برمجة تطبيقات Web Storage إمكانية الوصول إلى جلسة أو تخزين محلي لنطاق معين. راجع مواصفات Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | الأوضاع التي يمكن أن يعمل فيها ShadowRoot. |
