---
title: "واجهة IXPathResult"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.xpath.IXPathResult. تمثل واجهة XPathResult نتيجة تقييم تعبير XPath 1.0 ضمن سياق عقدة معينة. بما أن تقييم تعبير XPath يمكن أن ينتج أنواعًا مختلفة من النتائج، يتيح هذا الكائن إمكانية اكتشاف نوع النتيجة وقيمتها والتعامل معها."
type: docs

url: /ar/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

الواجهة `XPathResult` تمثل نتيجة تقييم تعبير XPath 1.0 ضمن سياق عقدة معينة. بما أن تقييم تعبير XPath يمكن أن ينتج أنواعًا مختلفة من النتائج، يتيح هذا الكائن إمكانية اكتشاف نوع النتيجة وقيمتها ومعالجتها.

```java
public interface IXPathResult
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) قيمة هذه النتيجة المنطقية. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) يدل على أن المتكرر أصبح غير صالح. صحيح إذا كان `resultType` هو نوع `UnorderedNodeIterator` أو نوع `OrderedNodeIterator` وتم تعديل المستند منذ إرجاع هذه النتيجة. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) قيمة هذه النتيجة العددية. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) رمز يمثل نوع هذه النتيجة، كما هو معرف في تعداد http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) قيمة نتيجة العقدة المفردة هذه، والتي قد تكون `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) عدد العقد في لقطة النتيجة. القيم الصالحة لمؤشرات snapshotItem هي `0` إلى `snapshotLength-1` شاملة. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) قيمة نتيجة السلسلة هذه. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | يتكرر ويعيد العقدة التالية من مجموعة العقد أو `null` إذا لم يتبق أي عقد. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | يعيد العنصر رقم `index` في مجموعة اللقطة. إذا كان `index` أكبر من أو يساوي عدد العقد في القائمة، فإن هذه الطريقة تعيد `null`. على عكس نتيجة المكرّر، لا تصبح اللقطة غير صالحة، ولكن قد لا تتطابق مع المستند الحالي إذا تم تغييره. |

### انظر أيضًا

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
