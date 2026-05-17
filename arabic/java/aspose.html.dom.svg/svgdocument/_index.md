---
title: "فئة SVGDocument"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.svg.SVGDocument. يُعد SVGDocument جذر تسلسل SVG الهرمي ويحتوي على المحتوى بالكامل. بالإضافة إلى توفير الوصول إلى الهرمية، يوفر أيضًا بعض الطرق المريحة للوصول إلى مجموعات معينة من المعلومات من المستند. عندما يتم تضمين عنصر svg مضمّنًا كعنصر من مستند من حزمة أخرى، مثل تضمينه داخل مستند XHTML، لن يكون هناك كائن SVGDocument؛ بدلاً من ذلك سيكون كائن الجذر في تسلسل كائنات المستند هو كائن Document من نوع مختلف مثل كائن HTMLDocument. ومع ذلك، سيظهر كائن SVGDocument عندما يكون العنصر الجذري لتسلسل مستند XML هو عنصر svg، مثل عند عرض ملف SVG مستقل أي ملف بنوع MIME image/svg+xml. في هذه الحالة سيكون كائن SVGDocument هو كائن الجذر لتسلسل نموذج كائنات المستند."
type: docs

url: /ar/java/com.aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

`SVGDocument` هو جذر تسلسل SVG الهرمي ويحتوي على كامل المحتوى. بالإضافة إلى توفير الوصول إلى الهرمية، فإنه يوفر أيضًا بعض طرق الراحة للوصول إلى مجموعات معينة من المعلومات من المستند. عندما يتم تضمين عنصر ‘svg’ مضمّنًا كعنصر من مستند من حزمة أخرى، مثل عندما يتم تضمين عنصر ‘svg’ مضمّنًا داخل مستند XHTML [XHTML]، لن يكون هناك كائن SVGDocument؛ بدلاً من ذلك، سيكون كائن الجذر في تسلسل كائنات المستند كائن Document من نوع مختلف، مثل كائن HTMLDocument. ومع ذلك، سي存在 كائن SVGDocument فعليًا عندما يكون العنصر الجذري لتسلسل مستند XML هو عنصر ‘svg’، مثل عند عرض ملف SVG مستقل (أي ملف بنوع MIME "image/svg+xml"). في هذه الحالة، سيكون كائن SVGDocument هو كائن الجذر في تسلسل نموذج كائنات المستند.

