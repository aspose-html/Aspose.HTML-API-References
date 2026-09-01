---
title: "TypeInfo.IsDerivedFrom"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة TypeInfo. تُعيد هذه الطريقة ما إذا كان هناك اشتقاق بين تعريف النوع المرجعي أي TypeInfo الذي تُستدعى منه الطريقة وتعريف النوع الآخر أي الذي يُمرَّر كمعامل"
type: docs

url: /ar/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

تعيد هذه الطريقة ما إذا كان هناك اشتقاق بين تعريف نوع المرجع، أي TypeInfo التي تُستدعى عليها الطريقة، وتعريف النوع الآخر، أي ذلك الممرّر كمعاملات.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| typeNamespaceArg | String | حزمة تعريف النوع الآخر |
| typeNameArg | String | اسم تعريف النوع الآخر. |
| derivationMethod | UInt64 | نوع الاشتقاق والشروط المطبقة بين نوعين، كما هو موضح في قائمة الثوابت المقدمة في هذه الواجهة. |

### قيمة الإرجاع

إذا كان مخطط المستند هو DTD أو لا يوجد مخطط مرتبط بالمستند، فإن هذه الطريقة ستعيد دائمًا false. إذا كان مخطط المستند هو XML Schema، فإن الطريقة ستعيد true إذا كان تعريف النوع المرجعي مشتقًا من تعريف النوع الآخر وفقًا لمعلمة الاشتقاق. إذا كانت قيمة المعلمة 0 (لم يتم ضبط أي بت إلى 1 لمعلمة derivationMethod)، فإن الطريقة ستعيد true إذا كان يمكن الوصول إلى تعريف النوع الآخر عن طريق تكرار أي تركيبة من {base type definition}، {item type definition} أو {member type definitions} بدءًا من تعريف النوع المرجعي.

### انظر أيضًا

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
