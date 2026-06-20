---
title: "com.aspose.html.dom"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "حزمة com.aspose.html.dom لنموذج كائن المستند (Document Object Model) توفر API تمثّل وتتفاعل مع أي مستندات HTML أو XML أو SVG. الـ DOM هو نموذج مستند يُحمَّل في المتصفح ويمثّل المستند كشجرة عقد حيث تمثل كل عقدة جزءًا من المستند، مثل عنصر أو نص أو سلسلة أو تعليق."
type: docs

url: /ar/java/com.aspose.html.dom/
---
حزمة **com.aspose.html.dom (Document Object Model)** توفر API تمثل وتتفاعل مع أي مستندات HTML أو XML أو SVG. الـ DOM هو نموذج مستند يُحمَّل في المتصفح ويُمثل المستند كشجرة عقد، حيث تمثل كل عقدة جزءًا من المستند (مثل عنصر، سلسلة نصية، أو تعليق).

## الفئات

| الفئة | الوصف |
| --- | --- |
| [Attr](./attr/) | واجهة Attr تمثل سمة في كائن Element. عادةً ما تُحدَّد القيم المسموح بها للسمة في مخطط مرتبط بالمستند. |
| [CDATASection](./cdatasection/) | تُستخدم أقسام CDATA لتجاوز كتل النص التي تحتوي على أحرف قد تُعتبر علامات. |
| [CharacterData](./characterdata/) | تُوسّع CharacterData فئة Node بمجموعة من السمات والطرق للوصول إلى بيانات الأحرف في الـ DOM. |
| [Comment](./comment/) | تورث من CharacterData وتمثّل محتوى التعليق، أي جميع الأحرف بين العلامتين '' البداية. |
| [Document](./document/) | تمثّل Document المستند الكامل لـ HTML أو XML أو SVG. مفهومياً، هي جذر شجرة المستند، وتوفر الوصول الأساسي إلى بيانات المستند. |
| [DocumentFragment](./documentfragment/) | DocumentFragment هو كائن مستند "خفيف الوزن" أو "حد أدنى". من الشائع جدًا الرغبة في استخراج جزء من شجرة المستند أو إنشاء جزء جديد من المستند. |
| [DocumentType](./documenttype/) | توفر DocumentType واجهة لقائمة الكيانات المعرفة للمستند. |
| [DOMException](./domexception/) | واجهة DOMException تمثل حدثًا غير طبيعي (يسمى استثناء) يحدث نتيجة استدعاء طريقة أو الوصول إلى خاصية في واجهة برمجة تطبيقات الويب. هذا هو الأسلوب الأساسي لوصف حالات الخطأ في واجهات برمجة تطبيقات الويب. |
| [DOMObject](./domobject/) | نوع DOMObject يُستخدم لتمثيل كائن أساسي لكامل نموذج كائن المستند (Document Object Model). بالنسبة لـ Java و ECMAScript، يُربط DOMObject بنوع Object. |
| [Element](./element/) | واجهة Element تمثل عنصرًا في مستند HTML أو XML. |
| [Entity](./entity/) | يمثل كيانًا معروفًا، إما مُحلَّلًا أو غير مُحلَّل، في مستند XML. |
| [EntityReference](./entityreference/) | قد تُستخدم عقد EntityReference لتمثيل إشارة كيان في الشجرة. |
| [EventTarget](./eventtarget/) | يتم تنفيذ واجهة **EventTarget** بواسطة الكائنات التي يمكنها استقبال الأحداث وقد يكون لديها مستمعون لها. بعبارة أخرى، أي هدف للأحداث ينفذ الطرق الثلاث المرتبطة بهذه الواجهة. |
| [Node](./node/) | واجهة Node هي نوع البيانات الأساسي لكامل نموذج كائن المستند (Document Object Model). تمثل عقدة واحدة في شجرة المستند. بينما تكشف جميع الكائنات التي تنفذ واجهة Node عن طرق للتعامل مع الأطفال، لا يجوز لجميع الكائنات التي تنفذ واجهة Node أن يكون لها أطفال. على سبيل المثال، قد لا تحتوي عقد [`Text`](../com.aspose.html.dom/text/) على أطفال، وإضافة أطفال إلى مثل هذه العقد يؤدي إلى رفع [`DOMException`](../com.aspose.html.dom/domexception/). |
| [Notation](./notation/) | يمثل تدوينًا تم إعلانه في DTD. |
| [ProcessingInstruction](./processinginstruction/) | تمثل ProcessingInstruction "تعليمات المعالجة"، وتُستخدم في XML كطريقة للحفاظ على معلومات خاصة بالمعالج داخل نص المستند. |
| [QualifiedName](./qualifiedname/) | يمثل اسمًا مؤهلًا في HTML. |
| [ShadowRoot](./shadowroot/) | ShadowRoot هو عقدة جذر لشجرة الظل. |
| [Text](./text/) | واجهة Text ترث من CharacterData وتمثل المحتوى النصي (المعروف ببيانات الأحرف في XML) لعنصر Element أو سمة Attr. |
| [TypeInfo](./typeinfo/) | تمثل TypeInfo نوعًا مُشارًا إليه من عقد Element أو Attr، المحدد في المخططات المرتبطة بالمستند. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | سياق التصفح هو بيئة تُعرض فيها كائنات [`Document`](../com.aspose.html.dom/document/) للمستخدم. |
| [IChildNode](./ichildnode/) | يعرّف واجهة [`IChildNode`](../com.aspose.html.dom/ichildnode/) التي يجب أن تُنفّذها [`Node`](../com.aspose.html.dom/node/) التي يمكن أن يكون لها أصل. |
| [IDOMImplementation](./idomimplementation/) | توفر واجهة DOMImplementation عددًا من الطرق لإجراء عمليات لا تعتمد على أي نسخة معينة من نموذج كائن المستند. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | يمثل واجهة يجب أن يرثها جميع العناصر التي تدعم معالجة أحداث النظام. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | يعرّف [`IChildNode`](../com.aspose.html.dom/ichildnode/) التي ليست [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | يعرّف [`IParentNode`](../com.aspose.html.dom/iparentnode/) التي ليست من نوع Element. |
| [IParentNode](./iparentnode/) | يعرّف واجهة [`IParentNode`](../com.aspose.html.dom/iparentnode/) التي تُنفّذها أي من الآباء المحتملين. |
| [IStorage](./istorage/) | توفر هذه الواجهة في واجهة برمجة تطبيقات Web Storage إمكانية الوصول إلى جلسة أو تخزين محلي لنطاق معين. راجع مواصفة Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | الأوضاع التي يمكن أن يعمل فيها ShadowRoot. |
