---
title: "ICSS2Properties.Position"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية ICSS2Properties. قيم هذه الخاصية لها المعاني التالية"
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/position/
---
## ICSS2Properties.Position property

القيم لهذه الخاصية لها المعاني التالية:

static - الصندوق هو صندوق عادي، يتم ترتيبه وفقًا لـ [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow). الخصائص ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left) و ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top) لا تُطبق. relative - يتم حساب موضع الصندوق وفقًا لـ [normal flow](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#normal-flow) (يُطلق على ذلك موضع في التدفق العادي). ثم يُزاح الصندوق [relative](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#relative-positioning) إلى موضعه الطبيعي. عندما يكون الصندوق B موضعًا نسبيًا، يتم حساب موضع الصندوق التالي كما لو أن B لم يُزاح. absolute - يُحدد موضع الصندوق (وربما حجمه) باستخدام الخصائص ['left'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-left)، ['right'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-right)، ['top'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-top)، و ['bottom'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-bottom). هذه الخصائص تحدد الإزاحات بالنسبة إلى [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block). تُؤخذ الصناديق الموضوعة مطلقًا خارج التدفق العادي. وهذا يعني أنها لا تؤثر على تخطيط الأخوة اللاحقة. أيضًا، رغم أن الصناديق [absolutely positioned](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#absolutely-positioned) لها هوامش، إلا أنها لا [collapse](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#collapsing-margins) مع أي هوامش أخرى. fixed - يُحسب موضع الصندوق وفقًا لنموذج 'absolute'، ولكن بالإضافة إلى ذلك، يصبح الصندوق [fixed](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#fixed-positioning) بالنسبة إلى مرجع ما. في حالة [continuous media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#continuous-media-group)، يُثبت الصندوق بالنسبة إلى [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (ولا يتحرك عند التمرير). في حالة [paged media](https://www.w3.org/TR/1998/REC-CSS2-19980512/media.html#paged-media-group)، يُثبت الصندوق بالنسبة إلى الصفحة، حتى إذا تم رؤية تلك الصفحة عبر [viewport](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#viewport) (في حالة معاينة الطباعة، على سبيل المثال). قد يرغب المؤلفون في تحديد 'fixed' بطريقة تعتمد على الوسائط.

```java
public String Position { get; set; }
```

### قيمة الإرجاع

خاصية position

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