```java
public class SVGDocument : Document, IDocumentCSS
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_10)(String) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_4)(Url) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_8)(Stream, String) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [SVGDocument](svgdocument/#constructor_11)(String, Configuration) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_14)(String, String) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_12)(String, Url) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_9)(Stream, String, Configuration) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [SVGDocument](svgdocument/#constructor_15)(String, String, Configuration) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |
| [SVGDocument](svgdocument/#constructor_13)(String, Url, Configuration) | يُنشئ مثيلًا جديدًا من الفئة `SVGDocument`. يعمل المُنشئ بشكل متزامن، ينتظر تحميل جميع الموارد الخارجية (الصور، السكريبتات، إلخ). لتحميل المستند بشكل غير متزامن استخدم الطريقة [`Navigate`](../../com.aspose.html.dom/document/navigate/) أو التحميلات الزائدة لها. أو يمكنك تعطيل تحميل بعض الموارد الخارجية بتعيين العلامات المناسبة في [`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) العنوان الأساسي المطلق لهذا العقدة أو null إذا لم يتمكن التنفيذ من الحصول على عنوان URI مطلق. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) يحصل على ترميز المستند. |
| [getCharset](../../com.aspose.html.dom/document/charset/) يحصل على ترميز المستند. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) يرجع العدد الحالي لعقد العنصر التي هي أبناء لهذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقد فرعية من النوع nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) الخاصية للقراءة فقط childNodes في واجهة Node تُعيد [`NodeList`](../../com.aspose.html.collections/nodelist/) حي لعقد الأطفال للعنصر المعطى حيث تُعطى العقدة الأولى الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [getChildren](../../com.aspose.html.dom/document/children/) تُرجع العناصر الفرعية. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) يحصل على نوع محتوى المستند. |
| [getContext](../../com.aspose.html.dom/document/context/) يحصل على سياق التصفح الحالي. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) سمة defaultView IDL لواجهة Document، عند الحصول عليها، يجب أن تُعيد كائن WindowProxy لسياق تصفح هذا المستند إذا كان لهذا المستند سياق تصفح مرتبط، أو null خلاف ذلك. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) إعلان نوع المستند المرتبط بهذا المستند. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) هذه سمة تسهيلية تسمح بالوصول المباشر إلى العقدة الفرعية التي هي عنصر المستند للمستند. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) موقع المستند أو null إذا كان غير معرف أو إذا تم إنشاء المستند باستخدام DOMImplementation.createDocument. |
| [getDomain](../../com.aspose.html.dom.svg/svgdocument/domain/) اسم النطاق الخاص بالخادم الذي قدم المستند، أو سلسلة null إذا تعذر تحديد الخادم باسم نطاق. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية للقراءة فقط firstChild في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم يكن للعقدة أي أطفال. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) تُرجع عقدة العنصر الفرعي الأول لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) كائن DOMImplementation الذي يتعامل مع هذا المستند. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) يحصل على ترميز المستند. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية للقراءة فقط lastChild في واجهة [`Node`](../../com.aspose.html.dom/node/) تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر، أو عقدة نص، أو عقدة تعليق. تُعيد null إذا لم يكن هناك أي عناصر طفل. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) تُرجع عقدة العنصر الفرعي الأخير لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) تُرجع الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) و[`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة من مستوى DOM 1، مثل [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/)، تكون القيمة دائمًا null. |
| [getLocation](../../com.aspose.html.dom/document/location/) موقع المستند. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) خاصية Element.packageURI للقراءة فقط تُعيد URI الحزمة للعنصر، أو null إذا لم يكن العنصر في حزمة. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) تُرجع عقدة العنصر الشقيق التالي لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة بعده في شجرة المستند. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) خاصية nextSibling للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُرجع العقدة التي تلي المحددة مباشرةً في [`childNodes`](../../com.aspose.html.dom/node/childnodes/) الخاصة بالوالد، أو تُرجع null إذا كانت العقدة المحددة هي الطفل الأخير في العنصر الأب. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) اسم هذه العقدة، حسب نوعها. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) رمز يمثل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | خاصية nodeValue في واجهة [`Node `](../../com.aspose.html.dom/node/) تُرجع أو تعين قيمة العقدة الحالية. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) يحصل على أصل المستند. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) يحصل على المستند المالك. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) خاصية parentElement للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُرجع العنصر الأب لعقدة DOM [`Element`](../../com.aspose.html.dom/element/)، أو null إذا لم يكن للعقدة أب، أو إذا كان أبها ليس عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُرجع أب العقدة المحددة في شجرة DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | خاصية prefix للقراءة فقط تُعيد بادئة الحزمة للعنصر المحدد، أو null إذا لم تُحدد أي بادئة. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) تُرجع عقدة العنصر الشقيق السابق لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة قبله في شجرة المستند. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) خاصية previousSibling للقراءة فقط في واجهة [`Node`](../../com.aspose.html.dom/node/) تُرجع العقدة التي تسبق المحددة مباشرةً في قائمة [`childNodes`](../../com.aspose.html.dom/node/firstchild/) الخاصة بالوالد، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) تُرجع حالة جاهزية المستند. "loading" أثناء تحميل المستند، "interactive" بمجرد الانتهاء من التحليل لكن لا يزال يتم تحميل الموارد الفرعية، و "complete" بمجرد الانتهاء من التحميل. |
| [getReferrer](../../com.aspose.html.dom.svg/svgdocument/referrer/) تُرجع URI للصفحة التي ربطتها إلى هذه الصفحة. تكون القيمة سلسلة فارغة إذا انتقل المستخدم إلى الصفحة مباشرة (ليس عبر رابط، بل على سبيل المثال عبر إشارة مرجعية). |
| [getRootElement](../../com.aspose.html.dom.svg/svgdocument/rootelement/) العنصر الجذر ‘svg’ في تسلسل المستند الهرمي. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) قائمة تحتوي على جميع أوراق الأنماط المرتبطة صراحةً أو المدمجة في المستند. بالنسبة لمستندات HTML، يتضمن ذلك أوراق الأنماط الخارجية، المضمنة عبر عنصر HTML LINK، وعناصر STYLE المضمنة. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | خاصية textContent لواجهة [`Node`](../../com.aspose.html.dom/node/) تمثل محتوى النص للعقدة ونسلها. |
| [getTitle](../../com.aspose.html.dom.svg/svgdocument/title/) عنوان المستند كما هو محدد بواسطة العنصر الفرعي ‘title’ لعنصر الجذر ‘svg’ (مثال: Here is the title...) |
| [getURL](../../com.aspose.html.dom.svg/svgdocument/url/) عنوان URI الكامل للمستند. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() في واجهة [`EventTarget `](../../com.aspose.html.dom/eventtarget/) تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | تضيف طريقة appendChild() في واجهة Node عقدة إلى نهاية قائمة الأطفال لعقدة أب محددة. إذا كان الطفل المعطى إشارة إلى عقدة موجودة بالفعل في المستند، فإن appendChild() تنقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك ضرورة لإزالة العقدة من عقدة الأب قبل إلحاقها بعقدة أخرى). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | تُعيد طريقة cloneNode() في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضًا أم لا. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | تُعيد طريقة cloneNode() في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضًا أم لا. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | طريقة Document.createAttribute() تنشئ عقدة سمة جديدة وتعيدها. الكائن ينشئ عقدة تنفذ واجهة [`Attr`](../../com.aspose.html.dom/attr/). لا يفرض DOM أي قيود على نوع السمات التي يمكن إضافتها إلى عنصر معين بهذه الطريقة. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | طريقة Document.createAttribute() تنشئ عقدة سمة جديدة وتعيدها. الكائن ينشئ عقدة تنفذ واجهة [Attr](T:com.aspose.html.dom.Attr). لا يفرض DOM أي قيود على نوع السمات التي يمكن إضافتها إلى عنصر معين بهذه الطريقة. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | ينشئ عقدة [`CDATASection`](../../com.aspose.html.dom/cdatasection/) تكون قيمتها السلسلة المحددة. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | ينشئ عقدة [`Comment`](../../com.aspose.html.dom/comment/) بناءً على السلسلة المحددة. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | ينشئ [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) جديد فارغ يمكن إضافة عقد DOM إليه لبناء شجرة DOM خارج الشاشة. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | الطريقة تُعيد كائن [`DocumentType`](../../com.aspose.html.dom/documenttype/) يمكن إما استخدامه مع DOMImplementation.createDocument عند إنشاء المستند أو إدراجه في المستند عبر طرق مثل Node.insertBefore() أو Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | في مستند HTML، تنشئ طريقة document.createElement() العنصر HTML المحدد بواسطة tagName، أو [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) إذا لم يتم التعرف على tagName. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | ينشئ عنصرًا بالاسم المؤهل المحدد وعنوان URI الخاص بالحزمة. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | ينشئ كائن EntityReference. بالإضافة إلى ذلك، إذا كانت الكيان المشار إليه معروفًا، يتم جعل قائمة الأطفال لعقدة EntityReference مماثلة لتلك الخاصة بعقدة Entity المقابلة. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | ينشئ [`Event`](../../com.aspose.html.dom.events/event/) من نوع يدعمه التنفيذ. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | ينشئ تعبير XPath محلل مع حزم محلولة. هذا مفيد عندما يُعاد استخدام التعبير في تطبيق لأنه يتيح تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وحل جميع بادئات الحزم مسبقًا داخل التعبير. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | إنشاء NodeIterator جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | يقوم بتكييف أي عقدة DOM لحل الحزم بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهر فيها داخل المستند. يعمل هذا المكيّف مثل طريقة DOM Level 3 `lookupNamespaceURI` على العقد في حل packageURI من بادئة معينة باستخدام المعلومات الحالية المتوفرة في تسلسل العقدة الهرمي عند استدعاء lookupNamespaceURI، كما يحل البادئة الضمنية xml بشكل صحيح. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | ينشئ عقدة ProcessingInstruction بناءً على الاسم والسلاسل البيانات المحددة. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | ينشئ عقدة Text بناءً على السلسلة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | إنشاء TreeWalker جديد على الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ[`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) المحدد، (متزامنًا) مستدعيًا مستمعي الحدث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | يُجري مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | طريقة Document getElementById() تُعيد كائن [`Element`](../../com.aspose.html.dom/element/) يمثل العنصر الذي تتطابق خاصية id الخاصة به مع السلسلة المحددة. نظرًا لأن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول بسرعة إلى عنصر محدد. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | طريقة getElementsByClassName لواجهة [`Document`](../../com.aspose.html.dom/document/) تُعيد كائنًا شبيهًا بالمصفوفة يحتوي على جميع العناصر الفرعية التي تحمل جميع أسماء الفئات المحددة. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | طريقة getElementsByTagName لواجهة [`Document`](../../com.aspose.html.dom/document/) تُعيد [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) من العناصر التي تحمل الاسم الوسمي المحدد. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | يعيد قائمة بالعناصر التي تحمل الاسم الوسمي المحدد وتخص الحزمة المحددة. يتم البحث في المستند بالكامل، بما في ذلك عقدة الجذر. |
| [getOverrideStyle](../../com.aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, String) | تُستخدم هذه الطريقة لاسترجاع إعلان نمط التجاوز لعنصر محدد وعنصر شبه محدد محدد. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | تُعيد طريقة hasChildNodes() في واجهة Node قيمة منطقية تُشير إلى ما إذا كان الـ[`Node`](../../com.aspose.html.dom/node/) المعطى يحتوي على عقد أطفال أم لا. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | يستورد عقدة من مستند آخر إلى هذا المستند، دون تعديل أو إزالة العقدة المصدر من المستند الأصلي؛ هذه الطريقة تنشئ نسخة جديدة من العقدة المصدر. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | تُدرج طريقة insertBefore() في واجهة Node عقدة قبل عقدة مرجعية كطفل لعقدة أب محددة. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | تقبل طريقة isDefaultNamespace() في واجهة Node URI الحزمة كمعامل. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | تختبر طريقة isEqualNode() في واجهة [`Node`](../../com.aspose.html.dom/node/) ما إذا كانت عقدتان متساويتان. تكون العقدتان متساويتين عندما يكون لهما نفس النوع والخصائص المحددة (بالنسبة للعناصر، قد يكون ذلك المعرف، عدد الأطفال، وما إلى ذلك)، وتطابق سماتهما، وما إلى ذلك. مجموعة البيانات المحددة التي يجب أن تتطابق تختلف حسب أنواع العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() في واجهة Node هي اسم مستعار قديم للمشغل الصارم ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | تأخذ طريقة lookupNamespaceURI() في واجهة Node بادئة كمعامل وتُعيد URI الحزمة المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | ترجع طريقة lookupPrefix() في واجهة Node سلسلة تحتوي على البادئة لURI حزمة معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُرجع أول بادئة. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | يقوم بتحميل المستند بناءً على كائن الطلب المحدد، مستبدلًا المحتوى السابق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلاً المحتوى السابق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلاً المحتوى السابق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد [`Text`](../../com.aspose.html.dom/text/) في العمق الكامل للشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في شكل "عادي" حيث تفصل البنية فقط (مثل [`elements`](../../com.aspose.html.dom/element/)، [`comments`](../../com.aspose.html.dom/comment/)، [`processing instructions`](../../com.aspose.html.dom/processinginstruction/)، [`CDATA sections`](../../com.aspose.html.dom/cdatasection/)، و[`entity references`](../../com.aspose.html.dom/entityreference/)) عقد [`Text`](../../com.aspose.html.dom/text/)، أي لا توجد عقد نصية متجاورة ولا عقد نصية فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة مستند معينة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../../com.aspose.html/configuration/) المرتبط بـ[`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) هو true، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد النص بالكامل. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | يعيد العنصر الأول في المستند الذي يطابق المحدد |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | يعيد NodeList بجميع العناصر في المستند التي تطابق المحدد |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | طريقة removeChild() في واجهة Node تزيل عقدةً فرعيةً من DOM وتعيد العقدة التي أزيلت. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [renderTo](../../com.aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | يُستخدم هذا الأسلوب لطباعة محتويات المستند الحالي إلى الجهاز المحدد. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويعيد عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) الذين يتم إدراجهم بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، فسيتم إزالته أولاً. |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save)(ResourceHandler) | يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_6)(String) | يحفظ المستند إلى ملف محلي محدد بـ `path`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | يحفظ المستند إلى ملف محلي محدد بـ `url`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_1)(ResourceHandler, SVGSaveFormat) | يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_2)(ResourceHandler, SVGSaveOptions) | يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_7)(String, SVGSaveFormat) | يحفظ المستند إلى ملف محلي محدد بـ `path`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_8)(String, SVGSaveOptions) | يحفظ المستند إلى ملف محلي محدد بـ `path`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | يحفظ المستند إلى ملف محلي محدد بـ `url`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | يحفظ المستند إلى ملف محلي محدد بـ `url`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيُنشأ اسمه كالتالي: output_file_name + \"_files\". |
| [toString](../../com.aspose.html.dom/node/toString/)() | يرجع سلسلة تمثل هذا الكائن. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | اكتب سلسلة نصية إلى تدفق المستند المفتوح بواسطة open(). لاحظ أن الدالة قد تنتج مستندًا ليس بالضرورة مدفوعًا بـ DTD وبالتالي قد ينتج نتيجة غير صالحة في سياق المستند. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | اكتب سلسلة نصية متبوعة بحرف سطر جديد إلى تدفق المستند المفتوح بواسطة open(). لاحظ أن الدالة قد تنتج مستندًا ليس بالضرورة مدفوعًا بـ DTD وبالتالي قد ينتج نتيجة غير صالحة في سياق المستند. |

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
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | الحصول أو تعيين معالج الحدث لـ OnInvalid. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | الحصول أو تعيين معالج الحدث لـ OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | الحصول أو تعيين معالج الحدث لـ OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | الحصول أو تعيين معالج الحدث لـ OnKeyUp. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | الحصول أو تعيين معالج الحدث لـ OnLoad. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | الحصول أو تعيين معالج الحدث لـ OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | الحصول أو تعيين معالج الحدث لـ OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | الحصول أو تعيين معالج الحدث لـ OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | الحصول أو تعيين معالج الحدث لـ OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | الحصول أو تعيين معالج الحدث لـ OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | الحصول أو تعيين معالج الحدث لـ OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | الحصول أو تعيين معالج الحدث لـ OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | الحصول أو تعيين معالج الحدث لـ OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | الحصول أو تعيين معالج الحدث لـ OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | الحصول أو تعيين معالج الحدث لـ OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | الحصول أو تعيين معالج الحدث لـ OnMouseWheel. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | الحصول أو تعيين معالج الحدث لـ OnPause. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | الحصول أو تعيين معالج الحدث لـ OnPlay. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | الحصول أو تعيين معالج الحدث لـ OnPlaying. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | الحصول أو تعيين معالج الحدث لـ OnProgress. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | الحصول أو تعيين معالج الحدث لـ OnRateChange. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | الحصول أو تعيين معالج الحدث لـ OnReadyStateChange. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | الحصول أو تعيين معالج الحدث لـ OnReset. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | الحصول أو تعيين معالج الحدث لـ OnResize. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | الحصول أو تعيين معالج الحدث لـ OnScroll. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | الحصول أو تعيين معالج الحدث لحدث OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | الحصول أو تعيين معالج الحدث لحدث OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | الحصول أو تعيين معالج الحدث لحدث OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | الحصول أو تعيين معالج الحدث لحدث OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | الحصول أو تعيين معالج الحدث لحدث OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | الحصول أو تعيين معالج الحدث لحدث OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | الحصول أو تعيين معالج الحدث لحدث OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | الحصول أو تعيين معالج الحدث لحدث OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | الحصول أو تعيين معالج الحدث لحدث OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | الحصول أو تعيين معالج الحدث لحدث OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | الحصول أو تعيين معالج الحدث لحدث OnWaiting. |

### انظر أيضًا

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
