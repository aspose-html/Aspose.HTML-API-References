---
title: SVGDocument
second_title: Aspose.HTML لمرجع .NET API
description: أنSVG الوثيقةهو جذر تسلسل SVG الهرمي ويحمل المحتوى بالكامل. إلى جانب توفير الوصول إلى التسلسل الهرمي  فإنه يوفر أيضًا بعض الطرق الملائمة للوصول إلى مجموعات معينة من المعلومات من المستند. عنصر مضمّن في مستند XHTML XHTML  فلن يكون كائن SVGDocument موجودًا  بدلاً من ذلك  سيكون الكائن الجذر في التسلسل الهرمي لكائن المستند كائن مستند من نوع مختلف  مثل كائن HTMLDocument. ومع ذلك  سيكون كائن SVGDocument موجودًا بالفعل عندما يكون العنصر الجذر للتسلسل الهرمي لمستند XML هو عنصر svg  مثل عند عرض ملف SVG مستقل على سبيل المثال  ملف من نوع MIME image / svg  xml. في هذه الحالة  سيكون كائن SVGDocument هو الكائن الجذر للتسلسل الهرمي لنموذج كائن المستند.
type: docs
weight: 2020
url: /ar/net/aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

أن`SVG الوثيقة`هو جذر تسلسل SVG الهرمي ويحمل المحتوى بالكامل. إلى جانب توفير الوصول إلى التسلسل الهرمي ، فإنه يوفر أيضًا بعض الطرق الملائمة للوصول إلى مجموعات معينة من المعلومات من المستند. عنصر مضمّن في مستند XHTML [XHTML] ، فلن يكون كائن SVGDocument موجودًا ؛ بدلاً من ذلك ، سيكون الكائن الجذر في التسلسل الهرمي لكائن المستند كائن مستند من نوع مختلف ، مثل كائن HTMLDocument. ومع ذلك ، سيكون كائن SVGDocument موجودًا بالفعل عندما يكون العنصر الجذر للتسلسل الهرمي لمستند XML هو عنصر 'svg' ، مثل عند عرض ملف SVG مستقل (على سبيل المثال ، ملف من نوع MIME "image / svg + xml"). في هذه الحالة ، سيكون كائن SVGDocument هو الكائن الجذر للتسلسل الهرمي لنموذج كائن المستند.

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SVGDocument](svgdocument#constructor)() | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) فئة . |
| [SVGDocument](svgdocument#constructor_1)(Configuration) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) فئة . |
| [SVGDocument](svgdocument#constructor_2)(RequestMessage) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_10)(string) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_4)(Url) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_3)(RequestMessage, Configuration) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_8)(Stream, string) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [SVGDocument](svgdocument#constructor_6)(Stream, Url) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [SVGDocument](svgdocument#constructor_11)(string, Configuration) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_14)(string, string) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_12)(string, Url) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_5)(Url, Configuration) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_9)(Stream, string, Configuration) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [SVGDocument](svgdocument#constructor_7)(Stream, Url, Configuration) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [SVGDocument](svgdocument#constructor_15)(string, string, Configuration) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |
| [SVGDocument](svgdocument#constructor_13)(string, Url, Configuration) | يقوم بتهيئة مثيل جديد لملف[`SVGDocument`](../svgdocument) صف دراسي. يعمل المُنشئ بشكل متزامن ، وينتظر تحميل جميع الموارد الخارجية (الصور ، والنصوص ، وما إلى ذلك) . لتحميل المستند بطريقة غير متزامنة ، استخدم الطريقة[`Navigate`](../../aspose.html.dom/document/navigate) أو overloads. أو يمكنك تعطيل تحميل بعض الموارد الخارجية عن طريق تعيين العلامات المناسبة في[`Security`](../../aspose.html.dom/ibrowsingcontext/security) . |

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | خريطة NamedNodeMap تحتوي على سمات هذه العقدة (إذا كانت عنصرًا) أو خالية بخلاف ذلك. |
| override [BaseURI](../../aspose.html.dom/document/baseuri) { get; } | URI الأساسي المطلق لهذه العقدة أو فارغ إذا لم يتمكن التطبيق من الحصول على URI مطلق. |
| [CharacterSet](../../aspose.html.dom/document/characterset) { get; } | الحصول على ترميز المستند. |
| [Charset](../../aspose.html.dom/document/charset) { get; } | الحصول على ترميز المستند. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount) { get; } | إرجاع العدد الحالي لعُقد العناصر التابعة لهذا العنصر. 0 إذا كان هذا العنصر لا يحتوي على عقد فرعية من نوع العقدة 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | قائمة NodeList التي تحتوي على كافة توابع هذه العقدة. إذا لم يكن هناك أطفال ، فهذه قائمة NodeList لا تحتوي على عقد .. |
| [Children](../../aspose.html.dom/document/children) { get; } | إرجاع العناصر الفرعية . |
| [ContentType](../../aspose.html.dom/document/contenttype) { get; } | الحصول على نوع محتوى المستند. |
| [Context](../../aspose.html.dom/document/context) { get; } | يحصل على سياق التصفح الحالي. |
| [DefaultView](../../aspose.html.dom/document/defaultview) { get; } | السمة الافتراضية للعرض IDL لواجهة المستند ، عند الحصول على ، يجب أن تعيد كائن WindowProxy الخاص بسياق الاستعراض الخاص بهذا المستند ، إذا كان هذا المستند يحتوي على سياق استعراض مرتبط ، أو فارغًا بخلاف ذلك. |
| [Doctype](../../aspose.html.dom/document/doctype) { get; } | إقرار نوع المستند المرتبط بهذا المستند . |
| [DocumentElement](../../aspose.html.dom/document/documentelement) { get; } | هذه سمة ملائمة تتيح الوصول المباشر إلى العقدة الفرعية التي تمثل عنصر المستند في المستند. |
| [DocumentURI](../../aspose.html.dom/document/documenturi) { get; } | مكان المستند أو فارغ إذا لم يتم تعريفه أو إذا تم إنشاء المستند باستخدام DOMImplementation.createDocument. |
| [Domain](../../aspose.html.dom.svg/svgdocument/domain) { get; } | اسم المجال للخادم الذي خدم المستند ، أو سلسلة فارغة إذا تعذر تحديد الخادم باسم المجال. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | الطفل الأول لهذه العقدة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild) { get; } | إرجاع أول عقدة عنصر فرعي لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عناصر فرعية. |
| [Implementation](../../aspose.html.dom/document/implementation) { get; } | كائن DOMImplementation الذي يعالج هذا المستند. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding) { get; } | الحصول على ترميز المستند. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | آخر تابع لهذه العقدة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild) { get; } | إرجاع آخر عقدة عنصر فرعي لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عناصر فرعية. |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | إرجاع الجزء المحلي من الاسم المؤهل لهذه العقدة . بالنسبة للعقد من أي نوع بخلاف ELEMENT_NODE و ATTRIBUTE_NODE والعقد التي تم إنشاؤها باستخدام طريقة DOM من المستوى 1 ، مثل Document.createElement () ، يكون هذا دائمًا فارغًا. |
| [Location](../../aspose.html.dom/document/location) { get; } | مكان المستند. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | معرف مساحة الاسم لهذه العقدة ، أو فارغ إذا كانت غير محددة. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling) { get; } | إرجاع عقدة العنصر الشقيق التالية لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عقد شقيقة لعنصر تأتي بعد هذا في شجرة الوثيقة. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | العقدة التي تلي هذه العقدة مباشرة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| override [NodeName](../../aspose.html.dom/document/nodename) { get; } | اسم هذه العقدة حسب نوعها. |
| override [NodeType](../../aspose.html.dom/document/nodetype) { get; } | رمز يمثل نوع الكائن الأساسي. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | قيمة هذه العقدة حسب نوعها. |
| [Origin](../../aspose.html.dom/document/origin) { get; } | يحصل على اصل الوثيقة . |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument) { get; } | الحصول على مستند المالك. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | يحصل على الوالد[`Element`](../../aspose.html.dom/element) من هذه العقدة. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | أصل هذه العقدة. قد يكون لجميع العقد ، باستثناء Attr و Document و DocumentFragment و Entity و Notation ، أصل. ومع ذلك ، إذا تم إنشاء عقدة للتو ولم تتم إضافتها بعد إلى الشجرة ، أو إذا تمت إزالتها من الشجرة ، فسيكون ذلك فارغًا. |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | بادئة مساحة الاسم لهذه العقدة ، أو فارغة إذا كانت غير محددة. عندما يتم تعريفه على أنه فارغ ، فإن الإعداد ليس له أي تأثير |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling) { get; } | إرجاع عقدة العنصر الشقيقة السابقة لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عقد شقيقة لعنصر تأتي قبل هذا في شجرة الوثيقة. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | العقدة التي تسبق هذه العقدة مباشرة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| [ReadyState](../../aspose.html.dom/document/readystate) { get; } | إرجاع جاهزية المستند. "التحميل" أثناء تحميل المستند ، "تفاعلي" بمجرد الانتهاء من التحليل مع استمرار تحميل الموارد الفرعية ، و "اكتمال" بمجرد تحميله. |
| [Referrer](../../aspose.html.dom.svg/svgdocument/referrer) { get; } | إرجاع URI للصفحة المرتبطة بهذه الصفحة. القيمة عبارة عن سلسلة فارغة إذا انتقل المستخدم إلى الصفحة مباشرة (ليس من خلال رابط ، ولكن ، على سبيل المثال ، عبر إشارة مرجعية) . |
| [RootElement](../../aspose.html.dom.svg/svgdocument/rootelement) { get; } | الجذر "svg" في التسلسل الهرمي للمستند. |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking) { get; set; } | سمة تحدد ما إذا كان التحقق من الخطأ يتم فرضه أم لا. عند التعيين على "خطأ" ، يكون التطبيق مجانيًا في عدم اختبار كل حالة خطأ محتملة يتم تحديدها عادةً على عمليات DOM ، وعدم رفع أي استثناءات DOM على عمليات DOM أو الإبلاغ عن الأخطاء أثناء استخدام Document.normalizeDocument (). في حالة الخطأ ، يكون السلوك غير محدد. هذه السمة صحيحة بشكل افتراضي. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets) { get; } | قائمة تحتوي على جميع أوراق الأنماط المرتبطة أو المضمنة في مستند بشكل صريح. بالنسبة لمستندات HTML ، يتضمن ذلك أوراق الأنماط الخارجية ، المضمنة عبر عنصر HTML LINK ، وعناصر النمط المضمنة. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent) { get; set; } | تقوم هذه السمة بإرجاع المحتوى النصي لهذه العقدة وتوابعها. عندما يتم تعريفه على أنه فارغ ، فإن تعيينه ليس له أي تأثير. عند الإعداد ، تتم إزالة أي أطفال محتملين قد تكون هذه العقدة لديهم ، وإذا لم تكن السلسلة الجديدة فارغة أو فارغة ، يتم استبدالها بعقدة نصية واحدة تحتوي على السلسلة التي تم تعيين هذه السمة عليها. |
| [Title](../../aspose.html.dom.svg/svgdocument/title) { get; } | عنوان المستند كما هو محدد بواسطة العنصر الفرعي "العنوان" للعنصر الجذر "svg" (على سبيل المثال ،هنا العنوان... ) |
| [URL](../../aspose.html.dom.svg/svgdocument/url) { get; } | عنوان URL الكامل للمستند. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone) { get; set; } | سمة تحدد ، كجزء من إعلان XML ، ما إذا كان هذا المستند مستقلاً. هذا خطأ عندما يكون غير محدد. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion) { get; set; } | سمة تحدد ، كجزء من إعلان XML ، رقم إصدار هذا المستند. إذا لم يكن هناك إعلان وإذا كان هذا المستند يدعم ميزة "XML" ، فإن القيمة هي "1.0". إذا كان هذا المستند لا يدعم ميزة "XML" ، فستكون القيمة دائمًا خالية. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | يضيف العقدة newChild إلى نهاية قائمة العناصر الفرعية لهذه العقدة. إذا كان الطفل الجديد موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | إرجاع نسخة مكررة من هذه العقدة ، على سبيل المثال ، بمثابة مُنشئ نسخة عام للعقد. لا تحتوي العقدة المكررة على أصل (العقدة الأم خالية) ولا توجد بيانات مستخدم. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | إرجاع نسخة مكررة من هذه العقدة ، على سبيل المثال ، بمثابة مُنشئ نسخة عام للعقد. لا تحتوي العقدة المكررة على أصل (العقدة الأم خالية) ولا توجد بيانات مستخدم. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute)(string) | لإنشاء Attr بالاسم المحدد . |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens)(string, string) | ينشئ سمة للاسم المؤهل المحدد ومساحة URI. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection)(string) | ينشئ عقدة CDATAS تكون قيمتها هي السلسلة المحددة. |
| [CreateComment](../../aspose.html.dom/document/createcomment)(string) | يقوم بإنشاء عقدة تعليق بالنظر إلى السلسلة المحددة . |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment)() | إنشاء كائن DocumentFragment فارغ . |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype)(string, string, string, string) | ينشئ عقدة DocumentType . |
| [CreateElement](../../aspose.html.dom/document/createelement)(string) | لتكوين عنصر من النوع المحدد. لاحظ أن المثيل الذي تم إرجاعه يطبق واجهة العنصر ، لذلك يمكن تحديد السمات مباشرة على الكائن الذي تم إرجاعه. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns)(string, string) | ينشئ عنصرًا للاسم المؤهل المحدد ومساحة الاسم URI. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference)(string) | إنشاء كائن EntityReference. بالإضافة إلى ذلك ، إذا كان الكيان المشار إليه معروفًا ، فستكون القائمة الفرعية لعقدة EntityReference مماثلة لقائمة عقدة الكيان المقابلة. |
| [CreateEvent](../../aspose.html.dom/document/createevent)(string) | ينشئ ملف[`Event`](../../aspose.html.dom.events/event) من النوع الذي يدعمه التنفيذ . |
| [CreateExpression](../../aspose.html.dom/document/createexpression)(string, IXPathNSResolver) | لتكوين تعبير XPath تم تحليله باستخدام مساحات الأسماء التي تم حلها. هذا مفيد عندما يُعاد استخدام تعبير في أحد التطبيقات لأنه يجعل من الممكن تجميع سلسلة التعبير في نموذج داخلي أكثر كفاءة و حل جميع بادئات مساحة الاسم التي تحدث داخل التعبير. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator)(Node) | قم بإنشاء NodeIterator جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator)(Node, long) | قم بإنشاء NodeIterator جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator)(Node, long, INodeFilter) | قم بإنشاء NodeIterator جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver)(Node) | تتكيف مع أي عقدة DOM لتحليل مساحات الأسماء بحيث يمكن بسهولة تقييم تعبير XPath بالنسبة إلى سياق العقدة حيث ظهر داخل المستند. يعمل هذا المحول مثل طريقة DOM المستوى 3`lookupNamespaceURI` على العقد في حل مساحة الاسمURI من بادئة معينة باستخدام المعلومات الحالية المتاحة في التسلسل الهرمي للعقدة في time lookupNamespaceURI ، يتم أيضًا حل بادئة xml الضمنية بشكل صحيح. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction)(string, string) | ينشئ عقدة ProcessingInstruction مع إعطاء الاسم المحدد وسلاسل البيانات. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode)(string) | يقوم بإنشاء عقدة نصية مع إعطاء السلسلة المحددة . |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker)(Node) | قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker)(Node, long) | قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker)(Node, long, INodeFilter) | قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | تسمح هذه الطريقة بإرسال الأحداث إلى نموذج حدث عمليات التنفيذ. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| [Evaluate](../../aspose.html.dom/document/evaluate)(string, Node, IXPathNSResolver, XPathResultType, object) | بتقييم سلسلة تعبير XPath وإرجاع نتيجة من النوع المحدد إن أمكن. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid)(string) | إرجاع العنصر الذي يحتوي على سمة معرف بالقيمة المحددة. إذا لم يكن هذا العنصر موجودًا ، فسيتم إرجاعه فارغًا. إذا كان هناك أكثر من عنصر واحد يحتوي على سمة معرف بهذه القيمة ، فإن ما يتم إرجاعه يكون غير محدد. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname)(string) | إرجاع كائن NodeList مباشر يحتوي على جميع العناصر في المستند التي تحتوي على جميع الفئات المحددة في الوسيطة . http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname)(string) | إرجاع NodeList لجميع العناصر بترتيب المستند مع اسم علامة محدد ومضمنة في المستند. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens)(string, string) | إرجاع NodeList لجميع العناصر مع اسم محلي محدد ومساحة اسم URI بترتيب المستند. |
| [GetOverrideStyle](../../aspose.html.dom.svg/svgdocument/getoverridestyle)(Element, string) | تُستخدم هذه الطريقة لاسترداد إعلان نمط التجاوز لعنصر محدد وعنصر زائف محدد. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | إرجاع ما إذا كانت هذه العقدة (إذا كانت عنصرًا) لها أي سمات |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | إرجاع ما إذا كان لهذه العقدة أي توابع. |
| [ImportNode](../../aspose.html.dom/document/importnode)(Node, bool) | يستورد عقدة من مستند آخر إلى هذا المستند ، بدون تغيير أو إزالة العقدة المصدر من المستند الأصلي ؛ هذه الطريقة تنشئ نسخة جديدة من العقدة المصدر. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | يقوم بإدراج العقدة قبل تابع العقدة الفرعية الموجودة. إذا كان التابع فارغًا ، أدخل العقدة في نهاية قائمة العناصر الفرعية . إذا كان الكائن الفرعي عبارة عن كائن DocumentFragment ، فسيتم إدراج جميع توابعه ، بالترتيب نفسه ، قبل التابع. إذا كان الطفل موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | يتحقق هذا الأسلوب مما إذا كانت مساحة الاسم المحددة هي مساحة الاسم الافتراضية أم لا. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | اختبار ما إذا كانت العقدتان متساويتان. تختبر هذه الطريقة المساواة بين العقد ، وليس التماثل (أي ما إذا كانت العقدتان مرجعيتان لنفس الكائن) والتي يمكن اختبارها باستخدام Node.isSameNode (). جميع العقد التي هي نفسها ستكون متساوية أيضًا ، على الرغم من أن العكس قد لا يكون صحيحًا. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | إرجاع ما إذا كانت هذه العقدة هي نفس العقدة المحددة. توفر هذه الطريقة طريقة لتحديد ما إذا كان مرجعان للعقدة يتم إرجاعهما بواسطة مرجع التطبيق نفس الكائن. عندما يكون مراجعان للعقدة مراجع لنفس الكائن ، حتى لو كان ذلك من خلال وكيل ، يمكن استخدام المراجع بشكل تبادلي تمامًا ، بحيث يكون لجميع السمات نفس القيم واستدعاء نفس طريقة DOM على أي مرجع له نفس التأثير دائمًا. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | ابحث عن مساحة الاسم URI المرتبطة بالبادئة المحددة ، بدءًا من هذه العقدة. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | ابحث عن البادئة المرتبطة بمساحة الاسم المحددة URI ، بدءًا من هذه العقدة. يتم تجاهل تعريفات مساحة الاسم الافتراضية بهذه الطريقة. راجع بحث بادئة مساحة الاسم للحصول على تفاصيل حول الخوارزمية المستخدمة بواسطة هذه الطريقة. |
| [Navigate](../../aspose.html.dom/document/navigate)(RequestMessage) | تحميل المستند بناءً على كائن الطلب المحدد ، مع استبدال المحتوى السابق. |
| [Navigate](../../aspose.html.dom/document/navigate)(string) | تحميل المستند في محدد موقع المعلومات (URL) المحدد في المثيل الحالي ، مع استبدال المحتوى السابق. |
| [Navigate](../../aspose.html.dom/document/navigate)(Url) | تحميل المستند في محدد موقع المعلومات (URL) المحدد في المثيل الحالي ، مع استبدال المحتوى السابق. |
| [Navigate](../../aspose.html.dom/document/navigate)(Stream, string) | تحميل المستند من محتوى محدد واستخدام baseUri لحل الموارد ذات الصلة ، واستبدال المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق . |
| [Navigate](../../aspose.html.dom/document/navigate)(Stream, Url) | تحميل المستند من محتوى محدد واستخدام baseUri لحل الموارد ذات الصلة ، واستبدال المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق . |
| [Navigate](../../aspose.html.dom/document/navigate)(string, string) | تحميل المستند من محتوى محدد واستخدام baseUri لحل الموارد ذات الصلة ، واستبدال المحتوى السابق. |
| [Navigate](../../aspose.html.dom/document/navigate)(string, Url) | تحميل المستند من محتوى محدد واستخدام baseUri لحل الموارد ذات الصلة ، واستبدال المحتوى السابق. |
| [Normalize](../../aspose.html.dom/node/normalize)() | وضع جميع العقد النصية في العمق الكامل للشجرة الفرعية أسفل هذه العقدة ، بما في ذلك عقد السمات ، في نموذج "عادي" حيث تفصل البنية فقط (على سبيل المثال ، العناصر والتعليقات وإرشادات المعالجة وأقسام CDATA ومراجع الكيانات) النص العقد ، أي لا توجد عقد نصية متجاورة ولا عقد نصية فارغة. يمكن استخدام هذا للتأكد من أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله ، ويكون مفيدًا عندما تكون العمليات (مثل عمليات بحث XPointer [XPointer]) التي تعتمد على بنية شجرة وثيقة معينة يستخدم. إذا كانت المعلمة "تطبيع الأحرف" لكائن DOMConfiguration المرفقة بـ Node.ownerDocument صحيحة ، فإن هذه الطريقة ستعمل أيضًا على تسوية أحرف العقد النصية بشكل كامل. |
| [QuerySelector](../../aspose.html.dom/document/queryselector)(string) | إرجاع العنصر الأول في المستند الذي يتطابق مع selector |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall)(string) | إرجاع قائمة NodeList لجميع العناصر الموجودة في المستند ، والتي تطابق selector |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | يزيل العقدة الفرعية التي أشار إليها oldChild من قائمة الأطفال ، ويعيدها . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../../aspose.html.dom/eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../../aspose.html.dom/eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../../aspose.html.dom/eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| override [RenderTo](../../aspose.html.dom.svg/svgdocument/renderto)(IDevice) | تُستخدم هذه الطريقة لطباعة محتويات المستند الحالي على الجهاز المحدد. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | يستبدل العقدة الفرعية oldChild بـ newChild في قائمة الأطفال ، ويعيد العقدة oldChild. إذا كان newChild هو كائن DocumentFragment ، فسيتم استبدال oldChild بكافة العناصر الفرعية DocumentFragment ، والتي يتم إدراجها بنفس الترتيب. إذا كان الطفل الجديد موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save)(IOutputStorage) | يحفظ محتوى الوثيقة والموارد في تخزين المخرجات. |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save_6)(string) | يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" . |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save_3)(Url) | يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" . |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save_1)(IOutputStorage, SVGSaveFormat) | يحفظ محتوى الوثيقة والموارد في تخزين المخرجات. |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save_2)(IOutputStorage, SVGSaveOptions) | يحفظ محتوى الوثيقة والموارد في تخزين المخرجات. |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save_7)(string, SVGSaveFormat) | يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" . |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save_8)(string, SVGSaveOptions) | يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" . |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save_4)(Url, SVGSaveFormat) | يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" . |
| [Save](../../aspose.html.dom.svg/svgdocument/save#save_5)(Url, SVGSaveOptions) | يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" . |
| override [ToString](../../aspose.html.dom/node/tostring)() | إرجاع أString الذي يمثل هذا المثال. |
| [Write](../../aspose.html.dom/document/write)(params string[]) | اكتب سلسلة نصية إلى تدفق مستند تم فتحه بواسطة open (). لاحظ أن الوظيفة ستنتج document الذي لا يكون بالضرورة مدفوعًا ب DTD وبالتالي قد ينتج عن ذلك نتيجة غير صالحة في سياق المستند. |
| [WriteLn](../../aspose.html.dom/document/writeln)(params string[]) | اكتب سلسلة نصية متبوعة بحرف سطر جديد إلى دفق document مفتوح بواسطة open (). لاحظ أن الوظيفة will تنتج مستندًا ليس بالضرورة مدفوعًا بـ DTD و وبالتالي قد ينتج نتيجة غير صالحة في سياق document |

### أنظر أيضا

* class [Document](../../aspose.html.dom/document)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
