---
title: "فئة DOMException"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.dom.DOMException. تمثل واجهة DOMException حدثاً غير طبيعي يُسمى استثناءً يحدث نتيجة استدعاء طريقة أو الوصول إلى خاصية في واجهة برمجة تطبيقات الويب. هذا هو الأسلوب الأساسي لوصف حالات الخطأ في واجهات برمجة تطبيقات الويب."
type: docs

url: /ar/java/com.aspose.html.dom/domexception/
---
## DOMException class

واجهة DOMException تمثل حدثًا غير طبيعي (يسمى استثناء) يحدث نتيجة استدعاء طريقة أو الوصول إلى خاصية في واجهة برمجة تطبيقات الويب. هذا هو الأسلوب الأساسي لوصف حالات الخطأ في واجهات برمجة تطبيقات الويب.

```java
public class DOMException : PlatformException
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | ينشئ مثيلاً جديداً من الفئة `DOMException`. |
| [DOMException](domexception/#constructor_1)(String, String) | ينشئ مثيلاً جديداً من الفئة `DOMException`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) يُعيد قيمة تحتوي على أحد ثوابت رمز الخطأ، أو 0 إذا لم يتطابق أي منها. يُستخدم هذا الحقل لأسباب تاريخية. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) يُعيد سلسلة تمثل رسالة أو وصفاً مرتبطاً باسم الخطأ المعطى. |
| [getName](../../com.aspose.html.dom/domexception/name/) يُعيد سلسلة تحتوي على أحد السلاسل المرتبطة باسم الخطأ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | تم إلغاء العملية. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | لا يمكن استنساخ الكائن. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | إذا لم يتناسب النطاق المحدد من النص مع DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | إذا تم إدراج أي عقدة في مكان لا تنتمي إليه. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | إذا كان الفهرس أو الحجم سالباً، أو أكبر من القيمة المسموح بها. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | إذا تم محاولة إضافة سمة مستخدمة بالفعل في مكان آخر. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | إذا لم يكن معلمة أو عملية مدعومة من قبل الكائن الأساسي. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | إذا تم تحديد حرف غير صالح أو غير قانوني، مثل في اسم XML. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | التعبير يحتوي على خطأ في الصياغة أو غير صالح وفقاً لقواعد XPathEvaluator المحدد، أو يحتوي على دوال امتداد متخصصة أو متغيرات غير مدعومة من قبل هذا التنفيذ. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | إذا تم محاولة تعديل نوع الكائن الأساسي. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | العقدة المقدمة غير صحيحة أو لها سلف غير صحيح لهذه العملية. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | إذا تم محاولة استخدام كائن غير صالح، أو لم يعد صالحًا. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | إذا تم محاولة إنشاء أو تعديل كائن بطريقة غير صحيحة فيما يتعلق بالحزم. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | حدث خطأ في الشبكة. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | إذا تم محاولة الإشارة إلى عقدة في سياق لا توجد فيه. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | إذا لم يدعم التنفيذ النوع المطلوب من الكائن أو العملية. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | إذا تم تحديد بيانات لعقدة لا تدعم البيانات. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | إذا تم محاولة تعديل كائن حيث لا يُسمح بالتعديلات. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | تم تجاوز الحصة. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | العملية غير آمنة. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | إذا تم تحديد سلسلة غير صالحة أو غير قانونية. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | انتهت مهلة العملية. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | لا يمكن تحويل التعبير لإرجاع النوع المحدد. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | إذا كان نوع الكائن غير متوافق مع النوع المتوقع للمعامل المرتبط بالكائن. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | عنوان URL المعطى لا يطابق عنوان URL آخر. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | إذا كان استدعاء طريقة مثل insertBefore أو removeChild سيجعل العقدة غير صالحة فيما يتعلق بـ \"الصلاحية الجزئية\"، فسيتم رفع هذا الاستثناء ولن يتم تنفيذ العملية. يُستخدم هذا الكود في [DOM Level 3 Validation]. راجع هذه المواصفة لمزيد من المعلومات. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | إذا تم استخدام عقدة في مستند مختلف عن المستند الذي أنشأها (الذي لا يدعمها). |

### انظر أيضًا

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
