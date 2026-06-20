---
title: "فئة Node"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.dom.Node. واجهة Node هي النوع الأساسي للبيانات لكامل نموذج كائن المستند (Document Object Model). تمثل عقدة واحدة في شجرة المستند. بينما جميع الكائنات التي تُطبق واجهة Node تُظهر طرقًا للتعامل مع الأبناء، ليس كل الكائنات التي تُطبق واجهة Node قد يكون لها أبناء. على سبيل المثال، قد لا تحتوي عقد النص (Text nodes) على أبناء، وإضافة أبناء إلى مثل هذه العقد يؤدي إلى رفع استثناء DOMException."
type: docs

url: /ar/java/com.aspose.html.dom/node/
---
## Node class

The Node interface هي نوع البيانات الأساسي لكامل نموذج كائن المستند (Document Object Model). تمثل عقدة واحدة في شجرة المستند. بينما جميع الكائنات التي تنفذ واجهة Node تعرض طرقًا للتعامل مع الأطفال، ليس كل الكائنات التي تنفذ واجهة Node قد تحتوي على أطفال. على سبيل المثال، قد لا تحتوي عقد [`Text`](../text/) على أطفال، وإضافة أطفال إلى مثل هذه العقد يؤدي إلى رفع استثناء [`DOMException`](../domexception/).

