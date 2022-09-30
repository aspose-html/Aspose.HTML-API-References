---
title: DocumentFragment
second_title: Aspose.HTML لمرجع .NET API
description: DocumentFragment هو كائن مستند خفيف الوزن أو بسيط. من الشائع جدًا أن تكون قادرًا على استخراج جزء من شجرة المستند أو إنشاء جزء جديد من المستند.
type: docs
weight: 680
url: /ar/net/aspose.html.dom/documentfragment/
---
## DocumentFragment class

DocumentFragment هو كائن مستند "خفيف الوزن" أو "بسيط". من الشائع جدًا أن تكون قادرًا على استخراج جزء من شجرة المستند أو إنشاء جزء جديد من المستند.

```csharp
public class DocumentFragment : Node, IParentNode
```

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes) { get; } | خريطة NamedNodeMap تحتوي على سمات هذه العقدة (إذا كانت عنصرًا) أو خالية بخلاف ذلك. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri) { get; } | URI الأساسي المطلق لهذه العقدة أو فارغ إذا لم يتمكن التطبيق من الحصول على URI مطلق. |
| [ChildElementCount](../../aspose.html.dom/documentfragment/childelementcount) { get; } | إرجاع العدد الحالي لعُقد العناصر التابعة لهذا العنصر. 0 إذا كان هذا العنصر لا يحتوي على عقد فرعية من نوع العقدة 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes) { get; } | قائمة NodeList التي تحتوي على كافة توابع هذه العقدة. إذا لم يكن هناك أطفال ، فهذه قائمة NodeList لا تحتوي على عقد .. |
| [Children](../../aspose.html.dom/documentfragment/children) { get; } | إرجاع العناصر الفرعية للعنصر الحالي. |
| [FirstChild](../../aspose.html.dom/node/firstchild) { get; } | الطفل الأول لهذه العقدة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| [FirstElementChild](../../aspose.html.dom/documentfragment/firstelementchild) { get; } | إرجاع أول عقدة عنصر فرعي لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عناصر فرعية. |
| [InnerHTML](../../aspose.html.dom/documentfragment/innerhtml) { get; set; } | إرجاع جزء من HTML أو XML يمثل محتويات العنصر. يمكن تعيينه لاستبدال محتويات العنصر بالعقد التي تم تحليلها من السلسلة المحددة. |
| [LastChild](../../aspose.html.dom/node/lastchild) { get; } | آخر تابع لهذه العقدة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| [LastElementChild](../../aspose.html.dom/documentfragment/lastelementchild) { get; } | إرجاع آخر عقدة عنصر فرعي لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عناصر فرعية. |
| virtual [LocalName](../../aspose.html.dom/node/localname) { get; } | إرجاع الجزء المحلي من الاسم المؤهل لهذه العقدة . بالنسبة للعقد من أي نوع بخلاف ELEMENT_NODE و ATTRIBUTE_NODE والعقد التي تم إنشاؤها باستخدام طريقة DOM من المستوى 1 ، مثل Document.createElement () ، يكون هذا دائمًا فارغًا. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri) { get; } | معرف مساحة الاسم لهذه العقدة ، أو فارغ إذا كانت غير محددة. |
| [NextElementSibling](../../aspose.html.dom/documentfragment/nextelementsibling) { get; } | إرجاع عقدة العنصر الشقيق التالية لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عقد شقيقة لعنصر تأتي بعد هذا في شجرة الوثيقة. |
| [NextSibling](../../aspose.html.dom/node/nextsibling) { get; } | العقدة التي تلي هذه العقدة مباشرة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| override [NodeName](../../aspose.html.dom/documentfragment/nodename) { get; } | اسم هذه العقدة حسب نوعها. |
| override [NodeType](../../aspose.html.dom/documentfragment/nodetype) { get; } | رمز يمثل نوع الكائن الأساسي. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue) { get; set; } | قيمة هذه العقدة حسب نوعها. |
| [OuterHTML](../../aspose.html.dom/documentfragment/outerhtml) { get; set; } | إرجاع جزء من HTML أو XML يمثل العنصر ومحتوياته. يمكن تعيينه لاستبدال العنصر بالعقد التي تم تحليلها من السلسلة المحددة. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument) { get; } | كائن المستند المرتبط بهذه العقدة. هذا هو أيضًا كائن المستند المستخدم لإنشاء عقد جديدة. عندما تكون هذه العقدة عبارة عن مستند أو نوع مستند لم يتم استخدامه مع أي مستند حتى الآن ، يكون هذا فارغًا. |
| [ParentElement](../../aspose.html.dom/node/parentelement) { get; } | يحصل على الوالد[`Element`](../element) من هذه العقدة. |
| [ParentNode](../../aspose.html.dom/node/parentnode) { get; } | أصل هذه العقدة. قد يكون لجميع العقد ، باستثناء Attr و Document و DocumentFragment و Entity و Notation ، أصل. ومع ذلك ، إذا تم إنشاء عقدة للتو ولم تتم إضافتها بعد إلى الشجرة ، أو إذا تمت إزالتها من الشجرة ، فسيكون ذلك فارغًا. |
| virtual [Prefix](../../aspose.html.dom/node/prefix) { get; set; } | بادئة مساحة الاسم لهذه العقدة ، أو فارغة إذا كانت غير محددة. عندما يتم تعريفه على أنه فارغ ، فإن الإعداد ليس له أي تأثير |
| [PreviousElementSibling](../../aspose.html.dom/documentfragment/previouselementsibling) { get; } | إرجاع عقدة العنصر الشقيقة السابقة لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عقد شقيقة لعنصر تأتي قبل هذا في شجرة الوثيقة. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling) { get; } | العقدة التي تسبق هذه العقدة مباشرة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| override [TextContent](../../aspose.html.dom/documentfragment/textcontent) { get; set; } | تقوم هذه السمة بإرجاع المحتوى النصي لهذه العقدة وتوابعها. عندما يتم تعريفه على أنه فارغ ، فإن تعيينه ليس له أي تأثير. عند الإعداد ، تتم إزالة أي أطفال محتملين قد تكون هذه العقدة لديهم ، وإذا لم تكن السلسلة الجديدة فارغة أو فارغة ، يتم استبدالها بعقدة نصية واحدة تحتوي على السلسلة التي تم تعيين هذه السمة عليها. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AppendChild](../../aspose.html.dom/node/appendchild)(Node) | يضيف العقدة newChild إلى نهاية قائمة العناصر الفرعية لهذه العقدة. إذا كان الطفل الجديد موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| [CloneNode](../../aspose.html.dom/node/clonenode)() | إرجاع نسخة مكررة من هذه العقدة ، على سبيل المثال ، بمثابة مُنشئ نسخة عام للعقد. لا تحتوي العقدة المكررة على أصل (العقدة الأم خالية) ولا توجد بيانات مستخدم. |
| [CloneNode](../../aspose.html.dom/node/clonenode)(bool) | إرجاع نسخة مكررة من هذه العقدة ، على سبيل المثال ، بمثابة مُنشئ نسخة عام للعقد. لا تحتوي العقدة المكررة على أصل (العقدة الأم خالية) ولا توجد بيانات مستخدم. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent)(Event) | تسمح هذه الطريقة بإرسال الأحداث إلى نموذج حدث عمليات التنفيذ. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes)() | إرجاع ما إذا كانت هذه العقدة (إذا كانت عنصرًا) لها أي سمات |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes)() | إرجاع ما إذا كان لهذه العقدة أي توابع. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore)(Node, Node) | يقوم بإدراج العقدة قبل تابع العقدة الفرعية الموجودة. إذا كان التابع فارغًا ، أدخل العقدة في نهاية قائمة العناصر الفرعية . إذا كان الكائن الفرعي عبارة عن كائن DocumentFragment ، فسيتم إدراج جميع توابعه ، بالترتيب نفسه ، قبل التابع. إذا كان الطفل موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace)(string) | يتحقق هذا الأسلوب مما إذا كانت مساحة الاسم المحددة هي مساحة الاسم الافتراضية أم لا. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode)(Node) | اختبار ما إذا كانت العقدتان متساويتان. تختبر هذه الطريقة المساواة بين العقد ، وليس التماثل (أي ما إذا كانت العقدتان مرجعيتان لنفس الكائن) والتي يمكن اختبارها باستخدام Node.isSameNode (). جميع العقد التي هي نفسها ستكون متساوية أيضًا ، على الرغم من أن العكس قد لا يكون صحيحًا. |
| [IsSameNode](../../aspose.html.dom/node/issamenode)(Node) | إرجاع ما إذا كانت هذه العقدة هي نفس العقدة المحددة. توفر هذه الطريقة طريقة لتحديد ما إذا كان مرجعان للعقدة يتم إرجاعهما بواسطة مرجع التطبيق نفس الكائن. عندما يكون مراجعان للعقدة مراجع لنفس الكائن ، حتى لو كان ذلك من خلال وكيل ، يمكن استخدام المراجع بشكل تبادلي تمامًا ، بحيث يكون لجميع السمات نفس القيم واستدعاء نفس طريقة DOM على أي مرجع له نفس التأثير دائمًا. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri)(string) | ابحث عن مساحة الاسم URI المرتبطة بالبادئة المحددة ، بدءًا من هذه العقدة. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix)(string) | ابحث عن البادئة المرتبطة بمساحة الاسم المحددة URI ، بدءًا من هذه العقدة. يتم تجاهل تعريفات مساحة الاسم الافتراضية بهذه الطريقة. راجع بحث بادئة مساحة الاسم للحصول على تفاصيل حول الخوارزمية المستخدمة بواسطة هذه الطريقة. |
| [Normalize](../../aspose.html.dom/node/normalize)() | وضع جميع العقد النصية في العمق الكامل للشجرة الفرعية أسفل هذه العقدة ، بما في ذلك عقد السمات ، في نموذج "عادي" حيث تفصل البنية فقط (على سبيل المثال ، العناصر والتعليقات وإرشادات المعالجة وأقسام CDATA ومراجع الكيانات) النص العقد ، أي لا توجد عقد نصية متجاورة ولا عقد نصية فارغة. يمكن استخدام هذا للتأكد من أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله ، ويكون مفيدًا عندما تكون العمليات (مثل عمليات بحث XPointer [XPointer]) التي تعتمد على بنية شجرة وثيقة معينة يستخدم. إذا كانت المعلمة "تطبيع الأحرف" لكائن DOMConfiguration المرفقة بـ Node.ownerDocument صحيحة ، فإن هذه الطريقة ستعمل أيضًا على تسوية أحرف العقد النصية بشكل كامل. |
| [QuerySelector](../../aspose.html.dom/documentfragment/queryselector)(string) | إرجاع العنصر الأول في المستند الذي يتطابق مع selector |
| [QuerySelectorAll](../../aspose.html.dom/documentfragment/queryselectorall)(string) | إرجاع قائمة NodeList لجميع العناصر الموجودة في المستند ، والتي تطابق selector |
| [RemoveChild](../../aspose.html.dom/node/removechild)(Node) | يزيل العقدة الفرعية التي أشار إليها oldChild من قائمة الأطفال ، ويعيدها . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.html.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild)(Node, Node) | يستبدل العقدة الفرعية oldChild بـ newChild في قائمة الأطفال ، ويعيد العقدة oldChild. إذا كان newChild هو كائن DocumentFragment ، فسيتم استبدال oldChild بكافة العناصر الفرعية DocumentFragment ، والتي يتم إدراجها بنفس الترتيب. إذا كان الطفل الجديد موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| override [ToString](../../aspose.html.dom/node/tostring)() | إرجاع أString الذي يمثل هذا المثال. |

### أنظر أيضا

* class [Node](../node)
* interface [IParentNode](../iparentnode)
* مساحة الاسم [Aspose.Html.Dom](../../aspose.html.dom)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
