---
title: "فئة Text"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.dom.Text. ترث واجهة Text من CharacterData وتمثل المحتوى النصي المسمى بيانات الأحرف في XML لعنصر Element أو سمة Attr"
type: docs

url: /ar/java/com.aspose.html.dom/text/
---
## Text class

واجهة Text ترث من CharacterData وتمثل المحتوى النصي (المعروف ببيانات الأحرف في XML) لعنصر Element أو سمة Attr.

```java
public class Text : CharacterData
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) الخاصية للقراءة فقط baseURI في واجهة Node تُعيد عنوان URL الأساسي المطلق للمستند الذي يحتوي على العقدة. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) الخاصية للقراءة فقط childNodes في واجهة Node تُعيد [`NodeList`](../../com.aspose.html.collections/nodelist/) حي لعقد الأطفال للعنصر المعطى حيث تُعطى العقدة الأولى الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | بيانات الأحرف للعقدة التي تنفذ هذه الواجهة. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) الخاصية read-only firstChild لواجهة [`Node`](../node/) تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم يكن للعقدة أي أطفال. |
| [getIsElementContentWhitespace](../../com.aspose.html.dom/text/iselementcontentwhitespace/) يُعيد ما إذا كانت عقدة النص هذه تحتوي على مسافات بيضاء ضمن محتوى العنصر، والتي تُسمى غالبًا بشكل غير دقيق "ignorable whitespace". |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) الخاصية read-only lastChild لواجهة [`Node`](../node/) تُعيد آخر طفل للعقدة. إذا كان أبُها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر أو عقدة نص أو عقدة تعليق. تُعيد null إذا لم توجد عناصر طفل. |
| [getLength](../../com.aspose.html.dom/characterdata/length/) عدد الوحدات 16-بت المتاحة عبر الخاصية data وطريقة subStringData أدناه. قد تكون قيمتها صفرًا، أي أن عقد CharacterData قد تكون فارغة. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) تُرجع الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](../node/element_node/) و[`ATTRIBUTE_NODE`](../node/attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة DOM المستوى 1، مثل [`Document.createElement()`](../document/createelement/)، تكون القيمة دائمًا null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) خاصية Element.packageURI للقراءة فقط تُعيد URI الحزمة للعنصر، أو null إذا لم يكن العنصر في حزمة. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) الخاصية read-only nextSibling لواجهة [`Node`](../node/) تُعيد العقدة التي تلي مباشرةً المحددة في [`childNodes`](../node/childnodes/) للوالد، أو تُعيد null إذا كانت العقدة المحددة هي آخر طفل في العنصر الأب. |
| [getNodeName](../../com.aspose.html.dom/text/nodename/) اسم هذه العقدة، حسب نوعها. |
| [getNodeType](../../com.aspose.html.dom/text/nodetype/) رمز يمثل نوع الكائن الأساسي. |
| [nodeValue](../../com.aspose.html.dom/text/nodevalue/) { get; set; } | قيمة هذه العقدة، حسب نوعها. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) خاصية ownerDocument للقراءة فقط في واجهة Node تُرجع كائن المستند الأعلى المستوى للعقدة. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) الخاصية read-only parentElement لواجهة [`Node`](../node/) تُعيد العنصر الأب لعقدة DOM وهو [`Element`](../element/)، أو null إذا لم يكن للعقدة أب، أو إذا كان أبها ليس عنصر DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) خاصية parentNode للقراءة فقط في واجهة Node تُرجع أب العقدة المحددة في شجرة DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | خاصية prefix للقراءة فقط تُعيد بادئة الحزمة للعنصر المحدد، أو null إذا لم تُحدد أي بادئة. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) الخاصية read-only previousSibling لواجهة [`Node`](../node/) تُعيد العقدة التي تسبق مباشرةً المحددة في قائمة [`childNodes`](../node/firstchild/) للوالد، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [textContent](../../com.aspose.html.dom/text/textcontent/) { get; set; } | هذه السمة تُرجع محتوى النص لهذه العقدة ونسلها. عندما تُحدد بأنها null، لا يؤثر تعيينها. عند التعيين، تُزال أي أطفال محتملين قد تكون للعقدة، وإذا لم تكن السلسلة الجديدة فارغة أو null، تُستبدل بعقدة نصية واحدة تحتوي على السلسلة التي تم تعيين هذه السمة إليها. |
| [getWholeText](../../com.aspose.html.dom/text/wholetext/) يُعيد كل نص عقد Text المتجاورة منطقيًا لهذه العقدة، مدموجًا بترتيب المستند. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | طريقة addEventListener() لواجهة [`EventTarget `](../eventtarget/) تُعدّ دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | تُعد طريقة addEventListener() في واجهة [EventTarget ](T:com.aspose.html.dom.EventTarget) دالة تُستدعى كلما تم تسليم الحدث المحدد إلى الهدف. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | تضيف طريقة appendChild() في واجهة Node عقدة إلى نهاية قائمة الأطفال لعقدة أب محددة. إذا كان الطفل المعطى إشارة إلى عقدة موجودة بالفعل في المستند، فإن appendChild() تنقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك ضرورة لإزالة العقدة من عقدة الأب قبل إلحاقها بعقدة أخرى). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | أضف السلسلة إلى نهاية بيانات الأحرف للعقدة. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | تُعيد طريقة cloneNode() في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضًا أم لا. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | تُعيد طريقة cloneNode() في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضًا أم لا. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | أزل نطاقًا من الوحدات 16-بت من العقدة. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | يُرسل حدثًا إلى الـ[`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) المحدد، (متزامنًا) مستدعيًا مستمعي الحدث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُرسل يدويًا باستخدام [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | يُجري مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع كائن ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | طريقة hasChildNodes() لواجهة Node تُعيد قيمة منطقية تُشير إلى ما إذا كان الـ[`Node`](../node/) المعطى يحتوي على عقد أطفال أم لا. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | تُدرج طريقة insertBefore() في واجهة Node عقدة قبل عقدة مرجعية كطفل لعقدة أب محددة. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | أدرج سلسلة في الموضع المحدد بوحدة 16-بت. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | تقبل طريقة isDefaultNamespace() في واجهة Node URI الحزمة كمعامل. تُعيد قيمة منطقية تكون true إذا كانت الحزمة هي الحزمة الافتراضية على العقدة المعطاة وfalse إذا لم تكن كذلك. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | طريقة isEqualNode() لواجهة [`Node`](../node/) تختبر ما إذا كانت عقدتان متساويتان. تكون العقدتان متساويتين عندما يكون لهما نفس النوع، والخصائص المعرّفة (للعناصر، يكون ذلك معرفهما، عدد الأطفال، وما إلى ذلك)، وتطابق سماتها، وما إلى ذلك. مجموعة البيانات المحددة التي يجب أن تتطابق تختلف حسب نوعي العقد. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | طريقة isSameNode() في واجهة Node هي اسم مستعار قديم للمشغل الصارم ===. أي أنها تختبر ما إذا كانت عقدتان هي نفسها (بمعنى آخر، ما إذا كانتا تشير إلى نفس الكائن). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | تأخذ طريقة lookupNamespaceURI() في واجهة Node بادئة كمعامل وتُعيد URI الحزمة المرتبط بها على العقدة المعطاة إذا وُجد (وnull إذا لم يُوجد). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | ترجع طريقة lookupPrefix() في واجهة Node سلسلة تحتوي على البادئة لURI حزمة معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُرجع أول بادئة. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | يضع جميع عقد `Text` في العمق الكامل للشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في شكل "normal" حيث تفصل البنية فقط (مثل [`elements`](../element/)، [`comments`](../comment/)، [`processing instructions`](../processinginstruction/)، [`CDATA sections`](../cdatasection/)، و[`entity references`](../entityreference/)) بين عقد `Text`، أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة المستند المحددة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../../com.aspose.html/configuration/) المرتبط بـ [`Node.ownerDocument`](../node/ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد Text بالكامل. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | طريقة removeChild() في واجهة Node تزيل عقدةً فرعيةً من DOM وتعيد العقدة التي أزيلت. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | تسمح هذه الطريقة بإزالة event listeners من event target. إذا تمت إزالته أثناء معالجة حدث، فلن يتم تشغيله بواسطة الإجراءات الحالية. لا يمكن أبدًا استدعاء event listeners بعد إزالتهم. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويُعيد عقدة oldChild. إذا كان newChild كائنًا من نوع [`DocumentFragment`](../documentfragment/)، يتم استبدال oldChild بجميع أطفال [`DocumentFragment`](../documentfragment/) الذين يُدرجون بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يتم إزالته أولاً. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | استبدل الأحرف بدءًا من الموضع المحدد بوحدة 16-بت بالسلسلة المحددة. |
| [replaceWholeText](../../com.aspose.html.dom/text/replacewholetext/)(String) | يستبدل نص العقدة الحالية وجميع العقد النصية المتجاورة منطقياً بالنص المحدد. يتم إزالة جميع العقد النصية المتجاورة منطقياً بما في ذلك العقدة الحالية ما لم تكن هي المستلم لنص الاستبدال. |
| [splitText](../../com.aspose.html.dom/text/splittext/)(int) | يقسم هذه العقدة إلى عقدتين عند الإزاحة المحددة، مع إبقاءهما في الشجرة كعقد شقيقة. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | يستخرج نطاقاً من البيانات من العقدة. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | يرجع سلسلة تمثل هذا الكائن. |

### انظر أيضًا

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