السمات [`nodeName`](./nodename/)، [`nodeValue`](./nodevalue/) والسمات مُدرجة كآلية للحصول على معلومات العقد دون التحويل إلى الواجهة المشتقة المحددة. في الحالات التي لا يوجد فيها تعيين واضح لهذه السمات لنوع عقدة محدد [`nodeType`](./nodetype/) (مثال، nodeValue لعقدة [`Element`](../element/) أو السمات لعقدة [`Comment`](../comment/))، تُعيد القيمة null. لاحظ أن الواجهات المتخصصة قد تحتوي على آليات إضافية وأكثر ملاءمة للحصول على المعلومات ذات الصلة وضبطها.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) الخاصية القابلة للقراءة فقط baseURI لواجهة Node تُعيد عنوان URL الأساسي المطلق للمستند الذي يحتوي على العقدة. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) الخاصية القابلة للقراءة فقط childNodes لواجهة Node تُعيد [`NodeList`](../../com.aspose.html.collections/nodelist/) حي لعقد الأطفال للعنصر المحدد حيث تُعطى العقدة الأولى الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية للقراءة فقط firstChild لواجهة `Node` تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم تكن للعقدة أي أطفال. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية للقراءة فقط lastChild لواجهة `Node` تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر، أو عقدة نص، أو عقدة تعليق. تُعيد null إذا لم توجد عناصر طفل. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) تُعيد الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](./element_node/) و[`ATTRIBUTE_NODE`](./attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة DOM Level 1، مثل [`Document.createElement()`](../document/createelement/)، تكون دائمًا null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) خاصية Element.packageURI للقراءة فقط تُعيد URI الحزمة للعنصر، أو null إذا لم يكن العنصر في حزمة. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) الخاصية للقراءة فقط nextSibling لواجهة `Node` تُعيد العقدة التي تلي مباشرةً المحددة في [`childNodes`](./childnodes/) للوالد، أو تُعيد null إذا كانت العقدة المحددة هي آخر طفل في العنصر الأب. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) الخاصية للقراءة فقط nodeName لواجهة Node تُعيد اسم العقدة الحالية كسلسلة نصية. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) رمز يمثل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue property لواجهة `Node ` تُعيد أو تعيّن قيمة العقدة الحالية. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) خاصية ownerDocument للقراءة فقط في واجهة Node تُعيد كائن المستند الأعلى للعقدة. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) الخاصية للقراءة فقط parentElement لواجهة `Node` تُعيد العنصر الأب [`Element`](../element/) لعقدة DOM، أو null إذا لم يكن للعقدة أب، أو إذا لم يكن أبها عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُعيد أب العقدة المحددة في شجرة DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | خاصية prefix للقراءة فقط تُعيد بادئة الحزمة للعنصر المحدد، أو null إذا لم تُحدد أي بادئة. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) الخاصية للقراءة فقط previousSibling لواجهة `Node` تُعيد العقدة التي تسبق مباشرةً المحددة في [`childNodes`](./firstchild/) للوالد، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | The textContent property لواجهة `Node` تمثل محتوى النص للعقدة ونسبها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() لواجهة [`EventTarget `](../eventtarget/) تُعدّ دالة تُستدعى كلما تم توصيل الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | طريقة appendChild() الخاصة بواجهة Node تُضيف عقدة إلى نهاية قائمة الأطفال للعقدة الأصلية المحددة. إذا كان الطفل المُعطى إشارة إلى عقدة موجودة بالفعل في المستند، فإن appendChild() تنقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك حاجة لإزالة العقدة من عقدتها الأصلية قبل إلحاقها بعقدة أخرى). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ينفّذ مهامًا معرفة من قبل التطبيق مرتبطة بتحرير أو تحرير أو إعادة ضبط الموارد غير المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | The hasChildNodes() method لواجهة Node تُعيد قيمة منطقية تشير إلى ما إذا كانت `Node` المعطاة تحتوي على عقد أطفال أم لا. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | طريقة insertBefore() الخاصة بواجهة Node تُدرج عقدة قبل عقدة مرجعية كطفل لعقدة أصلية محددة. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | طريقة isDefaultNamespace() الخاصة بواجهة Node تقبل عنوان حزمة URI كوسيط. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | The isEqualNode() method لواجهة `Node` تختبر ما إذا كانت عقدتين متساويتين. تكون العقدتين متساويتين عندما يكون لديهما نفس النوع، والخصائص المحددة (بالنسبة للعناصر، قد تكون معرفها، عدد الأطفال، وما إلى ذلك)، وتطابق سماتها، وهكذا. مجموعة نقاط البيانات المحددة التي يجب أن تتطابق تختلف حسب نوع العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() الخاصة بواجهة Node هي اسم مستعار قديم للمقارنة الصارمة ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | طريقة lookupNamespaceURI() الخاصة بواجهة Node تأخذ بادئة كمعامل وتُعيد عنوان الحزمة URI المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | طريقة lookupPrefix() الخاصة بواجهة Node تُعيد سلسلة تحتوي على البادئة لعنوان حزمة URI معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُعيد أول بادئة. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد [`Text`](../text/) في العمق الكامل للشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في شكل "عادي" حيث فقط البنية (مثل [`elements`](../element/)، [`comments`](../comment/)، [`processing instructions`](../processinginstruction/)، [`CDATA sections`](../cdatasection/)، و[`entity references`](../entityreference/)) تفصل بين عقد [`Text`](../text/)، أي لا توجد عقد نص متجاورة ولا عقد نص فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة مستند معينة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../../com.aspose.html/configuration/) المرتبط بـ [`Node.ownerDocument`](./ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد النص بالكامل. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | طريقة `removeChild()` في واجهة Node تزيل عقدة فرعية من DOM وتُرجع العقدة المُزالة. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويُعيد عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../documentfragment/) الذين يُدرجون بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يُزال أولاً. |
| [toString](../../com.aspose.html.dom/node/toString/)() | يعيد سلسلة تمثل هذا الكائن. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | سمة [`Attribute`](../attr/) لعقدة [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | قسم [`CDATASection`](../cdatasection/)، مثل &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | عقدة [`Comment`](../comment/)، مثل &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | عقدة [`DocumentFragment`](../documentfragment/). |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | عقدة [`Document`](../document/). |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | عقدة [`DocumentType`](../documenttype/)، مثل &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | عقدة [`Element`](../element/) مثل &lt;p&gt; أو &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | عقدة [`Entity`](../entity/). |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | عقدة [`EntityReference`](../entityreference/). |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | عقدة [`Notation`](../notation/). |
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
