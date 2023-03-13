---
title: FontMatcher.MatchFontFallback
second_title: Aspose.HTML لمرجع .NET API
description: FontMatcher طريقة. يتم استدعاء هذه الطريقة إذا لم يتم العثور على خط مناسب في مجلدات البحث عن الخطوط.fontMatchingProperties التي يمكن أن تجعلcharCode  أوباطل إذا كان هذا الخط غير متوفر.
type: docs
weight: 10
url: /ar/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

يتم استدعاء هذه الطريقة إذا لم يتم العثور على خط مناسب في مجلدات البحث عن الخطوط.*fontMatchingProperties* التي يمكن أن تجعل*charCode* ، أو`باطل` إذا كان هذا الخط غير متوفر.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | خصائص الخط المتطابق. |
| charCode | UInt32 | رمز الحرف الذي سيتم تقديمه باستخدام الخط المطابق. |

### قيمة الإرجاع

مصفوفة بايت تحتوي على بيانات الخطوط أو`باطل`.

### أنظر أيضا

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* مساحة الاسم [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* المجسم [Aspose.HTML](../../../)


