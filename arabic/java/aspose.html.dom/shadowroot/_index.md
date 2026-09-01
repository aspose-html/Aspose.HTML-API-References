---
title: "فئة ShadowRoot"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.dom.ShadowRoot. ShadowRoot هي عقدة جذر لشجرة الظل"
type: docs

url: /ar/java/com.aspose.html.dom/shadowroot/
---
## ShadowRoot class

ShadowRoot هو عقدة جذر لشجرة الظل.

```java
public class ShadowRoot : DocumentFragment
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) الخاصية القابلة للقراءة فقط baseURI لواجهة Node تُعيد عنوان URL الأساسي المطلق للمستند الذي يحتوي على العقدة. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) يعيد العدد الحالي لعقد العناصر التي هي أبناء لهذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقدة فرعية من نوع nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) الخاصية القابلة للقراءة فقط childNodes لواجهة Node تُعيد [`NodeList`](../../com.aspose.html.collections/nodelist/) حي لعقد الأطفال للعنصر المحدد حيث تُعطى العقدة الأولى الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) يعيد العناصر الفرعية للعنصر الحالي. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية read-only firstChild لواجهة [`Node`](../node/) تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم تكن للعقدة أي أطفال. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) يعيد عقدة العنصر الفرعي الأول لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host هو عنصر يحتوي على هذا ShadowRoot. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية read-only lastChild لواجهة [`Node`](../node/) تُعيد آخر طفل للعقدة. إذا كان أبها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر أو عقدة نص أو عقدة تعليق. تُعيد null إذا لم توجد عناصر طفل. |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) يعيد عقدة العنصر الفرعي الأخير لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) يُرجع الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](../node/element_node/) و[`ATTRIBUTE_NODE`](../node/attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة مستوى DOM 1، مثل [`Document.createElement()`](../document/createelement/)، تكون دائمًا فارغة. |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) الوضع الذي يعمل به هذا ShadowRoot. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) خاصية Element.packageURI للقراءة فقط تُعيد URI الحزمة للعنصر، أو null إذا لم يكن العنصر في حزمة. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) يعيد عقدة العنصر الشقيق التالي لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة تأتي بعده في شجرة المستند. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) الخاصية read-only nextSibling لواجهة [`Node`](../node/) تُعيد العقدة التي تلي مباشرةً العقدة المحددة في [`childNodes`](../node/childnodes/) الخاصة بوالدها، أو تُعيد null إذا كانت العقدة المحددة هي آخر طفل في العنصر الأب. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) اسم هذه العقدة، حسب نوعها. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) رمز يمثل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | خاصية nodeValue في واجهة [`Node `](../node/) تُرجع أو تعيّن قيمة العقدة الحالية. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) خاصية ownerDocument للقراءة فقط في واجهة Node تُعيد كائن المستند الأعلى للعقدة. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) الخاصية read-only parentElement لواجهة [`Node`](../node/) تُعيد العنصر الأب لعقدة DOM وهو [`Element`](../element/)، أو null إذا لم يكن للعقدة أب، أو إذا لم يكن أبها عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُعيد أب العقدة المحددة في شجرة DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | خاصية prefix للقراءة فقط تُعيد بادئة الحزمة للعنصر المحدد، أو null إذا لم تُحدد أي بادئة. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) يعيد عقدة العنصر الشقيق السابق لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة تأتي قبله في شجرة المستند. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) الخاصية read-only previousSibling لواجهة [`Node`](../node/) تُعيد العقدة التي تسبق مباشرةً العقدة المحددة في قائمة [`childNodes`](../node/firstchild/) الخاصة بوالدها، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | هذه السمة تُعيد محتوى النص لهذه العقدة ونوابها. عندما تُحدّد كـ null، لا يؤثر تعيينها. عند التعيين، تُزال جميع الأطفال المحتملين لهذه العقدة، وإذا لم تكن السلسلة الجديدة فارغة أو null، تُستبدل بعقدة نصية واحدة تحتوي على السلسلة التي تم تعيينها لهذه السمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() لواجهة [`EventTarget `](../eventtarget/) تُعدّ دالة تُستدعى كلما تم توصيل الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | طريقة appendChild() الخاصة بواجهة Node تُضيف عقدة إلى نهاية قائمة الأطفال للعقدة الأصلية المحددة. إذا كان الطفل المُعطى إشارة إلى عقدة موجودة بالفعل في المستند، فإن appendChild() تنقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك حاجة لإزالة العقدة من عقدتها الأصلية قبل إلحاقها بعقدة أخرى). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ينفّذ مهامًا معرفة من قبل التطبيق مرتبطة بتحرير أو تحرير أو إعادة ضبط الموارد غير المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | طريقة hasChildNodes() لواجهة Node تُعيد قيمة منطقية تُشير إلى ما إذا كان الـ[`Node`](../node/) المعطى يحتوي على عقد أطفال أم لا. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | طريقة insertBefore() الخاصة بواجهة Node تُدرج عقدة قبل عقدة مرجعية كطفل لعقدة أصلية محددة. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | طريقة isDefaultNamespace() الخاصة بواجهة Node تقبل عنوان حزمة URI كوسيط. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | طريقة isEqualNode() لواجهة [`Node`](../node/) تختبر ما إذا كان عقدان متساويين. تكون العقد متساوية عندما يكون لها نفس النوع والخصائص التعريفية (بالنسبة للعناصر، يكون ذلك المعرف ID، عدد الأطفال، وما إلى ذلك)، وتطابق سماتها، وما إلى ذلك. مجموعة البيانات المحددة التي يجب أن تتطابق تختلف حسب نوعي العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() الخاصة بواجهة Node هي اسم مستعار قديم للمقارنة الصارمة ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | طريقة lookupNamespaceURI() الخاصة بواجهة Node تأخذ بادئة كمعامل وتُعيد عنوان الحزمة URI المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | طريقة lookupPrefix() الخاصة بواجهة Node تُعيد سلسلة تحتوي على البادئة لعنوان حزمة URI معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُعيد أول بادئة. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد [`Text`](../text/) على كامل عمق الشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في صيغة \"عادية\" حيث تفصل البنية فقط (مثل [`elements`](../element/)، [`comments`](../comment/)، [`processing instructions`](../processinginstruction/)، [`CDATA sections`](../cdatasection/)، و[`entity references`](../entityreference/)) بين عقد [`Text`](../text/)، أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند يطابق ما إذا كان قد تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة مستند معينة. إذا كان معامل \"normalize-characters\" لكائن [`DOMConfiguration`](../../com.aspose.html/configuration/) المرتبط بـ[`Node.ownerDocument`](../node/ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد Text بالكامل. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | يرجع العنصر الأول في المستند الذي يطابق المحدد |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | يرجع NodeList لجميع العناصر في المستند التي تطابق المحدد |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | طريقة `removeChild()` في واجهة Node تزيل عقدة فرعية من DOM وتُرجع العقدة المُزالة. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويُعيد عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../documentfragment/) الذين يُدرجون بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يُزال أولاً. |
| [toString](../../com.aspose.html.dom/node/toString/)() | يعيد سلسلة تمثل هذا الكائن. |

### انظر أيضًا

* class [DocumentFragment](../documentfragment/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
