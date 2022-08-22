---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML لمرجع .NET API
description: ملف Aspose.html.Dom.Css مساحة الاسم مخصصة لجميع عمليات التلاعب ذات الصلة بـ CSS.
type: docs
weight: 70
url: /ar/net/aspose.html.dom.css/
---
ملف **Aspose.html.Dom.Css** مساحة الاسم مخصصة لجميع عمليات التلاعب ذات الصلة بـ CSS.

## الطبقات

| فصل | وصف |
| --- | --- |
| [Counter](./counter) | يتم استخدام واجهة العداد لتمثيل أي قيمة دالة للعداد. تعكس هذه الواجهة القيم الموجودة في خاصية النمط الأساسية. |
| [CSSPrimitiveValue](./cssprimitivevalue) | تمثل واجهة CSSPrimitiveValue قيمة CSS واحدة. يمكن استخدام هذه الواجهة لتحديد قيمة خاصية نمط معينة تم تعيينها حاليًا في كتلة أو لتعيين خاصية نمط معينة بشكل صريح داخل الكتلة. يمكن الحصول على مثيل لهذه الواجهة من طريقة getPropertyCSSValue لواجهة CSSStyleDeclusion. لا يحدث كائن CSSPrimitiveValue إلا في سياق خاصية CSS. |
| [CSSValue](./cssvalue) | يمثل قيمة بسيطة أو معقدة. لا يحدث كائن CSSValue إلا في سياق خاصية CSS. |
| [CSSValueList](./cssvaluelist) | توفر واجهة CSSValueList تجريدًا لمجموعة مرتبة من قيم CSS. |
| [Rect](./rect) | تُستخدم واجهة Rect لتمثيل أي قيمة مستقيمة. تعكس هذه الواجهة القيم الموجودة في خاصية النمط الأساسية. ومن ثم ، فإن التعديلات التي تم إجراؤها على كائنات CSSPrimitiveValue تعدل خاصية النمط. |
| [RGBColor](./rgbcolor) | تُستخدم واجهة RGBColor لتمثيل أي قيمة لونية RGB. تعكس هذه الواجهة القيم الموجودة في خاصية النمط الأساسية. ومن ثم ، فإن التعديلات التي تم إجراؤها على كائنات CSSPrimitiveValue تعدل خاصية النمط. |
## واجهات

