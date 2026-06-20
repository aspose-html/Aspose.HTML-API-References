---
title: "ICSS2Properties.Azimuth"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية ICSS2Properties. الصوت المكاني هو خاصية أسلوبية مهمة للعرض السمعي. يوفر طريقة طبيعية للتمييز بين عدة أصوات كما هو الحال في الحياة الواقعية حيث نادراً ما يقف الناس جميعاً في نفس الموقع داخل الغرفة."
type: docs

url: /ar/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

الصوت المكاني هو خاصية أسلوبية مهمة للعرض السمعي. يوفر طريقة طبيعية للتمييز بين عدة أصوات، كما هو الحال في الحياة الواقعية (نادراً ما يقف الناس جميعاً في نفس الموقع داخل الغرفة).

```java
public String Azimuth { get; set; }
```

### قيمة الإرجاع

خاصية azimuth

### Property Value

القيم لها المعاني التالية:

angle - يتم وصف الموضع بزاوية ضمن النطاق '-360deg' إلى '360deg'. القيمة '0deg' تعني مباشرة أمامك في مركز مساحة الصوت. '90deg' تعني إلى اليمين، '180deg' خلف، و'270deg' (أو ما يعادلها بشكل أكثر ملاءمة '-90deg') إلى اليسار.

left-side - نفس '270deg'. مع 'behind'، '270deg'.

far-left - نفس '300deg'. مع 'behind'، '240deg'.

left - نفس '320deg'. مع 'behind'، '220deg'.

center-left - نفس '340deg'. مع 'behind'، '200deg'.

center - نفس '0deg'. مع 'behind'، '180deg'.

center-right - نفس '20deg'. مع 'behind'، '160deg'.

right - نفس '40deg'. مع 'behind'، '140deg'.

far-right - نفس '60deg'. مع 'behind'، '120deg'.

right-side - نفس '90deg'. مع 'behind'، '90deg'.

leftwards - يحرك الصوت إلى اليسار، بالنسبة للزاوية الحالية. بدقة أكبر، يطرح 20 درجة. تُجرى العمليات الحسابية بتطبيق باقي القسمة على 360 درجة. لاحظ أن 'leftwards' يُوصف بدقة أكبر بأنه \"turned counter-clockwise,\"، لأنه دائمًا يطرح 20 درجة، حتى إذا كانت الزاوية الأفقية الموروثة بالفعل خلف المستمع (في هذه الحالة يبدو أن الصوت يتحرك إلى اليمين).

rightwards - يحرك الصوت إلى اليمين، بالنسبة للزاوية الحالية. بدقة أكبر، يضيف 20 درجة. راجع 'leftwards' للعمليات الحسابية.

### انظر أيضًا

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
