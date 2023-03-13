---
title: Enum MarkdownFeatures
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Saving.MarkdownFeatures Sıralama. birMarkdownFeatures bayrak seti markdown. ye dönüştürülen öğeleri seçmek için kullanılan aşağıdaki bayraklardan sıfır veya daha fazlasının bir kümesidir.
type: docs
weight: 4620
url: /tr/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

bir`MarkdownFeatures` bayrak seti, markdown. 'ye dönüştürülen öğeleri seçmek için kullanılan aşağıdaki bayraklardan sıfır veya daha fazlasının bir kümesidir.

```csharp
[Flags]
public enum MarkdownFeatures
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| InlineHTML | `1` | Bu bayrak, HTML öğelerinin satır içine alınmasını sağlar. Bu bayrak, blok düzeyindeki öğelerden (örneğin,`div` ) kimin`indirim` öznitelik değeri eşittir`Çizgide` ortaya çıkan işaretlemeye eklenecek. |
| AutomaticParagraph | `2` | Bu bayrak, dönüştürülmesini sağlar`paragraf` elementler. Bu tür öğelerin içeriği ayrı satırlara yerleştirilecek, böylece işaretleme işleyicileri onu kaydıracaktır. |
| Header | `4` | Bu bayrak, dönüştürülmesini sağlar`başlık` elementler. |
| Blockquote | `8` | Bu bayrak, dönüştürülmesini sağlar`blok alıntı` elementler. |
| List | `10` | Bu bayrak, dönüştürülmesini sağlar`liste` elementler. |
| CodeBlock | `20` | Bu bayrak, kod bloklarının dönüştürülmesini sağlar. Kod bloğu 2 öğeden oluşur`ön` Ve`kod` , bu tür bir yapının içeriği "olduğu gibi" süreçlerdir. |
| HorizontalRule | `40` | Bu bayrak, dönüştürülmesini sağlar`yatay kurallar` . |
| Link | `80` | Bu bayrak, dönüştürülmesini sağlar`A` elementler. |
| Emphasis | `100` | Bu bayrak, dönüştürülmesini sağlar`vurgu` elementler. |
| InlineCode | `200` | Bu bayrak, dönüştürülmesini sağlar`kod` elementler. |
| Image | `400` | Bu bayrak, dönüştürülmesini sağlar`img` elementler. |
| LineBreak | `800` | Bu bayrak, dönüştürülmesini sağlar`br` elementler. |
| Video | `1000` | Bu bayrak, dönüştürülmesini sağlar`video` elementler. |
| Table | `2000` | Bu bayrak, dönüştürülmesini sağlar`masa` elementler. |
| TaskList | `4000` | Bu bayrak, görev listelerinin dönüştürülmesini sağlar. Görev listesi şunlardan oluşur:`giriş` öğesinin ilk çocuğu olması gereken öğe`liste` eleman ve kimin`tip` öznitelik değeri eşit olmalıdır`onay kutusu` . |
| Strikethrough | `8000` | Bu bayrak, dönüştürülmesini sağlar`del` elementler. |
| Strong | `10000` | Bu bayrak, dönüştürülmesini sağlar`güçlü` elementler. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Saving](../../aspose.html.saving/)
* toplantı [Aspose.HTML](../../)


