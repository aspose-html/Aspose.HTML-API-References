---
title: "com.aspose.html.dom.css"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "يوفر واجهات لمواصفة نمط DOM المستوى 2. أوراق الأنماط المتتالية CSS هي لغة أوراق أنماط تسمح للمؤلفين والمستخدمين بإرفاق الأنماط مثل الخطوط والمسافات إلى المستندات المهيكلة مثل مستندات HTML وتطبيقات XML. يدعم أوراق الأنماط الخاصة بوسائط معينة حتى يتمكن المؤلفون من تخصيص عرض مستنداتهم للمتصفحات البصرية، الأجهزة السمعية، الطابعات، أجهزة برايل، الأجهزة المحمولة وغيرها. كما يدعم تموضع المحتوى وميزات تخطيط الجداول للتعريب وبعض الخصائص المتعلقة بواجهة المستخدم. من خلال فصل نمط العرض للمستندات عن محتواها، يبسط CSS إنشاء الويب وصيانة المواقع."
type: docs

url: /ar/java/com.aspose.html.dom.css/
---
توفر واجهات لمواصفات نمط المستوى 2 للـ DOM. أوراق الأنماط المتتالية (CSS) هي لغة أوراق أنماط تسمح للمؤلفين والمستخدمين بإرفاق الأنماط (مثل الخطوط والمسافات) بالمستندات المهيكلة (مثل مستندات HTML وتطبيقات XML). تدعم أوراق الأنماط الخاصة بالوسائط بحيث يمكن للمؤلفين تخصيص عرض مستنداتهم للمتصفحات البصرية، الأجهزة السمعية، الطابعات، أجهزة البرايل، الأجهزة المحمولة، إلخ. كما تدعم تموضع المحتوى، تخطيط الجداول، ميزات التعريب وبعض الخصائص المتعلقة بواجهة المستخدم. من خلال فصل نمط عرض المستندات عن محتواها، يبسط CSS عملية إنشاء الويب وصيانة المواقع.

## الفئات