| واجهه المستخدم | وصف |
| --- | --- |
| [ICSS2Properties](./icss2properties) | يوفر واجهة لخصائص CSS2 وتعيين القيم في سياق عنصر HTML معين |
| [ICSSCharsetRule](./icsscharsetrule) | تمثل واجهة CSSCharsetRule قاعدةcharset في ورقة أنماط CSS. لا تؤثر قيمة سمة الترميز على ترميز البيانات النصية في كائنات DOM ؛ هذا الترميز دائمًا هو UTF-16. بعد تحميل ورقة الأنماط ، تكون قيمة سمة الترميز هي القيمة الموجودة في قاعدةcharset. إذا لم يكن هناكcharset في المستند الأصلي ، فلن يتم إنشاء CSSCharsetRule. يمكن أيضًا استخدام قيمة سمة التشفير كتلميح للتشفير المستخدم في إنشاء تسلسل لورقة الأنماط. |
| [ICSSCounterStyleRule](./icsscounterstylerule) | تسمح قاعدة @ counter-style للمؤلفين بتعريف نمط عداد مخصص. |
| [ICSSFontFaceRule](./icssfontfacerule) | تمثل واجهة CSSFontFaceRule قاعدة @ font-face في ورقة أنماط CSS. تُستخدم قاعدة @ font-face للاحتفاظ بمجموعة من أوصاف الخط. |
| [ICSSImportRule](./icssimportrule) | تمثل واجهة CSSImportRule قاعدةimport داخل ورقة أنماط CSS. تُستخدم قاعدةimport لاستيراد قواعد الأنماط من أوراق الأنماط الأخرى. |
| [ICSSKeyframeRule](./icsskeyframerule) | تمثل واجهة CSSKeyframeRule قاعدة النمط لمفتاح واحد. |
| [ICSSKeyframesRule](./icsskeyframesrule) | تمثل واجهة CSSKeyframesRule مجموعة كاملة من الإطارات الرئيسية لرسم متحرك واحد |
| [ICSSMarginRule](./icssmarginrule) | تمثل واجهة CSSMarginRule هامشًا في القاعدة . |
| [ICSSMediaRule](./icssmediarule) | تمثل واجهة CSSMediaRule قاعدةmedia في ورقة أنماط CSS. يمكن استخدام قاعدةmedia لتحديد قواعد الأنماط لأنواع وسائط معينة. |
| [ICSSPageRule](./icsspagerule) | تمثل واجهة CSSPageRule قاعدة @ صفحة داخل ورقة أنماط CSS. تُستخدم القاعدةpage لتحديد الأبعاد والاتجاه والهوامش وما إلى ذلك لمربع الصفحة للوسائط المقسمة إلى صفحات. |
| [ICSSRule](./icssrule) | واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من عبارات CSS. يتضمن هذا كلاً من مجموعات القواعد و at-rules. من المتوقع أن يحافظ التطبيق على جميع القواعد المحددة في ورقة أنماط CSS ، حتى إذا لم يتعرف المحلل اللغوي على القاعدة. يتم تمثيل القواعد غير المعترف بها باستخدام!:ICSSUnknownRule الواجهة . |
| [ICSSRuleList](./icssrulelist) | توفر واجهة CSSRuleList تجريدًا لمجموعة مرتبة من قواعد CSS. |
| [ICSSStyleDeclaration](./icssstyledeclaration) | تمثل واجهة CSSStyleDeclusion كتلة إعلان CSS واحدة. يمكن استخدام هذه الواجهة لتحديد خصائص النمط المعينة حاليًا في كتلة أو لتعيين خصائص النمط بشكل صريح داخل الكتلة. |
| [ICSSStyleRule](./icssstylerule) | تمثل واجهة CSSStyleRule قاعدة واحدة تم تعيينها في ورقة أنماط CSS. |
| [ICSSStyleSheet](./icssstylesheet) | واجهة CSSStyleSheet هي واجهة ملموسة تستخدم لتمثيل ورقة أنماط CSS ، أي ورقة أنماط يكون نوع محتواها "text / css" . |
| [ICSSUnknownRule](./icssunknownrule) | تمثل واجهة CSSUnknownRule قاعدة عامة لا يدعمها وكيل المستخدم هذا. |
| [ICSSValueList](./icssvaluelist) | توفر الواجهة تجريدًا لمجموعة مرتبة من قيم CSS. |
| [IDocumentCSS](./idocumentcss) | تمثل هذه الواجهة مستندًا باستخدام طريقة عرض CSS . |
| [IDocumentStyle](./idocumentstyle) | توفر واجهة DocumentStyle آلية يمكن من خلالها استرداد أوراق الأنماط المضمنة في المستند. التوقع هو أنه يمكن الحصول على مثيل لواجهة DocumentStyle باستخدام طرق الصب الخاصة بالربط على مثيل لواجهة المستند. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle) | يتم عرض معلومات النمط المضمنة المرفقة بالعناصر من خلال سمة النمط. يمثل هذا محتويات سمة STYLE لعناصر HTML (أو عناصر في مخططات أو DTD أخرى تستخدم سمة STYLE بنفس الطريقة). |
| [ILinkStyle](./ilinkstyle) | توفر واجهة LinkStyle آلية يمكن من خلالها استرداد ورقة الأنماط من العقدة المسؤولة عن ربطها بمستند. يمكن الحصول على مثيل لواجهة LinkStyle باستخدام طرق الصب الخاصة بالربط على مثيل لعقدة ربط (HTMLLinkElement أو HTMLStyleElement أو ProcessingInstruction في DOM Level 2) . |
| [IMediaList](./imedialist) | توفر واجهة MediaList تجريدًا لمجموعة مرتبة من الوسائط ، دون تعريف أو تقييد كيفية تنفيذ هذه المجموعة. القائمة الفارغة هي نفس القائمة التي تحتوي على الوسيط "الكل". |
| [IStyleSheet](./istylesheet) | واجهة StyleSheet هي الواجهة الأساسية المجردة لأي نوع من أوراق الأنماط. إنها تمثل ورقة نمط واحدة مرتبطة بمستند منظم. |
| [IStyleSheetList](./istylesheetlist) | توفر واجهة StyleSheetList تجريدًا لمجموعة مرتبة من أوراق الأنماط. |
| [IViewCSS](./iviewcss) | تمثل هذه الواجهة طريقة عرض CSS . |
## تعداد

| تعداد | وصف |
| --- | --- |
| [CSSEngineMode](./cssenginemode) | يحدد CSS وضع المحرك |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
