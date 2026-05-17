---
title: "فئة Node"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.Node. واجهة Node هي النوع الأساسي للبيانات لكامل نموذج كائن المستند (Document Object Model). تمثل عقدة واحدة في شجرة المستند. بينما جميع الكائنات التي تُطبق واجهة Node تُظهر طرقًا للتعامل مع الأطفال، ليس كل الكائنات التي تُطبق واجهة Node قد يكون لها أطفال. على سبيل المثال، قد لا تحتوي عقد النص (Text nodes) على أطفال، وإضافة أطفال إلى مثل هذه العقد يؤدي إلى رفع استثناء DOMException."
type: docs

url: /ar/java/com.aspose.html.dom/node/
---
## Node class

The Node interface هي نوع البيانات الأساسي لكامل Document Object Model. تمثل عقدة واحدة في شجرة المستند. بينما جميع الكائنات التي تنفذ واجهة Node تكشف عن طرق للتعامل مع الأطفال، ليس كل الكائنات التي تنفذ واجهة Node قد يكون لديها أطفال. على سبيل المثال، قد لا تحتوي عقد [`Text`](../text/) على أطفال، وإضافة أطفال إلى مثل هذه العقد يؤدي إلى رفع [`DOMException`](../domexception/).

السمات [`nodeName`](./nodename/)، [`nodeValue`](./nodevalue/) والسمات مُدرجة كآلية للوصول إلى معلومات العقد دون التحويل إلى الواجهة المشتقة المحددة. في الحالات التي لا يوجد فيها تعيين واضح لهذه السمات لنوع عقدة محدد [`nodeType`](./nodetype/) (مثلاً، nodeValue لعقدة [`Element`](../element/) أو السمات لعقدة [`Comment`](../comment/))، تُعيد هذه القيمة null. لاحظ أن الواجهات المتخصصة قد تحتوي على آليات إضافية وأكثر ملاءمة للحصول على المعلومات ذات الصلة وتعيينها.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) الخاصية للقراءة فقط baseURI في واجهة Node تُعيد عنوان URL الأساسي المطلق للمستند الذي يحتوي على العقدة. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) الخاصية للقراءة فقط childNodes في واجهة Node تُعيد [`NodeList`](../../com.aspose.html.collections/nodelist/) حي لعقد الأطفال للعنصر المعطى حيث تُعطى العقدة الأولى الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية read-only firstChild لواجهة `Node` تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم يكن للعقدة أطفال. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية read-only lastChild لواجهة `Node` تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر، أو عقدة نص، أو عقدة تعليق. تُعيد null إذا لم توجد عناصر طفل. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) تُعيد الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](./element_node/) و[`ATTRIBUTE_NODE`](./attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة DOM Level 1، مثل [`Document.createElement()`](../document/createelement/)، تكون دائمًا null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) خاصية Element.packageURI للقراءة فقط تُعيد URI الحزمة للعنصر، أو null إذا لم يكن العنصر في حزمة. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) الخاصية read-only nextSibling لواجهة `Node` تُعيد العقدة التي تلي المحددة مباشرةً في `childNodes` الخاصة بوالدها، أو تُعيد null إذا كانت العقدة المحددة هي آخر طفل في العنصر الأب. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) الخاصية read-only nodeName لواجهة Node تُعيد اسم العقدة الحالية كسلسلة نصية. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) رمز يمثل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | خاصية nodeValue لواجهة `Node` تُعيد أو تُعيّن قيمة العقدة الحالية. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) خاصية ownerDocument للقراءة فقط في واجهة Node تُرجع كائن المستند الأعلى المستوى للعقدة. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) الخاصية read-only parentElement لواجهة `Node` تُعيد العنصر الأب [`Element`](../element/) لعقدة DOM، أو null إذا لم يكن للعقدة أب، أو إذا لم يكن أبها عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُرجع أب العقدة المحددة في شجرة DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | خاصية prefix للقراءة فقط تُعيد بادئة الحزمة للعنصر المحدد، أو null إذا لم تُحدد أي بادئة. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) الخاصية read-only previousSibling لواجهة `Node` تُعيد العقدة التي تسبق المحددة مباشرةً في قائمة `childNodes` الخاصة بوالدها، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | خاصية textContent لواجهة `Node` تمثل محتوى النص للعقدة وأبنائها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() لواجهة [`EventTarget `](../eventtarget/) تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | تضيف طريقة appendChild() في واجهة Node عقدة إلى نهاية قائمة الأطفال لعقدة أب محددة. إذا كان الطفل المعطى إشارة إلى عقدة موجودة بالفعل في المستند، فإن appendChild() تنقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك ضرورة لإزالة العقدة من عقدة الأب قبل إلحاقها بعقدة أخرى). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | تُعيد طريقة cloneNode() في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضًا أم لا. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | تُعيد طريقة cloneNode() في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضًا أم لا. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ[`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) المحدد، (متزامنًا) مستدعيًا مستمعي الحدث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | يُجري مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | طريقة hasChildNodes() لواجهة Node تُعيد قيمة منطقية تشير إلى ما إذا كانت العقدة `Node` المعطاة تحتوي على عقد أطفال أم لا. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | تُدرج طريقة insertBefore() في واجهة Node عقدة قبل عقدة مرجعية كطفل لعقدة أب محددة. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | تقبل طريقة isDefaultNamespace() في واجهة Node URI الحزمة كمعامل. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | طريقة isEqualNode() لواجهة `Node` تختبر ما إذا كانت عقدتان متساويتان. تكون العقدتان متساويتين عندما يكون لهما نفس النوع، والخصائص التعريفية (بالنسبة للعناصر، قد تكون المعرف ID، عدد الأطفال، وما إلى ذلك)، وتطابق سماتها، وهكذا. مجموعة نقاط البيانات المحددة التي يجب أن تتطابق تختلف حسب أنواع العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() في واجهة Node هي اسم مستعار قديم للمشغل الصارم ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | تأخذ طريقة lookupNamespaceURI() في واجهة Node بادئة كمعامل وتُعيد URI الحزمة المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | ترجع طريقة lookupPrefix() في واجهة Node سلسلة تحتوي على البادئة لURI حزمة معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُرجع أول بادئة. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد [`Text`](../text/) على كامل عمق الشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في شكل \"normal\" حيث تفصل البنية فقط (مثلًا، [`elements`](../element/)، [`comments`](../comment/)، [`processing instructions`](../processinginstruction/)، [`CDATA sections`](../cdatasection/)، و[`entity references`](../entityreference/)) بين عقد [`Text`](../text/)، أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عند العمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على حرف  ????? ??? ??? ... |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | طريقة removeChild() في واجهة Node تزيل عقدةً فرعيةً من DOM وتعيد العقدة التي أزيلت. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويُعيد عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../documentfragment/) الذين يُدرجون بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يتم إزالته أولاً. |
| [toString](../../com.aspose.html.dom/node/toString/)() | يرجع سلسلة تمثل هذا الكائن. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | `[`Attribute`](../attr/)` من [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | `[`CDATASection`](../cdatasection/)`، مثل &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | عقدة [`Comment`](../comment/)، مثل &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | عقدة [`DocumentFragment`](../documentfragment/). |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | عقدة [`Document`](../document/). |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | عقدة [`DocumentType`](../documenttype/)، مثل &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | عقدة [`Element`](../element/) مثل &lt;p&gt; أو &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | عقدة [`Entity`](../entity/). |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | عقدة [`EntityReference`](../entityreference/). |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | عقدة [`Notation`](../notation/) |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | [`ProcessingInstruction`](../processinginstruction/) من مستند XML، مثل &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | النص الفعلي [`Text`](../text/) داخل [`Element`](../element/) أو [`Attr`](../attr/). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### انظر أيضًا

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
