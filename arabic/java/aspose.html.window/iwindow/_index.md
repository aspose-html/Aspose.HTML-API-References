---
title: "واجهة IWindow"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.window.IWindow. كائن النافذة يمثل نافذة تحتوي على مستند DOM"
type: docs

url: /ar/java/com.aspose.html.window/iwindow/
---
## IWindow interface

كائن النافذة يمثل نافذة تحتوي على مستند DOM.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) يجب أن تُعيد خاصية document أحدث كائن Document لكائن Window. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) كائن frameElement لمستند. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) يُعيد كائن Storage يتيح لك حفظ أزواج المفتاح/القيمة في وكيل المستخدم. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) يجب أن تُعيد خاصية location في واجهة Window كائن Location الخاص بمستند كائن Window ذلك. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) خاصية opener في كائن Window، عند القراءة، يجب أن تُعيد كائن WindowProxy لسياق التصفح الذي تم إنشاء سياق التصفح الحالي منه (سياق التصفح المفتاح)، إذا كان موجودًا وما زال متاحًا، وإذا لم يتخلَّ سياق التصفح الحالي عن مُفتاحه؛ وإلا يجب أن تُعيد null. عند الكتابة، إذا كانت القيمة الجديدة null يجب على سياق التصفح الحالي أن يتخلى عن مُفتاحه؛ إذا كانت القيمة الجديدة أي شيء آخر يجب على وكيل المستخدم استدعاء الطريقة الداخلية [[DefineOwnProperty]] لكائن Window، مع تمرير اسم الخاصية "opener" كمفتاح الخاصية، ووصف الخاصية { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } كوصف الخاصية، حيث value هي القيمة الجديدة. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) خاصية parent في كائن Window لمستند داخل سياق تصفح b يجب أن تُعيد كائن WindowProxy لسياق التصفح الأب، إذا كان موجودًا (أي إذا كان b سياق تصفح فرعي)، أو كائن WindowProxy لسياق التصفح b نفسه، وإلا (أي إذا كان سياق تصفح أعلى مستوى أو سياق متداخل منفصل). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) يُعيد كائن WindowProxy لسياق تصفح كائن Window. |
| [getTop](../../com.aspose.html.window/iwindow/top/) خاصية top في كائن Window لمستند داخل سياق تصفح b يجب أن تُعيد كائن WindowProxy لسياق التصفح الأعلى مستوى (الذي سيكون كائن WindowProxy الخاص به إذا كان سياق تصفح أعلى مستوى)، إذا كان لديه واحد، أو كائن WindowProxy الخاص به وإلا (مثلاً إذا كان سياق تصفح متداخل منفصل). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) يُعيد كائن WindowProxy لسياق تصفح كائن Window. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | يعرض تنبيهًا موداليًا مع الرسالة المعطاة، وينتظر حتى يغلقه المستخدم. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي على بيانات ثنائية مُشفَّرة بـ base64، يفكّ شفرتها، ويُعيد سلسلة تتكون من أحرف في النطاق U+0000 إلى U+00FF، كل حرف يمثل بايتًا ثنائيًا بقيم 0x00 إلى 0xFF على التوالي، بما يتطابق مع تلك البيانات الثنائية. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي فقط على أحرف في النطاق U+0000 إلى U+00FF، كل حرف يمثل بايتًا ثنائيًا بقيم 0x00 إلى 0xFF على التوالي، ويحوّلها إلى تمثيل base64، ثم يُعيده. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | يعرض نافذة منبثقة مودالية بنص OK/Cancel مع الرسالة المعطاة، ينتظر حتى يغلقها المستخدم، ويُعيد true إذا نقر المستخدم على OK وfalse إذا نقر على Cancel. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | يُعيد كائن MediaQueryList جديد يمكن بعد ذلك استخدامه لتحديد ما إذا كان المستند يطابق سلسلة استعلام الوسائط، وكذلك لمراقبة المستند لاكتشاف متى يطابق (أو يتوقف عن المطابقة) ذلك الاستعلام. راجع مواصفة CSSOM View Module: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | يعرض نافذة منبثقة مودالية بحقل نص مع الرسالة المعطاة، ينتظر حتى يغلقها المستخدم، ويُعيد القيمة التي أدخلها المستخدم. إذا ألغى المستخدم النافذة، يُعيد null بدلاً من ذلك. إذا كان الوسيط الثاني موجودًا، تُستخدم القيمة المعطاة كقيمة افتراضية. |

### انظر أيضًا

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
