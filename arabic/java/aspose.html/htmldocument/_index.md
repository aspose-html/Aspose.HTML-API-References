---
title: "فئة HTMLDocument"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.HTMLDocument. تمثل مستند HTML. تُضاف جميع كائنات HTML ذات المستوى الأعلى إلى هذا الكائن. تمثل هذه الفئة صفحة HTML كما نراها في المتصفح. تُضاف جميع النماذج والجداول والسكربتات ... إلى صفحة HTML عبر واجهات هذه الفئة. HTMLDocument هو تنفيذ HTML لأكثر واجهة عامة للمستند، وكلاهما نقطة أساسية أو جذرية لنموذج كائن المستند (DOM - Document Object Model). تتوافق هذه المفاهيم بالكامل مع أساسيات أو معايير تطوير الويب الرسمية. لأغراض تطوير الويب يمكنك عمومًا اعتبار HTMLDocument كاسم مستعار لـ Document الذي يُبنى عليه HTMLDocument."
type: docs

url: /ar/java/com.aspose.html/htmldocument/
---
## HTMLDocument class

يمثل مستند HTML. تُضاف جميع كائنات HTML ذات المستوى الأعلى إلى هذا الكائن. تمثل هذه الفئة صفحة HTML كما نراها في المتصفح. تُضاف جميع النماذج والجداول والسكريبتات ... إلى صفحة HTML عبر واجهات هذه الفئة. [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) هو تنفيذ HTML لأكثر واجهة [Document](https://dom.spec.whatwg.org/#document) عمومية، وكلاهما نقطة أساسية أو جذرية لـ [DOM](https://dom.spec.whatwg.org/) - نموذج كائن المستند. هذه المفاهيم تتوافق تمامًا مع أساسيات أو معايير تطوير الويب الرسمية. لأغراض تطوير الويب، يمكنك عمومًا اعتبار HTMLDocument كاسم مستعار لـ Document، الذي يُبنى عليه HTMLDocument.

```java
public class HTMLDocument : Document, IDocumentCSS
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | يقوم مُنشئ HTMLDocument بإنشاء كائن مستند HTML جديد يكون صفحة ويب محمَّلة في المتصفح وتعمل كنقطة دخول إلى محتوى الصفحة. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | يقوم مُنشئ HTMLDocument بإنشاء كائن مستند HTML جديد يكون صفحة ويب محمَّلة في المتصفح وتعمل كنقطة دخول إلى محتوى الصفحة. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | ينشئ مستند HTML من كائن [`RequestMessage`](../../com.aspose.html.net/requestmessage/). |
| [HTMLDocument](htmldocument/#constructor_10)(String) | يقوم بتحميل مستند HTML من عنوان. |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | يقوم بتحميل مستند HTML من عنوان URL. |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | ينشئ مستند HTML من كائن [RequestMessage](T:com.aspose.html.net.RequestMessage). |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, String) | ينشئ مستند HTML من محتوى [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) مع base-uri محدد يُستخدم لحل مسار الموارد النسبية. |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | ينشئ مستند HTML من محتوى [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) مع base-uri محدد يُستخدم لحل مسار الموارد النسبية. |
| [HTMLDocument](htmldocument/#constructor_11)(String, Configuration) | يقوم بتحميل مستند HTML من عنوان مع إعدادات تكوين البيئة المحددة. |
| [HTMLDocument](htmldocument/#constructor_14)(String, String) | ينشئ مستند HTML من محتوى سلسلة (String) مع base-uri محدد. |
| [HTMLDocument](htmldocument/#constructor_12)(String, Url) | ينشئ مستند HTML من محتوى سلسلة (String) مع base-uri محدد. |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | يقوم بتحميل مستند HTML من عنوان URL مع إعدادات تكوين البيئة المحددة. |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, String, Configuration) | ينشئ مستند HTML من محتوى [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) مع base-uri محدد وإعدادات تكوين البيئة. |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | ينشئ مستند HTML من محتوى [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) مع base-uri محدد وإعدادات تكوين البيئة. |
| [HTMLDocument](htmldocument/#constructor_15)(String, String, Configuration) | ينشئ مستند HTML من محتوى سلسلة (String) مع base-uri محدد وإعدادات تكوين البيئة. |
| [HTMLDocument](htmldocument/#constructor_13)(String, Url, Configuration) | ينشئ مستند HTML من محتوى سلسلة (String) مع base-uri محدد وإعدادات تكوين البيئة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAnchors](../../com.aspose.html/htmldocument/anchors/) مجموعة من جميع عناصر الارتساء (`A`) في المستند التي لها قيمة لخاصية `name`. لأسباب التوافق مع الإصدارات السابقة، تحتوي مجموعة الارتساء المرجعة فقط على تلك التي تم إنشاؤها باستخدام خاصية `name`، وليس تلك التي تم إنشاؤها باستخدام خاصية `id`. لاحظ أنه في [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)]، لا تحمل خاصية `name` (انظر القسم 4.10) أي معنى وتوجد فقط لأغراض الوكلاء المستخدمين القديمين: تُستبدل بخاصية `id`. يجب على المستخدمين تفضيل آليات التكرار التي يوفرها [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] بدلاً من ذلك. |
| [getApplets](../../com.aspose.html/htmldocument/applets/) مجموعة من جميع عناصر `OBJECT` التي تشمل التطبيقات الصغيرة (applets) وعناصر `APPLET` (المهملة) في المستند. |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) عنوان URI الأساسي المطلق لهذا العقدة أو Null إذا لم يتمكن التنفيذ من الحصول على URI مطلق. |
[getBody]
[setBody] The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) يحصل على ترميز المستند. |
| [getCharset](../../com.aspose.html.dom/document/charset/) يحصل على ترميز المستند. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) يرجع العدد الحالي لعقد العنصر التي هي أبناء لهذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقد فرعية من نوع nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) الخاصية القابلة للقراءة فقط childNodes لواجهة Node تُعيد [`NodeList`](../../com.aspose.html.collections/nodelist/) حي لعقد الأطفال للعنصر المحدد حيث تُعطى العقدة الأولى الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [getChildren](../../com.aspose.html.dom/document/children/) يرجع العناصر الفرعية. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) يحصل على نوع محتوى المستند. |
| [getContext](../../com.aspose.html.dom/document/context/) يحصل على سياق التصفح الحالي. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) خاصية defaultView IDL لواجهة Document، عند الحصول عليها، يجب أن تُعيد كائن WindowProxy لسياق تصفح هذا المستند إذا كان لهذا المستند سياق تصفح مرتبط، أو null خلاف ذلك. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) إعلان نوع المستند المرتبط بهذا المستند. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) هذه خاصية مريحة تسمح بالوصول المباشر إلى العقدة الفرعية التي هي عنصر المستند للمستند. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) موقع المستند أو null إذا كان غير معرف أو إذا تم إنشاء المستند باستخدام DOMImplementation.createDocument. |
| [getDomain](../../com.aspose.html/htmldocument/domain/) اسم النطاق الخاص بالخادم الذي قدم المستند، أو `null` إذا تعذر تحديد الخادم باسم نطاق. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية القابلة للقراءة فقط firstChild لواجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم يكن للعقدة أي أطفال. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) يرجع أول عقدة عنصر فرعي لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getForms](../../com.aspose.html/htmldocument/forms/) مجموعة من جميع نماذج المستند. |
| [getImages](../../com.aspose.html/htmldocument/images/) مجموعة من جميع عناصر `IMG` في المستند. يقتصر السلوك على عناصر `IMG` للتوافق مع الإصدارات السابقة. كما يُقترح في [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)]، لإدراج الصور قد يستخدم المؤلفون عنصر `OBJECT` أو عنصر `IMG`. لذلك يُنصح بعدم استخدام هذه الخاصية للعثور على الصور في المستند بل استخدام `getElementsByTagName` مع HTML 4.01 أو `getElementsByTagNameNS` مع XHTML 1.0. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) كائن DOMImplementation الذي يدير هذا المستند. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) يحصل على ترميز المستند. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية القابلة للقراءة فقط lastChild لواجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر أو عقدة نص أو عقدة تعليق. تُعيد null إذا لم يكن هناك أي عناصر طفل. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) يرجع آخر عقدة عنصر فرعي لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getLinks](../../com.aspose.html/htmldocument/links/) مجموعة من جميع عناصر `AREA` وعناصر الارتساء (`A`) في المستند التي لها قيمة لخاصية `href`. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) يرجع الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) و[`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة من مستوى DOM 1، مثل [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/)، يكون هذا دائمًا null. |
| [getLocation](../../com.aspose.html.dom/document/location/) موقع المستند. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) خاصية Element.packageURI للقراءة فقط تُعيد URI الحزمة للعنصر، أو null إذا لم يكن العنصر في حزمة. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) يرجع عقدة العنصر الشقيقة التالية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة من العناصر تأتي بعده في شجرة المستند. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) خاصية nextSibling للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد العقدة التي تلي المحددة مباشرةً في [`childNodes`](../../com.aspose.html.dom/node/childnodes/) الخاصة بوالدها، أو تُعيد null إذا كانت العقدة المحددة هي العنصر الفرعي الأخير في العنصر الأب. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) اسم هذه العقدة، حسب نوعها. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) رمز يمثل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | خاصية nodeValue في واجهة [`Node `](../../com.aspose.html.dom/node/) تُعيد أو تُعيّن قيمة العقدة الحالية. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) يحصل على أصل المستند. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) يحصل على المستند المالك. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) خاصية parentElement للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد العنصر الأب لعقدة DOM [`Element`](../../com.aspose.html.dom/element/)، أو null إذا لم يكن للعقدة أب، أو إذا كان أبها ليس عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُعيد أب العقدة المحددة في شجرة DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | خاصية prefix للقراءة فقط تُعيد بادئة الحزمة للعنصر المحدد، أو null إذا لم تُحدد أي بادئة. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) يرجع عقدة العنصر الشقيقة السابقة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة من العناصر تأتي قبلها في شجرة المستند. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) خاصية previousSibling للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد العقدة التي تسبق المحددة مباشرةً في قائمة [`childNodes`](../../com.aspose.html.dom/node/firstchild/) الخاصة بوالدها، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) يرجع حالة جاهزية المستند. "loading" أثناء تحميل المستند، "interactive" بمجرد الانتهاء من التحليل لكنه لا يزال يحمل الموارد الفرعية، و"complete" بمجرد اكتماله. |
| [getReferrer](../../com.aspose.html/htmldocument/referrer/) يُعيد عنوان URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] للصفحة التي ربطت بهذه الصفحة. تكون القيمة سلسلة فارغة إذا انتقل المستخدم إلى الصفحة مباشرة (ليس عبر رابط، بل على سبيل المثال عبر إشارة مرجعية). |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) قائمة تحتوي على جميع أوراق الأنماط المرتبطة صراحةً أو المدمجة في المستند. بالنسبة لمستندات HTML، يتضمن ذلك أوراق الأنماط الخارجية، المضمنة عبر عنصر HTML LINK، وعناصر STYLE المضمنة. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | خاصية textContent لواجهة [`Node`](../../com.aspose.html.dom/node/) تمثل محتوى النص للعقدة ونسلها. |
[getTitle]
[setTitle] The title of a document as specified by the `TITLE` element in the head of the document. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() في واجهة [`EventTarget `](../../com.aspose.html.dom/eventtarget/) تُعدّ دالة تُستدعى كلما تم توصيل الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | طريقة addEventListener() الخاصة بـ [EventTarget ](T:com.aspose.html.dom.EventTarget)interface تُعدّ دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | طريقة appendChild() الخاصة بواجهة Node تُضيف عقدة إلى نهاية قائمة الأطفال للعقدة الأصلية المحددة. إذا كان الطفل المُعطى إشارة إلى عقدة موجودة بالفعل في المستند، فإن appendChild() تنقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك حاجة لإزالة العقدة من عقدتها الأصلية قبل إلحاقها بعقدة أخرى). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | طريقة Document.createAttribute() تنشئ عقدة سمة جديدة وتعيدها. الكائن ينشئ عقدة تنفذ واجهة [`Attr`](../../com.aspose.html.dom/attr/). لا يفرض DOM نوع السمات التي يمكن إضافتها إلى عنصر معين بهذه الطريقة. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | طريقة Document.createAttribute() تنشئ عقدة سمة جديدة وتعيدها. الكائن ينشئ عقدة تنفذ واجهة [Attr](T:com.aspose.html.dom.Attr). لا يفرض DOM نوع السمات التي يمكن إضافتها إلى عنصر معين بهذه الطريقة. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | ينشئ عقدة [`CDATASection`](../../com.aspose.html.dom/cdatasection/) تكون قيمتها السلسلة المحددة. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | ينشئ عقدة [`Comment`](../../com.aspose.html.dom/comment/) بناءً على السلسلة المحددة. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | ينشئ [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) فارغًا جديدًا يمكن إضافة عقد DOM إليه لبناء شجرة DOM غير مرئية. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | تعيد الطريقة كائن [`DocumentType`](../../com.aspose.html.dom/documenttype/) يمكن إما استخدامه مع DOMImplementation.createDocument عند إنشاء المستند أو إدراجه في المستند عبر طرق مثل Node.insertBefore() أو Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | في مستند HTML، تُنشئ طريقة document.createElement() العنصر HTML المحدد بـ tagName، أو عنصر [`HTMLUnknownElement`](../htmlunknownelement/) إذا لم يُعترف بـ tagName. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | ينشئ عنصرًا بالاسم المؤهل المحدد وعنوان URI الخاص بالحزمة. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | ينشئ كائن EntityReference. بالإضافة إلى ذلك، إذا كانت الكيان المشار إليه معروفًا، يتم جعل قائمة الأطفال لعقدة EntityReference مماثلة لتلك الخاصة بعقدة Entity المقابلة. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | ينشئ [`Event`](../../com.aspose.html.dom.events/event/) من نوع يدعمه التنفيذ. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | ينشئ تعبير XPath محلل مع حزم محلولة. يكون هذا مفيدًا عندما يُعاد استخدام التعبير في تطبيق لأنه يتيح تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وحل جميع بادئات الحزم الموجودة في التعبير مسبقًا. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | يقوم بتكييف أي عقدة DOM لحل الحزم بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهر فيها داخل المستند. يعمل هذا المكيّف مثل طريقة DOM Level 3 `lookupNamespaceURI` على العقد في حل packageURI من بادئة معينة باستخدام المعلومات الحالية المتوفرة في تسلسل العقدة الهرمي في وقت استدعاء lookupNamespaceURI، مع حل البادئة الضمنية xml بشكل صحيح. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | ينشئ عقدة ProcessingInstruction بناءً على الاسم والسلاسل البيانات المحددة. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | ينشئ عقدة Text بناءً على السلسلة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ينفّذ مهامًا معرفة من قبل التطبيق مرتبطة بتحرير أو تحرير أو إعادة ضبط الموارد غير المُدارة. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | تعيد طريقة Document getElementById() كائن [`Element`](../../com.aspose.html.dom/element/) يمثل العنصر الذي تتطابق خاصية id الخاصة به مع السلسلة المحددة. نظرًا لأن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول إلى عنصر محدد بسرعة. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | تعيد طريقة getElementsByClassName لواجهة [`Document`](../../com.aspose.html.dom/document/) كائنًا شبيهًا بالمصفوفة يحتوي على جميع العناصر الفرعية التي تحمل جميع أسماء الفئات المحددة. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | تعيد طريقة getElementsByTagName لواجهة [`Document`](../../com.aspose.html.dom/document/) كائنًا من نوع [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) يحتوي على العناصر ذات الاسم الوسمي المحدد. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | يعيد قائمة بالعناصر التي تحمل الاسم الوسمي المحدد وتخص الحزمة المحددة. يتم البحث في المستند بالكامل، بما في ذلك عقدة الجذر. |
| [getOverrideStyle](../../com.aspose.html/htmldocument/getoverridestyle/)(Element, String) | تُستخدم هذه الطريقة لاسترجاع إعلان نمط التجاوز لعنصر محدد وعنصر شبه محدد محدد. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | طريقة hasChildNodes() الخاصة بواجهة Node تُعيد قيمة منطقية تُشير إلى ما إذا كان الـ [`Node`](../../com.aspose.html.dom/node/) المُعطى يحتوي على عقد أطفال أم لا. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | يستورد عقدة من مستند آخر إلى هذا المستند، دون تعديل أو إزالة العقدة المصدر من المستند الأصلي؛ تنشئ هذه الطريقة نسخة جديدة من العقدة المصدر. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | طريقة insertBefore() الخاصة بواجهة Node تُدرج عقدة قبل عقدة مرجعية كطفل لعقدة أصلية محددة. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | طريقة isDefaultNamespace() الخاصة بواجهة Node تقبل عنوان حزمة URI كوسيط. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | طريقة isEqualNode() الخاصة بواجهة [`Node`](../../com.aspose.html.dom/node/) تختبر ما إذا كانت عقدتان متساويتان. تكون العقدتان متساويتين عندما يكون لهما نفس النوع والخصائص المحددة (بالنسبة للعناصر، قد تكون المعرف، عدد الأطفال، وما إلى ذلك)، وتطابق سماتهما، وهكذا. مجموعة نقاط البيانات التي يجب أن تتطابق تختلف حسب نوع العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() الخاصة بواجهة Node هي اسم مستعار قديم للمقارنة الصارمة ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | طريقة lookupNamespaceURI() الخاصة بواجهة Node تأخذ بادئة كمعامل وتُعيد عنوان الحزمة URI المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | طريقة lookupPrefix() الخاصة بواجهة Node تُعيد سلسلة تحتوي على البادئة لعنوان حزمة URI معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُعيد أول بادئة. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | يقوم بتحميل المستند بناءً على كائن الطلب المحدد، مستبدلًا المحتوى السابق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | يقوم بتحميل المستند من عنوان الإنترنت (URL) المحدد إلى النسخة الحالية، مستبدلاً المحتوى السابق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | يقوم بتحميل المستند من عنوان الإنترنت (URL) المحدد إلى النسخة الحالية، مستبدلاً المحتوى السابق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد [`Text`](../../com.aspose.html.dom/text/) في العمق الكامل للشجرة الفرعية تحت هذا الـ Node، بما في ذلك عقد السمات، في صيغة "عادية" حيث تفصل البنية فقط (مثلًا، [`elements`](../../com.aspose.html.dom/element/)، [`comments`](../../com.aspose.html.dom/comment/)، [`processing instructions`](../../com.aspose.html.dom/processinginstruction/)، [`CDATA sections`](../../com.aspose.html.dom/cdatasection/)، و[`entity references`](../../com.aspose.html.dom/entityreference/)) عقد [`Text`](../../com.aspose.html.dom/text/)، أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للوثيقة هو نفسه كما لو تم حفظها وإعادة تحميلها، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة وثيقة معينة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../configuration/) المرتبط بـ [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد Text بالكامل. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | يرجع العنصر الأول في المستند الذي يطابق المحدد |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | يرجع NodeList لجميع العناصر في المستند التي تطابق المحدد |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | طريقة `removeChild()` في واجهة Node تزيل عقدة فرعية من DOM وتُرجع العقدة المُزالة. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة مستمع أثناء معالجة حدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتها. |
| [renderTo](../../com.aspose.html/htmldocument/renderto/)(IDevice) | يُستخدم هذا الأسلوب لطباعة محتويات المستند الحالي إلى الجهاز المحدد. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويُرجع عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) الذين يُدرجون بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يتم إزالته أولاً. |
| [save](../../com.aspose.html/htmldocument/save/#save)(ResourceHandler) | يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_10)(String) | يحفظ المستند إلى ملف محلي محدد بالمسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_5)(Url) | يحفظ المستند إلى ملف محلي محدد بواسطة url. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كـ output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_1)(ResourceHandler, HTMLSaveFormat) | يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_2)(ResourceHandler, HTMLSaveOptions) | يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_3)(ResourceHandler, MarkdownSaveOptions) | يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_4)(ResourceHandler, MHTMLSaveOptions) | يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html/htmldocument/save/#save_11)(String, HTMLSaveFormat) | يحفظ المستند إلى ملف محلي محدد بواسطة path. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كـ output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_12)(String, HTMLSaveOptions) | يحفظ المستند إلى ملف محلي محدد بالمسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_13)(String, MarkdownSaveOptions) | يحفظ المستند إلى ملف محلي محدد بالمسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_14)(String, MHTMLSaveOptions) | يحفظ المستند إلى ملف محلي محدد بالمسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | يحفظ المستند إلى ملف محلي محدد بواسطة url. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كـ output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | يحفظ المستند إلى ملف محلي محدد بواسطة url. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كالتالي: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | يحفظ المستند إلى ملف محلي محدد بواسطة url. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كالتالي: output_file_name + "_files". |
| [save](../../com.aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | يحفظ المستند إلى ملف محلي محدد بواسطة url. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كالتالي: output_file_name + "_files". |
| [toString](../../com.aspose.html.dom/node/toString/)() | يعيد سلسلة تمثل هذا الكائن. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | اكتب سلسلة نصية إلى تدفق المستند المفتوح بواسطة open(). لاحظ أن الدالة ستنتج مستندًا قد لا يكون مدفوعًا بـ DTD وبالتالي قد ينتج نتيجة غير صالحة في سياق المستند. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | اكتب سلسلة نصية متبوعة بحرف سطر جديد إلى تدفق المستند المفتوح بواسطة open(). لاحظ أن الدالة ستنتج مستندًا قد لا يكون مدفوعًا بـ DTD وبالتالي قد ينتج نتيجة غير صالحة في سياق المستند. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | يحصل أو يعيّن معالج الحدث لحدث OnAbort. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | يحصل أو يعيّن معالج الحدث لحدث OnBlur. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | يحصل أو يعيّن معالج الحدث لحدث OnCancel. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | يحصل أو يعيّن معالج الحدث لحدث OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | يحصل أو يعيّن معالج الحدث لحدث OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | يحصل أو يعيّن معالج الحدث لحدث OnChange. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | يحصل أو يعيّن معالج الحدث لحدث OnClick. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | يحصل أو يعيّن معالج الحدث لحدث OnCueChange. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | يحصل أو يعيّن معالج الحدث لحدث OnDblClick. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | يحصل أو يعيّن معالج الحدث لحدث OnDurationChange. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | يحصل أو يعيّن معالج الحدث لحدث OnEmptied. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | يحصل أو يعيّن معالج الحدث لحدث OnEnded. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | يحصل أو يعيّن معالج الحدث لحدث OnError. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | يحصل أو يعيّن معالج الحدث لحدث OnFocus. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | يحصل أو يعيّن معالج الحدث لحدث OnInput. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | الحصول أو تعيين معالج الحدث لحدث OnInvalid. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | الحصول أو تعيين معالج الحدث لحدث OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | الحصول أو تعيين معالج الحدث لحدث OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | الحصول أو تعيين معالج الحدث لحدث OnKeyUp. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | الحصول أو تعيين معالج الحدث لحدث OnLoad. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | الحصول أو تعيين معالج الحدث لحدث OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | الحصول أو تعيين معالج الحدث لحدث OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | الحصول أو تعيين معالج الحدث لحدث OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | الحصول أو تعيين معالج الحدث لحدث OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | الحصول أو تعيين معالج الحدث لحدث OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | الحصول أو تعيين معالج الحدث لحدث OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | الحصول أو تعيين معالج الحدث لحدث OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | الحصول أو تعيين معالج الحدث لحدث OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | الحصول أو تعيين معالج الحدث لحدث OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | الحصول أو تعيين معالج الحدث لحدث OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | الحصول أو تعيين معالج الحدث لحدث OnMouseWheel. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | الحصول أو تعيين معالج الحدث لحدث OnPause. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | الحصول أو تعيين معالج الحدث لحدث OnPlay. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | الحصول أو تعيين معالج الحدث لحدث OnPlaying. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | الحصول أو تعيين معالج الحدث لحدث OnProgress. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | الحصول أو تعيين معالج الحدث لحدث OnRateChange. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | الحصول أو تعيين معالج الحدث لحدث OnReadyStateChange. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | الحصول أو تعيين معالج الحدث لحدث OnReset. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | الحصول أو تعيين معالج الحدث لحدث OnResize. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | الحصول أو تعيين معالج الحدث لحدث OnScroll. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | يحصل أو يضبط معالج الحدث لحدث OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | يحصل أو يضبط معالج الحدث لحدث OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | يحصل أو يضبط معالج الحدث لحدث OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | يحصل أو يضبط معالج الحدث لحدث OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | يحصل أو يضبط معالج الحدث لحدث OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | يحصل أو يضبط معالج الحدث لحدث OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | يحصل أو يضبط معالج الحدث لحدث OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | يحصل أو يضبط معالج الحدث لحدث OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | يحصل أو يضبط معالج الحدث لحدث OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | يحصل أو يضبط معالج الحدث لحدث OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | يحصل أو يضبط معالج الحدث لحدث OnWaiting. |

## ملاحظات

يمكن الحصول على مزيد من المعلومات حول HTMLDocument و Document و DOM في موارد تطوير الويب الشهيرة:

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

مرجع المعايير:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
    // إنشاء نسخة من مستند HTML
	using (var document = new HTMLDocument())
      {
        // إنشاء عنصر نمط وتعيين اللون الأخضر لجميع العناصر التي يكون اسم الفئة لها يساوي 'gr'.
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // ابحث عن عنصر رأس المستند وألحق عنصر النمط بالرأس
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // إنشاء عنصر فقرة مع اسم الفئة 'gr'.
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // إنشاء عقدة نصية
        var text = document.CreateTextNode("Hello World!!");

        // إلحاق عقدة النص بالفقرة
        p.AppendChild(text);

        // إلحاق الفقرة بعنصر جسم المستند
        document.Body.AppendChild(p);

        // حفظ مستند HTML إلى ملف 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // إنشاء نسخة من جهاز إخراج PDF وتصيير المستند داخل هذا الجهاز
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // تصيير HTML إلى PDF
          document.RenderTo(device);
        }
      }       
```

### انظر أيضًا

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
