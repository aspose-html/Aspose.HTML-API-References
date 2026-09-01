---
title: "تعداد MarkdownFeatures"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "التعداد com.aspose.html.saving.MarkdownFeatures. مجموعة أعلام MarkdownFeatures هي مجموعة من صفر أو أكثر من الأعلام التالية التي تُستخدم لتحديد العناصر التي تُحول إلى markdown"
type: docs

url: /ar/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

مجموعة أعلام `MarkdownFeatures` هي مجموعة من صفر أو أكثر من الأعلام التالية، والتي تُستخدم لتحديد العناصر التي تُحول إلى markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| InlineHTML | `1` | هذه العلامة تمكّن تضمين عناصر HTML داخل النص. إذا تم تعيين هذه العلامة، فسيتم إدراج عناصر المستوى الكتلي (مثل `div`) التي تكون قيمة سمة `markdown` الخاصة بها مساوية لـ `inline` في markdown الناتج. |
| AutomaticParagraph | `2` | هذه العلامة تمكّن تحويل عناصر `paragraph`. سيُوضع محتوى هذه العناصر على أسطر منفصلة، وبالتالي سيقوم معالجات markdown بلفه. |
| Header | `4` | هذه العلامة تمكّن تحويل عناصر `header`. |
| Blockquote | `8` | هذه العلامة تمكّن تحويل عناصر `blockquote`. |
| List | `10` | هذه العلامة تمكّن تحويل عناصر `list`. |
| CodeBlock | `20` | هذه العلامة تمكّن تحويل كتل الشيفرة. تتكون كتلة الشيفرة من عنصرين `pre` و `code`، ويتم معالجة محتوى هذا التركيب "كما هو". |
| HorizontalRule | `40` | هذه العلامة تمكّن تحويل `horizontal rules`. |
| Link | `80` | هذه العلامة تمكّن تحويل عناصر `a`. |
| Emphasis | `100` | هذا العلم يتيح تحويل عناصر `emphasis`. |
| InlineCode | `200` | هذا العلم يتيح تحويل عناصر `code`. |
| Image | `400` | هذا العلم يتيح تحويل عناصر `img`. |
| LineBreak | `800` | هذا العلم يتيح تحويل عناصر `br`. |
| Video | `1000` | هذا العلم يتيح تحويل عناصر `video`. |
| Table | `2000` | هذا العلم يتيح تحويل عناصر `table`. |
| TaskList | `4000` | هذا العلم يتيح تحويل قوائم المهام. تتكون قائمة المهام من عنصر `input`، والذي يجب أن يكون الطفل الأول لعنصر `list` وتكون قيمة سمة `type` الخاصة به مساوية لـ `checkbox`. |
| Strikethrough | `8000` | هذا العلم يتيح تحويل عناصر `del`. |
| Strong | `10000` | هذا العلم يتيح تحويل عناصر `strong`. |

### انظر أيضًا

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
