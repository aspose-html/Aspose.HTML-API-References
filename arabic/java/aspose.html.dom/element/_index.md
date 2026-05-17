---
title: "فئة Element"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.Element. تمثل واجهة Element عنصرًا في مستند HTML أو XML"
type: docs

url: /ar/java/com.aspose.html.dom/element/
---
## Element class

واجهة Element تمثل عنصرًا في مستند HTML أو XML.

```java
public class Element : Node, IChildNode, IParentNode
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Element](element/)(QualifiedName, Document) | يُهيئ نسخة جديدة من فئة `Element`. لا تستدعِ هذا المُنشئ مباشرةً، استخدم [`CreateElement`](../document/createelement/) أو [`CreateElementNS`](../document/createelementns/). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) خريطة NamedNodeMap تحتوي على سمات هذه العقدة (إذا كانت عنصرًا) أو null خلاف ذلك. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) الخاصية للقراءة فقط baseURI في واجهة Node تُعيد عنوان URL الأساسي المطلق للمستند الذي يحتوي على العقدة. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) تُعيد العدد الحالي لعقد العناصر التي هي أبناء لهذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقدة فرعية من نوع nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) الخاصية للقراءة فقط childNodes في واجهة Node تُعيد [`NodeList`](../../com.aspose.html.collections/nodelist/) حي لعقد الأطفال للعنصر المعطى حيث تُعطى العقدة الأولى الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [getChildren](../../com.aspose.html.dom/element/children/) تُعيد عناصر الطفل للعنصر الحالي. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) تُعيد DOMTokenList حي يحتوي على الرموز المستخرجة من تحليل السمة \"class\". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية read-only firstChild لواجهة [`Node`](../node/) تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم يكن للعقدة أي أطفال. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) تُعيد أول عقدة عنصر طفل لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر طفل. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية read-only lastChild لواجهة [`Node`](../node/) تُعيد آخر طفل للعقدة. إذا كان أبُها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر أو عقدة نص أو عقدة تعليق. تُعيد null إذا لم توجد عناصر طفل. |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) يرجع عقدة العنصر الطفل الأخيرة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر طفل. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) يرجع الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير ELEMENT_NODE و ATTRIBUTE_NODE والعقد التي تم إنشاؤها باستخدام طريقة DOM Level 1، مثل Document.createElement()، يكون هذا دائمًا null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) URI الحزمة لهذه العقدة، أو null إذا لم يُحدد. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) يرجع عقدة العنصر الشقيقة التالية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي بعده في شجرة المستند. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) الخاصية read-only nextSibling لواجهة [`Node`](../node/) تُعيد العقدة التي تلي مباشرةً المحددة في [`childNodes`](../node/childnodes/) للوالد، أو تُعيد null إذا كانت العقدة المحددة هي آخر طفل في العنصر الأب. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) اسم هذه العقدة، حسب نوعها. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) رمز يمثل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | خاصية nodeValue للواجهة [`Node `](../node/) تُرجع أو تُعيّن قيمة العقدة الحالية. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) خاصية ownerDocument للقراءة فقط في واجهة Node تُرجع كائن المستند الأعلى المستوى للعقدة. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) الخاصية القابلة للقراءة فقط parentElement لواجهة [`Node`](../node/) تُعيد العنصر `Element` الأب لعقدة DOM، أو null إذا لم يكن للعقدة أب، أو إذا لم يكن أبها عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُرجع أب العقدة المحددة في شجرة DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) بادئة الحزمة لهذه العقدة، أو null إذا لم تُحدد. عندما تُحدد بأنها null، لا يؤثر تعيينها. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) يرجع عقدة العنصر الشقيقة السابقة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي قبلها في شجرة المستند. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) الخاصية read-only previousSibling لواجهة [`Node`](../node/) تُعيد العقدة التي تسبق مباشرةً المحددة في قائمة [`childNodes`](../node/firstchild/) للوالد، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) يرجع shadowRoot المخزن على هذا العنصر أو null إذا كان مغلقًا. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) اسم العنصر. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | هذه السمة تُرجع محتوى النص لهذه العقدة ونسلها. عندما تُحدد بأنها null، لا يؤثر تعيينها. عند التعيين، تُزال أي أطفال محتملين قد تكون للعقدة، وإذا لم تكن السلسلة الجديدة فارغة أو null، تُستبدل بعقدة نصية واحدة تحتوي على السلسلة التي تم تعيين هذه السمة إليها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() لواجهة [`EventTarget `](../eventtarget/) تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | تضيف طريقة appendChild() في واجهة Node عقدة إلى نهاية قائمة الأطفال لعقدة أب محددة. إذا كان الطفل المعطى إشارة إلى عقدة موجودة بالفعل في المستند، فإن appendChild() تنقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك ضرورة لإزالة العقدة من عقدة الأب قبل إلحاقها بعقدة أخرى). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | ينشئ جذرًا ظليًّا ويُرفقه بالعنصر الحالي. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | تُعيد طريقة cloneNode() في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضًا أم لا. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | تُعيد طريقة cloneNode() في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضًا أم لا. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ[`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) المحدد، (متزامنًا) مستدعيًا مستمعي الحدث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | يُجري مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | يسترجع قيمة سمة حسب الاسم. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | يرجع أسماء السمات للعنصر كمصفوفة من السلاسل. إذا لم يكن للعنصر أي سمات، فإنه يُرجع مصفوفة فارغة. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | يسترجع عقدة سمة حسب الاسم. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | يسترجع عقدة Attr حسب الاسم المحلي وURI الحزمة. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | يسترجع قيمة سمة حسب الاسم المحلي وURI الحزمة. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | يعيد كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع العناصر داخل `element` التي تمتلك جميع الفئات المحددة في المعامل. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | يعيد كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع `elements` ذات اسم الوسم المحدد، بترتيب المستند. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | يعيد كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع `elements` التي لها اسم محلي وسلسلة URI للحزمة المحددة، بترتيب المستند. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | يرجع true عندما تكون سمة بالاسم المحدد مُحددة على هذا العنصر أو لها قيمة افتراضية، وإلا يرجع false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | يرجع true عندما تكون سمة بالاسم المحلي وURI الحزمة المحددين مُحددة على هذا العنصر أو لها قيمة افتراضية، وإلا يرجع false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | يرجع ما إذا كانت هذه العقدة (إذا كانت عنصرًا) لديها أي سمات. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | طريقة hasChildNodes() لواجهة Node تُعيد قيمة منطقية تُشير إلى ما إذا كان الـ[`Node`](../node/) المعطى يحتوي على عقد أطفال أم لا. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | تُدرج طريقة insertBefore() في واجهة Node عقدة قبل عقدة مرجعية كطفل لعقدة أب محددة. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | تقبل طريقة isDefaultNamespace() في واجهة Node URI الحزمة كمعامل. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | طريقة isEqualNode() لواجهة [`Node`](../node/) تختبر ما إذا كانت عقدتان متساويتان. تكون العقدتان متساويتين عندما يكون لهما نفس النوع، والخصائص المعرّفة (للعناصر، يكون ذلك معرفهما، عدد الأطفال، وما إلى ذلك)، وتطابق سماتها، وما إلى ذلك. مجموعة البيانات المحددة التي يجب أن تتطابق تختلف حسب نوعي العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() في واجهة Node هي اسم مستعار قديم للمشغل الصارم ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | تأخذ طريقة lookupNamespaceURI() في واجهة Node بادئة كمعامل وتُعيد URI الحزمة المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | ترجع طريقة lookupPrefix() في واجهة Node سلسلة تحتوي على البادئة لURI حزمة معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُرجع أول بادئة. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد [`Text`](../text/) في العمق الكامل للشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في شكل "normal" حيث تفصل البنية فقط (مثل `elements`، [`comments`](../comment/)، [`processing instructions`](../processinginstruction/)، [`CDATA sections`](../cdatasection/)، و[`entity references`](../entityreference/)) بين عقد [`Text`](../text/)، أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة المستند المحددة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../../com.aspose.html/configuration/) المرتبط بـ [`Node.ownerDocument`](../node/ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد Text بالكامل. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | يعيد العنصر الأول في المستند الذي يطابق المحدد |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | يعيد NodeList بجميع العناصر في المستند التي تطابق المحدد |
| [remove](../../com.aspose.html.dom/element/remove/)() | يزيل هذه المثيلة. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | يزيل سمةً بالاسم. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | يزيل عقدة السمة المحددة. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | يزيل سمةً بالاسم المحلي وURI الحزمة. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | طريقة removeChild() في واجهة Node تزيل عقدةً فرعيةً من DOM وتعيد العقدة التي أزيلت. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويُعيد عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../documentfragment/) الذين يُدرجون بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يتم إزالته أولاً. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | يضيف سمة جديدة. إذا كانت سمة بهذا الاسم موجودة بالفعل في العنصر، يتم تغيير قيمتها لتصبح قيمة معلمة value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | يضيف عقدة سمة جديدة. إذا كانت سمة بهذا الاسم (nodeName) موجودة بالفعل في العنصر، يتم استبدالها بالجديدة. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | يضيف سمة جديدة. إذا كانت سمة بهذا الاسم المحلي وURI الحزمة موجودة بالفعل في العنصر، يتم استبدالها بالجديدة. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | يضيف سمة جديدة. إذا كانت سمة بنفس الاسم المحلي وURI الحزمة موجودة بالفعل على العنصر، يتم تغيير بادئتها لتصبح الجزء البادئ من qualifiedName، وتُغيّر قيمتها لتصبح قيمة المعامل value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute)(String) | إذا لم يتم تقديم force، فإنها "تبدّل" qualifiedName، بإزالته إذا كان موجودًا وإضافته إذا لم يكن موجودًا. إذا كان force صحيحًا، تُضيف qualifiedName. إذا كان force خاطئًا، تُزيل qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute_1)(String, bool) | إذا لم يتم تقديم force، فإنها "تبدّل" qualifiedName، بإزالته إذا كان موجودًا وإضافته إذا لم يكن موجودًا. إذا كان force صحيحًا، تُضيف qualifiedName. إذا كان force خاطئًا، تُزيل qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | يرجع سلسلة تمثل هذا الكائن. |

### انظر أيضًا

* class [Node](../node/)
* interface [IChildNode](../ichildnode/)
* interface [IParentNode](../iparentnode/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
