---
title: "تعداد MarkdownFeatures"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "التعداد com.aspose.html.saving.MarkdownFeatures. مجموعة أعلام MarkdownFeatures هي مجموعة من صفر أو أكثر من الأعلام التالية التي تُستخدم لاختيار العناصر التي تُحول إلى markdown"
type: docs

url: /ar/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

مجموعة أعلام `MarkdownFeatures` هي مجموعة من صفر أو أكثر من الأعلام التالية، والتي تُستخدم لاختيار العناصر التي تُحول إلى markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| InlineHTML | `1` | هذا العلم يُمكّن تضمين عناصر HTML. إذا تم تعيين هذا العلم، فإن عناصر المستوى الكتلي (مثل `div`) التي تكون قيمة سمة `markdown` الخاصة بها تساوي `inline` سيتم إدراجها في markdown الناتج. |
| AutomaticParagraph | `2` | هذا العلم يُمكّن تحويل عناصر `paragraph`. محتوى هذه العناصر سيُوضع على أسطر منفصلة، بحيث يقوم معالجات markdown بلفه. |
| Header | `4` | هذا العلم يُمكّن تحويل عناصر `header`. |
| Blockquote | `8` | هذا العلم يُمكّن تحويل عناصر `blockquote`. |
| List | `10` | هذا العلم يُمكّن تحويل عناصر `list`. |
| CodeBlock | `20` | هذا العلم يُمكّن تحويل كتل الشيفرة. تتكون كتلة الشيفرة من عنصرين `pre` و `code`، ومحتوى هذه البنية يُعالج كما هو. |
| HorizontalRule | `40` | هذا العلم يُمكّن تحويل `horizontal rules`. |
| Link | `80` | هذا العلم يُمكّن تحويل عناصر `a`. |
| Emphasis | `100` | تُتيح هذه العلامة تحويل عناصر `emphasis`. |
| InlineCode | `200` | تُتيح هذه العلامة تحويل عناصر `code`. |
| Image | `400` | تُتيح هذه العلامة تحويل عناصر `img`. |
| LineBreak | `800` | تُتيح هذه العلامة تحويل عناصر `br`. |
| Video | `1000` | تُتيح هذه العلامة تحويل عناصر `video`. |
| Table | `2000` | تُتيح هذه العلامة تحويل عناصر `table`. |
| TaskList | `4000` | تُتيح هذه العلامة تحويل قوائم المهام. تتكون قائمة المهام من عنصر `input`، والذي يجب أن يكون الطفل الأول لعنصر `list` ويجب أن تكون قيمة السمة `type` مساوية لـ `checkbox`. |
| Strikethrough | `8000` | تُتيح هذه العلامة تحويل عناصر `del`. |
| Strong | `10000` | تُتيح هذه العلامة تحويل عناصر `strong`. |

### انظر أيضًا

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
