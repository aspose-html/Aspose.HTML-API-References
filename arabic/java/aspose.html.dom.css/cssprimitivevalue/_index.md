---
title: "فئة CSSPrimitiveValue"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.css.CSSPrimitiveValue class. تُشتق واجهة CSSPrimitiveValue من واجهة CSSValue وتمثل القيمة المحسوبة الحالية لخاصية CSS."
type: docs

url: /ar/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

تستمد واجهة CSSPrimitiveValue من واجهة CSSValue وتمثل القيمة المحسوبة الحالية لخاصية CSS.

ملاحظة: كانت هذه الواجهة جزءًا من محاولة لإنشاء نموذج كائن CSS مكتوب بنوع. تم التخلي عن هذه المحاولة، ومعظم المتصفحات لا تنفذها.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | خاصية cssText في واجهة [`CSSValue`](../cssvalue/) تمثل قيمة خاصية CSS المحسوبة الحالية. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) رمز يحدد نوع القيمة. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) نوع القيمة كما هو معرف في الثوابت المذكورة أعلاه. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | يحدد ما إذا كان الكائن المحدد يساوي هذه المثيلة. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | تُستخدم هذه الطريقة للحصول على قيمة Counter. إذا لم تحتوي قيمة CSS هذه على قيمة عداد، يتم رفع استثناء DOMException. يمكن تعديل الخاصية النمطية المقابلة باستخدام واجهة Counter. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | يُستخدم هذا الأسلوب للحصول على قيمة عائمة بوحدة محددة. إذا لم تحتوي قيمة CSS هذه على قيمة عائمة أو لا يمكن تحويلها إلى الوحدة المحددة، يتم رفع استثناء DOMException. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | يعيد رمز تجزئة لهذا الكائن. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | يُستخدم هذا الأسلوب للحصول على قيمة عدد صحيح بوحدة محددة. إذا لم تحتوي قيمة CSS هذه على قيمة عدد صحيح أو لا يمكن تحويلها إلى الوحدة المحددة، يتم رفع استثناء DOMException. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | تُستخدم هذه الطريقة لاسترجاع نوع كائن ECMAScript. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | يُستخدم هذا الأسلوب للحصول على قيمة المستطيل (Rect). إذا لم تحتوي قيمة CSS هذه على قيمة مستطيل، يتم رفع استثناء DOMException. يمكن تعديل الخاصية النمطية المقابلة باستخدام واجهة Rect. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | يُستخدم هذا الأسلوب للحصول على لون RGB. إذا لم تحتوي قيمة CSS هذه على قيمة لون RGB، يتم رفع استثناء DOMException. يمكن تعديل الخاصية النمطية المقابلة باستخدام واجهة RGBColor. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | يُستخدم هذا الأسلوب للحصول على قيمة سلسلة (String). إذا لم تحتوي قيمة CSS على قيمة سلسلة، يتم رفع استثناء DOMException. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | طريقة لتعيين القيمة العائمة بوحدة محددة. إذا لم تستطع الخاصية المرتبطة بهذه القيمة قبول الوحدة المحددة أو القيمة العائمة، ستبقى القيمة دون تغيير وسيتم رفع استثناء DOMException. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | طريقة لتعيين القيمة عدد صحيح بوحدة محددة. إذا لم تستطع الخاصية المرتبطة بهذه القيمة قبول الوحدة المحددة أو القيمة عدد صحيح، ستبقى القيمة دون تغيير وسيتم رفع استثناء DOMException. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | طريقة لتعيين قيمة السلسلة (String) بالوحدة المحددة. إذا لم تستطع الخاصية المرتبطة بهذه القيمة قبول الوحدة المحددة أو قيمة السلسلة، ستبقى القيمة دون تغيير وسيتم رفع استثناء DOMException. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | يعيد سلسلة تمثل هذا الكائن. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | القيمة هي دالة سمة. يمكن الحصول على القيمة باستخدام طريقة getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | القيمة هي طول (ch). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | القيمة هي طول (cm). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | القيمة هي دالة عداد أو عدادات. يمكن الحصول على القيمة باستخدام طريقة GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | القيمة هي زاوية (deg). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | القيمة هي رقم بعد غير معروف. يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | القيمة هي نقاط لكل سنتيمتر (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | القيمة هي نقاط لكل بوصة (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | القيمة هي نقاط لكل وحدة ‘px’ (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | القيمة هي طول (ems). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | القيمة هي طول (exs). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | القيمة هي زاوية (grad). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | القيمة هي تردد (Hz). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | القيمة هي معرف. يمكن الحصول على القيمة باستخدام طريقة getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | القيمة هي طول (in). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | القيمة هي تردد (kHz). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | القيمة هي طول (mm). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | القيمة هي وقت (ms). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | القيمة هي رقم بسيط. يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | القيمة هي طول (pc). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | القيمة هي نسبة مئوية. يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | القيمة هي طول (pt). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | القيمة هي طول (px). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | القيمة هي زاوية (rad). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | القيمة هي دالة rect. يمكن الحصول على القيمة باستخدام طريقة GetRectValue. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | القيمة هي طول (rem). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | القيمة هي لون RGB. يمكن الحصول على القيمة باستخدام طريقة GetRGBColorValue. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | القيمة هي وقت (s). يمكن الحصول على القيمة باستخدام طريقة getFloatValue. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | القيمة هي STRING. يمكن الحصول على القيمة باستخدام طريقة getStringValue. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | القيمة ليست قيمة CSS2 معروفة. لا يمكن الحصول على القيمة إلا باستخدام خاصية cssText. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | القيمة هي URI. يمكن الحصول على القيمة باستخدام طريقة getStringValue. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | القيمة هي نسبة مئوية من ارتفاع العرض الكامل. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | القيمة هي نسبة مئوية من عرض أو ارتفاع العرض، أيهما أكبر. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | القيمة هي نسبة مئوية من عرض أو ارتفاع العرض، أيهما أصغر. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | القيمة هي نسبة مئوية من عرض العرض الكامل. |

### انظر أيضًا

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