| فئة | الوصف |
| --- | --- |
| [Counter](./counter/) | تُستخدم واجهة Counter لتمثيل أي قيمة عدّ أو قيمة دالة العدّات. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | تشتق واجهة CSSPrimitiveValue من واجهة CSSValue وتمثل القيمة المحسوبة الحالية لخاصية CSS. |
| [CSSValue](./cssvalue/) | يمثل قيمة بسيطة أو مركبة. كائن CSSValue يظهر فقط في سياق خاصية CSS. |
| [CSSValueList](./cssvaluelist/) | توفر واجهة CSSValueList تجريد مجموعة مرتبة من قيم CSS. |
| [Rect](./rect/) | تُستخدم واجهة Rect لتمثيل أي قيمة مستطيلة. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. وبالتالي، التعديلات التي تُجرى على كائنات [`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/) تُعدّل خاصية النمط. |
| [RGBColor](./rgbcolor/) | تُستخدم واجهة RGBColor لتمثيل أي قيمة لون RGB. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. وبالتالي، التعديلات التي تُجرى على كائنات CSSPrimitiveValue تُعدّل خاصية النمط. |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | تمثل واجهة CSS2Properties آلية مريحة لاسترجاع وتعيين الخصائص داخل [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). تتطابق سمات هذه الواجهة مع جميع الخصائص المحددة في CSS2. الحصول على سمة من هذه الواجهة يعادل استدعاء طريقة getPropertyValue في واجهة [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). تعيين سمة في هذه الواجهة يعادل استدعاء طريقة setProperty في واجهة [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). |
| [ICSSCharsetRule](./icsscharsetrule/) | تمثل واجهة CSSCharsetRule قاعدة @charset في ورقة أنماط CSS. لا يؤثر قيمة سمة الترميز على ترميز بيانات النص في كائنات DOM؛ هذا الترميز يكون دائمًا UTF-16. بعد تحميل ورقة الأنماط، تكون قيمة سمة الترميز هي القيمة الموجودة في قاعدة @charset. إذا لم توجد قاعدة @charset في المستند الأصلي، فلن يتم إنشاء CSSCharsetRule. قد تُستخدم قيمة سمة الترميز أيضًا كإشارة للترميز المستخدم عند تسلسل ورقة الأنماط. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | تمثل واجهة CSSCounterStyleRule قاعدة @counter-style التي تسمح للمؤلفين بتعريف نمط عدّ مخصص. |
| [ICSSFontFaceRule](./icssfontfacerule/) | تمثل واجهة CSSFontFaceRule قاعدة @font-face في ورقة أنماط CSS. تُستخدم قاعدة @font-face لحفظ مجموعة من أوصاف الخطوط. |
| [ICSSImportRule](./icssimportrule/) | تمثل واجهة CSSImportRule قاعدة @import داخل ورقة أنماط CSS. تُستخدم قاعدة @import لاستيراد قواعد الأنماط من أوراق أنماط أخرى. |
| [ICSSKeyframeRule](./icsskeyframerule/) | تصف واجهة [`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/) كائنًا يمثل مجموعة من الأنماط لإطار رئيسي معين. وهي تتطابق مع محتويات إطار رئيسي واحد من قاعدة @keyframes. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | تسترجع وتعيّن خاصية name في واجهة CSSKeyframeRule اسم الرسوم المتحركة كما يُستخدم في خاصية animation-name. |
| [ICSSMarginRule](./icssmarginrule/) | تمثل واجهة CSSMarginRule قاعدة هامش (مثل @top-left) في قاعدة @page. |
| [ICSSMediaRule](./icssmediarule/) | تمثل واجهة CSSMediaRule قاعدة @media في ورقة أنماط CSS. يمكن استخدام قاعدة @media لتحديد قواعد الأنماط لأنواع وسائط محددة. |
| [ICSSPageRule](./icsspagerule/) | تمثل واجهة CSSPageRule قاعدة @page داخل ورقة أنماط CSS. تُستخدم قاعدة @page لتحديد الأبعاد، الاتجاه، الهوامش، إلخ، لصندوق الصفحة للوسائط المرقّمة. |
| [ICSSRule](./icssrule/) | واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من بيانات CSS. وتشمل مجموعات القواعد والقواعد الخاصة. من المتوقع أن تحتفظ أي تنفيذ بجميع القواعد المحددة في ورقة أنماط CSS، حتى إذا لم يتعرف المُحلل على القاعدة. تُمثَّل القواعد غير المعروفة باستخدام هذه الواجهة. |
| [ICSSRuleList](./icssrulelist/) | تمثل CSSRuleList مجموعة مرتبة من كائنات [`CSSRule`](../com.aspose.html.dom.css/icssrule/) للقراءة فقط. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | واجهة CSSStyleDeclaration تمثل كائنًا هو كتلة إعلان CSS، وتعرض معلومات النمط ومجموعة من الأساليب والخصائص المتعلقة بالنمط. |
| [ICSSStyleRule](./icssstylerule/) | واجهة CSSStyleRule تمثل قاعدة نمط CSS واحدة. يجب أن تُعيد خاصية selectorText عند الحصول عليها نتيجة تسلسل مجموعة المحددات المرتبطة. |
| [ICSSStyleSheet](./icssstylesheet/) | واجهة CSSStyleSheet تمثل ورقة أنماط CSS واحدة، وتتيح لك فحص وتعديل قائمة القواعد الموجودة في ورقة الأنماط. إنها ترث الخصائص والأساليب من والدها، [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/). |
| [ICSSUnknownRule](./icssunknownrule/) | واجهة CSSUnknownRule تمثل قاعدة‑at غير مدعومة من قبل هذا المتصفح. |
| [ICSSValueList](./icssvaluelist/) | واجهة CSSValueList مشتقة من واجهة [`CSSValue`](../com.aspose.html.dom.css/cssvalue/) وتوفر تجريدًا لمجموعة مرتبة من قيم CSS. |
| [IDocumentCSS](./idocumentcss/) | هذه الواجهة تمثل مستندًا مع عرض CSS. |
| [IDocumentStyle](./idocumentstyle/) | واجهة DocumentStyle توفر آلية يمكن من خلالها استرجاع أوراق الأنماط المدمجة في المستند. من المتوقع أنه يمكن الحصول على مثال من واجهة DocumentStyle باستخدام طرق التحويل الخاصة بالربط على مثال من واجهة Document. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | معلومات النمط المضمنة المرفقة بالعناصر تُعرض عبر سمة style. هذا يمثل محتويات سمة STYLE لعناصر HTML (أو العناصر في مخططات أو DTDs أخرى تستخدم سمة STYLE بنفس الطريقة). من المتوقع أنه يمكن الحصول على مثال من واجهة ElementCSSInlineStyle باستخدام طرق التحويل الخاصة بالربط على مثال من واجهة Element عندما يدعم العنصر معلومات نمط CSS مضمنة. |
| [ILinkStyle](./ilinkstyle/) | واجهة LinkStyle توفر آلية يمكن من خلالها استرجاع ورقة نمط من العقدة المسؤولة عن ربطها بالمستند. يمكن الحصول على مثال من واجهة LinkStyle باستخدام طرق التحويل الخاصة بالربط على مثال من عقدة ربط (HTMLLinkElement، |
| [IMediaList](./imedialist/) | واجهة MediaList توفر تجريدًا لمجموعة مرتبة من الوسائط، دون تعريف أو تقييد كيفية تنفيذ هذه المجموعة. القائمة الفارغة تعادل القائمة التي تحتوي على الوسيط "all". |
| [IStyleSheet](./istylesheet/) | واجهة StyleSheet هي الواجهة الأساسية المجردة لأي نوع من أوراق الأنماط. إنها تمثل ورقة نمط واحدة مرتبطة بمستند منظم. في HTML، تمثل واجهة StyleSheet إما ورقة نمط خارجية، تُدرج عبر عنصر HTML LINK، أو عنصر STYLE مضمن. في XML، تمثل هذه الواجهة ورقة نمط خارجية، تُدرج عبر تعليمات معالجة ورقة الأنماط. ستقوم أوراق أنماط CSS بتنفيذ الواجهة المتخصصة أكثر [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/). |
| [IStyleSheetList](./istylesheetlist/) | واجهة StyleSheetList تمثل قائمة من كائنات [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/). يمكن إرجاع مثال من هذا الكائن عبر [`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/). |
| [IViewCSS](./iviewcss/) | واجهة IViewCSS تمثل امتدادًا لكائن Window يمنح الوصول إلى قيم جميع خصائص CSS لعنصر. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | يحدد وضع CSSEngine. للقيم المعاني التالية: |
