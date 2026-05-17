---
title: "FontMatcher.MatchFontFallback"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة FontMatcher. يتم استدعاء هذه الطريقة إذا لم يتم العثور على خط مناسب في مجلدات البحث عن الخطوط. يجب أن تُرجع خط true type بناءً على fontMatchingProperties التي يمكنها عرض charCode أو null إذا لم يتوفر هذا الخط"
type: docs

url: /ar/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

يتم استدعاء هذه الطريقة إذا لم يتم العثور على خط مناسب في مجلدات البحث عن الخطوط. يجب أن تُعيد خطًا من النوع true بناءً على *fontMatchingProperties* الذي يمكنه عرض *charCode*، أو `null` إذا لم يكن هذا الخط متاحًا.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | خصائص الخط المطابق. |
| charCode | UInt32 | رمز الحرف الذي سيتم عرضه باستخدام الخط المطابق. |

### قيمة الإرجاع

مصفوفة بايت تحتوي على بيانات الخطوط أو `null`.

### انظر أيضًا

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
