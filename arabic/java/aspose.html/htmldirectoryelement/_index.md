---
title: "فئة HTMLDirectoryElement"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.HTMLDirectoryElement. قائمة الدليل. راجع تعريف العنصر DIR في HTML 4.01. هذا العنصر مهمل في HTML 4.01"
type: docs

url: /ar/java/com.aspose.html/htmldirectoryelement/
---
## HTMLDirectoryElement class

قائمة الدليل. راجع تعريف العنصر DIR في HTML 4.01. هذا العنصر مهمل في HTML 4.01.

انظر أيضاً إلى [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLDirectoryElement : HTMLElement
```

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
[getCompact]
[setCompact] Reduce spacing between list items. See the compact attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية للقراءة فقط firstChild في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم يكن للعقدة أي أطفال. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) تُعيد أول عقدة عنصر طفل لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر طفل. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية للقراءة فقط lastChild في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر، أو عقدة نص، أو عقدة تعليق. تُعيد null إذا لم يكن هناك أي عناصر طفل. |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) يرجع عقدة العنصر الطفل الأخيرة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر طفل. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) يرجع الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير ELEMENT_NODE و ATTRIBUTE_NODE والعقد التي تم إنشاؤها باستخدام طريقة DOM Level 1، مثل Document.createElement()، يكون هذا دائمًا null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) URI الحزمة لهذه العقدة، أو null إذا لم يُحدد. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) يرجع عقدة العنصر الشقيقة التالية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي بعده في شجرة المستند. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) خاصية nextSibling للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُرجع العقدة التي تلي المحددة مباشرةً في [`childNodes`](../../com.aspose.html.dom/node/childnodes/) الخاصة بالوالد، أو تُرجع null إذا كانت العقدة المحددة هي الطفل الأخير في العنصر الأب. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) اسم هذه العقدة، حسب نوعها. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) رمز يمثل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | خاصية nodeValue في واجهة [`Node `](../../com.aspose.html.dom/node/) تُرجع أو تعين قيمة العقدة الحالية. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) خاصية ownerDocument للقراءة فقط في واجهة Node تُرجع كائن المستند الأعلى المستوى للعقدة. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) خاصية parentElement للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُرجع العنصر الأب لعقدة DOM [`Element`](../../com.aspose.html.dom/element/)، أو null إذا لم يكن للعقدة أب، أو إذا كان أبها ليس عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُرجع أب العقدة المحددة في شجرة DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) بادئة الحزمة لهذه العقدة، أو null إذا لم تُحدد. عندما تُحدد بأنها null، لا يؤثر تعيينها. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) يرجع عقدة العنصر الشقيقة السابقة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي قبلها في شجرة المستند. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) خاصية previousSibling للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُرجع العقدة التي تسبق المحددة مباشرةً في قائمة [`childNodes`](../../com.aspose.html.dom/node/firstchild/) الخاصة بالوالد، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) يرجع shadowRoot المخزن على هذا العنصر أو null إذا كان مغلقًا. |
| [getStyle](../../com.aspose.html/htmlelement/style/) يمثل سمة نمط تسمح للمؤلف بتطبيق معلومات النمط مباشرةً على عنصر محدد. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) اسم العنصر. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | هذه السمة تُرجع محتوى النص لهذه العقدة ونسلها. عندما تُحدد بأنها null، لا يؤثر تعيينها. عند التعيين، تُزال أي أطفال محتملين قد تكون للعقدة، وإذا لم تكن السلسلة الجديدة فارغة أو null، تُستبدل بعقدة نصية واحدة تحتوي على السلسلة التي تم تعيين هذه السمة إليها. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() في واجهة [`EventTarget `](../../com.aspose.html.dom/eventtarget/) تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
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
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | يرجع كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع العناصر داخل [`element`](../../com.aspose.html.dom/element/) التي تمتلك جميع الفئات المحددة في الوسيط. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | يرجع كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع [`elements`](../../com.aspose.html.dom/element/) ذات اسم علامة معين، بترتيب المستند. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | يرجع كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع [`elements`](../../com.aspose.html.dom/element/) ذات الاسم المحلي وURI الحزمة المحددين، بترتيب المستند. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | يرجع true عندما تكون سمة بالاسم المحدد مُحددة على هذا العنصر أو لها قيمة افتراضية، وإلا يرجع false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | يرجع true عندما تكون سمة بالاسم المحلي وURI الحزمة المحددين مُحددة على هذا العنصر أو لها قيمة افتراضية، وإلا يرجع false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | يرجع ما إذا كانت هذه العقدة (إذا كانت عنصرًا) لديها أي سمات. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | تُعيد طريقة hasChildNodes() في واجهة Node قيمة منطقية تُشير إلى ما إذا كان الـ[`Node`](../../com.aspose.html.dom/node/) المعطى يحتوي على عقد أطفال أم لا. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | تُدرج طريقة insertBefore() في واجهة Node عقدة قبل عقدة مرجعية كطفل لعقدة أب محددة. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | تقبل طريقة isDefaultNamespace() في واجهة Node URI الحزمة كمعامل. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | تختبر طريقة isEqualNode() في واجهة [`Node`](../../com.aspose.html.dom/node/) ما إذا كانت عقدتان متساويتان. تكون العقدتان متساويتين عندما يكون لهما نفس النوع والخصائص المحددة (بالنسبة للعناصر، قد يكون ذلك المعرف، عدد الأطفال، وما إلى ذلك)، وتطابق سماتهما، وما إلى ذلك. مجموعة البيانات المحددة التي يجب أن تتطابق تختلف حسب أنواع العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() في واجهة Node هي اسم مستعار قديم للمشغل الصارم ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | تأخذ طريقة lookupNamespaceURI() في واجهة Node بادئة كمعامل وتُعيد URI الحزمة المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | ترجع طريقة lookupPrefix() في واجهة Node سلسلة تحتوي على البادئة لURI حزمة معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُرجع أول بادئة. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد [`Text`](../../com.aspose.html.dom/text/) في العمق الكامل للشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في شكل "عادي" حيث تفصل فقط البنية (مثلًا، [`elements`](../../com.aspose.html.dom/element/)، [`comments`](../../com.aspose.html.dom/comment/)، [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), و[`entity references`](../../com.aspose.html.dom/entityreference/)) عقد [`Text`](../../com.aspose.html.dom/text/)، أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM لمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة المستند المحددة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../configuration/) المرتبط بـ [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد Text بالكامل. |
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
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويعيد عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) الذين يتم إدراجهم بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، فسيتم إزالته أولاً. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | يضيف سمة جديدة. إذا كانت سمة بهذا الاسم موجودة بالفعل في العنصر، يتم تغيير قيمتها لتصبح قيمة معلمة value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | يضيف عقدة سمة جديدة. إذا كانت سمة بهذا الاسم (nodeName) موجودة بالفعل في العنصر، يتم استبدالها بالجديدة. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | يضيف سمة جديدة. إذا كانت سمة بهذا الاسم المحلي وURI الحزمة موجودة بالفعل في العنصر، يتم استبدالها بالجديدة. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | يضيف سمة جديدة. إذا كانت سمة بنفس الاسم المحلي وURI الحزمة موجودة بالفعل على العنصر، يتم تغيير بادئتها لتصبح الجزء البادئ من qualifiedName، وتُغيّر قيمتها لتصبح قيمة المعامل value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | إذا لم يتم تقديم force، فإنها "تبدّل" qualifiedName، بإزالته إذا كان موجودًا وإضافته إذا لم يكن موجودًا. إذا كان force صحيحًا، تُضيف qualifiedName. إذا كان force خاطئًا، تُزيل qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | إذا لم يتم تقديم force، فإنها "تبدّل" qualifiedName، بإزالته إذا كان موجودًا وإضافته إذا لم يكن موجودًا. إذا كان force صحيحًا، تُضيف qualifiedName. إذا كان force خاطئًا، تُزيل qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | يرجع سلسلة تمثل هذا الكائن. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | يحصل أو يعيّن معالج الحدث لحدث OnAbort. |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | يحصل أو يعيّن معالج الحدث لحدث OnBlur. |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | يحصل أو يعيّن معالج الحدث لحدث OnCancel. |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | يحصل أو يعيّن معالج الحدث لحدث OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | يحصل أو يعيّن معالج الحدث لحدث OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | يحصل أو يعيّن معالج الحدث لحدث OnChange. |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | يحصل أو يعيّن معالج الحدث لحدث OnClick. |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | يحصل أو يعيّن معالج الحدث لحدث OnCueChange. |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | يحصل أو يعيّن معالج الحدث لحدث OnDblClick. |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | يحصل أو يعيّن معالج الحدث لحدث OnDurationChange. |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | يحصل أو يعيّن معالج الحدث لحدث OnEmptied. |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | يحصل أو يعيّن معالج الحدث لحدث OnEnded. |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | يحصل أو يعيّن معالج الحدث لحدث OnError. |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | يحصل أو يعيّن معالج الحدث لحدث OnFocus. |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | يحصل أو يعيّن معالج الحدث لحدث OnInput. |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | الحصول أو تعيين معالج الحدث لـ OnInvalid. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | الحصول أو تعيين معالج الحدث لـ OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | الحصول أو تعيين معالج الحدث لـ OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | الحصول أو تعيين معالج الحدث لـ OnKeyUp. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | الحصول أو تعيين معالج الحدث لـ OnLoad. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | الحصول أو تعيين معالج الحدث لـ OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | الحصول أو تعيين معالج الحدث لـ OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | الحصول أو تعيين معالج الحدث لـ OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | الحصول أو تعيين معالج الحدث لـ OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | الحصول أو تعيين معالج الحدث لـ OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | الحصول أو تعيين معالج الحدث لـ OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | الحصول أو تعيين معالج الحدث لـ OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | الحصول أو تعيين معالج الحدث لـ OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | الحصول أو تعيين معالج الحدث لـ OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | الحصول أو تعيين معالج الحدث لـ OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | الحصول أو تعيين معالج الحدث لـ OnMouseWheel. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | الحصول أو تعيين معالج الحدث لـ OnPause. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | الحصول أو تعيين معالج الحدث لـ OnPlay. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | الحصول أو تعيين معالج الحدث لـ OnPlaying. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | الحصول أو تعيين معالج الحدث لـ OnProgress. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | الحصول أو تعيين معالج الحدث لـ OnRateChange. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | الحصول أو تعيين معالج الحدث لـ OnReset. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | الحصول أو تعيين معالج الحدث لـ OnResize. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | الحصول أو تعيين معالج الحدث لـ OnScroll. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | الحصول أو تعيين معالج الحدث لحدث OnSeeked. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | الحصول أو تعيين معالج الحدث لحدث OnSeeking. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | الحصول أو تعيين معالج الحدث لحدث OnSelect. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | الحصول أو تعيين معالج الحدث لحدث OnShow. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | الحصول أو تعيين معالج الحدث لحدث OnStalled. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | الحصول أو تعيين معالج الحدث لحدث OnSubmit. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | الحصول أو تعيين معالج الحدث لحدث OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | الحصول أو تعيين معالج الحدث لحدث OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | الحصول أو تعيين معالج الحدث لحدث OnToggle. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | الحصول أو تعيين معالج الحدث لحدث OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | الحصول أو تعيين معالج الحدث لحدث OnWaiting. |

### انظر أيضًا

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
