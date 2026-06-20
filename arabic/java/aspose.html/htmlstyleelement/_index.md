---
title: "فئة HTMLStyleElement"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.HTMLStyleElement. معلومات النمط. راجع تعريف عنصر STYLE في HTML 4.01، وحدة CSS، DOM Level 2 Style Sheets and CSS، وواجهة LinkStyle في وحدة StyleSheets، DOM Level 2 Style Sheets and CSS."
type: docs

url: /ar/java/com.aspose.html/htmlstyleelement/
---
## HTMLStyleElement class

معلومات النمط. راجع تعريف العنصر STYLE في HTML 4.01، وحدة CSS [[DOM Level 2 Style Sheets and CSS](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)] وواجهة `LinkStyle` في وحدة StyleSheets [[DOM Level 2 Style Sheets and CSS](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113)].

انظر أيضًا إلى [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLStyleElement : HTMLElement, ILinkStyle
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) خريطة NamedNodeMap تحتوي على سمات هذه العقدة (إذا كانت عنصرًا) أو null otherwise. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) الخاصية القابلة للقراءة فقط baseURI لواجهة Node تُعيد عنوان URL الأساسي المطلق للمستند الذي يحتوي على العقدة. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) يُعيد العدد الحالي لعقد العناصر التي هي أبناء لهذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقدة فرعية من نوع nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) الخاصية القابلة للقراءة فقط childNodes لواجهة Node تُعيد [`NodeList`](../../com.aspose.html.collections/nodelist/) حي لعقد الأطفال للعنصر المحدد حيث تُعطى العقدة الأولى الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [getChildren](../../com.aspose.html.dom/element/children/) يُعيد عناصر الطفل للعنصر الحالي. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) يُعيد DOMTokenList حي يحتوي على الرموز المستخرجة من تحليل السمة "class". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
[getDisabled]
[setDisabled] Enables/disables the style sheet. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية القابلة للقراءة فقط firstChild لواجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم يكن للعقدة أي أطفال. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) يُعيد أول عقدة عنصر طفل لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر طفل. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية القابلة للقراءة فقط lastChild لواجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر أو عقدة نص أو عقدة تعليق. تُعيد null إذا لم يكن هناك أي عناصر طفل. |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) يعيد عقدة العنصر الفرعي الأخير لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) يعيد الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير ELEMENT_NODE و ATTRIBUTE_NODE والعقد التي تم إنشاؤها باستخدام طريقة DOM Level 1، مثل Document.createElement()، يكون هذا دائمًا null. |
[getMedia]
[setMedia] Designed for use with one or more target media. See the media attribute definition in HTML 4.01. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) معرّف URI للحزمة لهذه العقدة، أو null إذا لم يُحدّد. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) يعيد عقدة العنصر الشقيقة التالية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصرية تأتي بعده في شجرة المستند. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) خاصية nextSibling للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد العقدة التي تلي المحددة مباشرةً في [`childNodes`](../../com.aspose.html.dom/node/childnodes/) الخاصة بوالدها، أو تُعيد null إذا كانت العقدة المحددة هي العنصر الفرعي الأخير في العنصر الأب. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) اسم هذه العقدة، حسب نوعها. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) رمز يُمثّل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | خاصية nodeValue في واجهة [`Node `](../../com.aspose.html.dom/node/) تُعيد أو تُعيّن قيمة العقدة الحالية. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) خاصية ownerDocument للقراءة فقط في واجهة Node تُعيد كائن المستند الأعلى للعقدة. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) خاصية parentElement للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد العنصر الأب لعقدة DOM [`Element`](../../com.aspose.html.dom/element/)، أو null إذا لم يكن للعقدة أب، أو إذا كان أبها ليس عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُعيد أب العقدة المحددة في شجرة DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) بادئة الحزمة لهذه العقدة، أو null إذا لم تُحدّد. عندما تُعيّن كـ null، لا يؤثر التعيين. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) يعيد عقدة العنصر الشقيقة السابقة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصرية تأتي قبلها في شجرة المستند. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) خاصية previousSibling للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد العقدة التي تسبق المحددة مباشرةً في قائمة [`childNodes`](../../com.aspose.html.dom/node/firstchild/) الخاصة بوالدها، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) يعيد shadowRoot المخزن على هذا العنصر أو null إذا كان مغلقًا. |
| [getSheet](../../com.aspose.html/htmlstyleelement/sheet/) يحصل على ورقة الأنماط المرتبطة. |
| [getStyle](../../com.aspose.html/htmlelement/style/) يمثل سمة نمط تسمح للمؤلف بتطبيق معلومات النمط مباشرةً على عنصر محدد. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) اسم العنصر. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | هذه السمة تُعيد محتوى النص لهذه العقدة ونوابها. عندما تُحدّد كـ null، لا يؤثر تعيينها. عند التعيين، تُزال جميع الأطفال المحتملين لهذه العقدة، وإذا لم تكن السلسلة الجديدة فارغة أو null، تُستبدل بعقدة نصية واحدة تحتوي على السلسلة التي تم تعيينها لهذه السمة. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |
[getType]
[setType] The content type of the style sheet language. See the type attribute definition in HTML 4.01. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() في واجهة [`EventTarget `](../../com.aspose.html.dom/eventtarget/) تُعدّ دالة تُستدعى كلما تم توصيل الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | طريقة appendChild() الخاصة بواجهة Node تُضيف عقدة إلى نهاية قائمة الأطفال للعقدة الأصلية المحددة. إذا كان الطفل المُعطى إشارة إلى عقدة موجودة بالفعل في المستند، فإن appendChild() تنقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك حاجة لإزالة العقدة من عقدتها الأصلية قبل إلحاقها بعقدة أخرى). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | ينشئ جذر الظل ويربطه بالعنصر الحالي. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ينفّذ مهامًا معرفة من قبل التطبيق مرتبطة بتحرير أو تحرير أو إعادة ضبط الموارد غير المُدارة. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | يسترجع قيمة سمة بحسب الاسم. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | يعيد أسماء السمات للعنصر كمصفوفة من السلاسل. إذا لم يكن للعنصر أي سمات، فإنه يُعيد مصفوفة فارغة. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | يسترجع عقدة سمة بحسب الاسم. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | يسترجع عقدة Attr بحسب الاسم المحلي وعنوان الحزمة URI. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | يسترجع قيمة سمة بحسب الاسم المحلي وعنوان الحزمة URI. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | يعيد كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع العناصر داخل [`element`](../../com.aspose.html.dom/element/) التي لديها جميع الفئات المحددة في الوسيط. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | يعيد كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع [`elements`](../../com.aspose.html.dom/element/) ذات اسم العلامة المحدد، بترتيب المستند. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | يعيد كائن [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على جميع [`elements`](../../com.aspose.html.dom/element/) ذات الاسم المحلي وعنوان الحزمة URI المحدد، بترتيب المستند. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | يعيد true عندما تكون سمة بالاسم المحدد مُحددة على هذا العنصر أو لها قيمة افتراضية، وإلا يعيد false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | يعيد true عندما تكون سمة بالاسم المحلي وعنوان الحزمة URI المحدد مُحددة على هذا العنصر أو لها قيمة افتراضية، وإلا يعيد false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | يعيد ما إذا كانت هذه العقدة (إذا كانت عنصرًا) تحتوي على أي سمات. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | طريقة hasChildNodes() الخاصة بواجهة Node تُعيد قيمة منطقية تُشير إلى ما إذا كان الـ [`Node`](../../com.aspose.html.dom/node/) المُعطى يحتوي على عقد أطفال أم لا. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | طريقة insertBefore() الخاصة بواجهة Node تُدرج عقدة قبل عقدة مرجعية كطفل لعقدة أصلية محددة. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | طريقة isDefaultNamespace() الخاصة بواجهة Node تقبل عنوان حزمة URI كوسيط. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | طريقة isEqualNode() الخاصة بواجهة [`Node`](../../com.aspose.html.dom/node/) تختبر ما إذا كانت عقدتان متساويتان. تكون العقدتان متساويتين عندما يكون لهما نفس النوع والخصائص المحددة (بالنسبة للعناصر، قد تكون المعرف، عدد الأطفال، وما إلى ذلك)، وتطابق سماتهما، وهكذا. مجموعة نقاط البيانات التي يجب أن تتطابق تختلف حسب نوع العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() الخاصة بواجهة Node هي اسم مستعار قديم للمقارنة الصارمة ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | طريقة lookupNamespaceURI() الخاصة بواجهة Node تأخذ بادئة كمعامل وتُعيد عنوان الحزمة URI المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | طريقة lookupPrefix() الخاصة بواجهة Node تُعيد سلسلة تحتوي على البادئة لعنوان حزمة URI معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُعيد أول بادئة. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد [`Text`](../../com.aspose.html.dom/text/) في العمق الكامل للشجرة الفرعية تحت هذا الـ Node، بما في ذلك عقد السمات، في صيغة "عادية" حيث تفصل البنية فقط (مثلًا، [`elements`](../../com.aspose.html.dom/element/)، [`comments`](../../com.aspose.html.dom/comment/)، [`processing instructions`](../../com.aspose.html.dom/processinginstruction/)، [`CDATA sections`](../../com.aspose.html.dom/cdatasection/)، و[`entity references`](../../com.aspose.html.dom/entityreference/)) عقد [`Text`](../../com.aspose.html.dom/text/)، أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للوثيقة هو نفسه كما لو تم حفظها وإعادة تحميلها، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة وثيقة معينة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../configuration/) المرتبط بـ [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد Text بالكامل. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | يرجع العنصر الأول في المستند الذي يطابق المحدد |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | يرجع NodeList لجميع العناصر في المستند التي تطابق المحدد |
| [remove](../../com.aspose.html.dom/element/remove/)() | يزيل هذا المثيل. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | يزيل سمةً بالاسم. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | يزيل عقدة السمة المحددة. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | يزيل سمةً بالاسم المحلي وعنوان URI للحزمة. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | طريقة `removeChild()` في واجهة Node تزيل عقدة فرعية من DOM وتُرجع العقدة المُزالة. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويُرجع عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) الذين يُدرجون بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يتم إزالته أولاً. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | يضيف سمةً جديدة. إذا كانت سمة بهذا الاسم موجودة بالفعل في العنصر، يتم تغيير قيمتها لتصبح قيمة المعامل value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | يضيف عقدة سمة جديدة. إذا كانت سمة بهذا الاسم (nodeName) موجودة بالفعل في العنصر، يتم استبدالها بالجديدة. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | يضيف سمةً جديدة. إذا كانت سمة بهذا الاسم المحلي وعنوان URI للحزمة موجودة بالفعل في العنصر، يتم استبدالها بالجديدة. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | يضيف سمةً جديدة. إذا كانت سمة بنفس الاسم المحلي وعنوان URI للحزمة موجودة بالفعل على العنصر، يتم تغيير بادئتها لتصبح الجزء البادئ من qualifiedName، وتُغيّر قيمتها لتصبح قيمة المعامل value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | إذا لم يُعطَ force، فإنها "تبدّل" qualifiedName، بإزالته إذا كان موجودًا وإضافته إذا لم يكن موجودًا. إذا كان force صحيحًا، تُضيف qualifiedName. إذا كان force خاطئًا، تُزيل qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | إذا لم يُعطَ force، فإنها "تبدّل" qualifiedName، بإزالته إذا كان موجودًا وإضافته إذا لم يكن موجودًا. إذا كان force صحيحًا، تُضيف qualifiedName. إذا كان force خاطئًا، تُزيل qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | يعيد سلسلة تمثل هذا الكائن. |

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
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | الحصول أو تعيين معالج الحدث لحدث OnInvalid. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | الحصول أو تعيين معالج الحدث لحدث OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | الحصول أو تعيين معالج الحدث لحدث OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | الحصول أو تعيين معالج الحدث لحدث OnKeyUp. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | الحصول أو تعيين معالج الحدث لحدث OnLoad. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | الحصول أو تعيين معالج الحدث لحدث OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | الحصول أو تعيين معالج الحدث لحدث OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | الحصول أو تعيين معالج الحدث لحدث OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | الحصول أو تعيين معالج الحدث لحدث OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | الحصول أو تعيين معالج الحدث لحدث OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | الحصول أو تعيين معالج الحدث لحدث OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | الحصول أو تعيين معالج الحدث لحدث OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | الحصول أو تعيين معالج الحدث لحدث OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | الحصول أو تعيين معالج الحدث لحدث OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | الحصول أو تعيين معالج الحدث لحدث OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | الحصول أو تعيين معالج الحدث لحدث OnMouseWheel. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | الحصول أو تعيين معالج الحدث لحدث OnPause. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | الحصول أو تعيين معالج الحدث لحدث OnPlay. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | الحصول أو تعيين معالج الحدث لحدث OnPlaying. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | الحصول أو تعيين معالج الحدث لحدث OnProgress. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | الحصول أو تعيين معالج الحدث لحدث OnRateChange. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | الحصول أو تعيين معالج الحدث لحدث OnReset. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | الحصول أو تعيين معالج الحدث لحدث OnResize. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | الحصول أو تعيين معالج الحدث لحدث OnScroll. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | يحصل أو يضبط معالج الحدث لحدث OnSeeked. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | يحصل أو يضبط معالج الحدث لحدث OnSeeking. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | يحصل أو يضبط معالج الحدث لحدث OnSelect. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | يحصل أو يضبط معالج الحدث لحدث OnShow. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | يحصل أو يضبط معالج الحدث لحدث OnStalled. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | يحصل أو يضبط معالج الحدث لحدث OnSubmit. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | يحصل أو يضبط معالج الحدث لحدث OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | يحصل أو يضبط معالج الحدث لحدث OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | يحصل أو يضبط معالج الحدث لحدث OnToggle. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | يحصل أو يضبط معالج الحدث لحدث OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | يحصل أو يضبط معالج الحدث لحدث OnWaiting. |

### انظر أيضًا

* class [HTMLElement](../htmlelement/)
* interface [ILinkStyle](../../com.aspose.html.dom.css/ilinkstyle/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
