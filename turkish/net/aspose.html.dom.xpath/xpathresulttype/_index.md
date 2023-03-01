---
title: Enum XPathResultType
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.XPath.XPathResultType Sıralama. Bunun ne tür bir sonuç olduğunu gösteren işaretsiz bir kısa devre. Belirli bir isetipbelirtilirse sonuç gerekli ve mümkün olan yerlerde XPath türü dönüştürmeler kullanılarak karşılık gelen türü olarak döndürülür.
type: docs
weight: 2610
url: /tr/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Bunun ne tür bir sonuç olduğunu gösteren işaretsiz bir kısa devre. Belirli bir ise`tip`belirtilirse sonuç, gerekli ve mümkün olan yerlerde XPath türü dönüştürmeler kullanılarak karşılık gelen türü olarak döndürülür.

```csharp
public enum XPathResultType
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Any | `0` | Bu kod belirli bir türü temsil etmiyor. XPath ifadesinin değerlendirilmesi asla bu türü üretmeyecektir. Bu tür istenirse, o zaman değerlendirme, ifadenin değerlendirilmesinden doğal olarak kaynaklanan tür ne olursa olsun, döndürür. Doğal sonucu, ne zaman ayarlanmış bir düğüm ise`Herhangi` tür istendi, ardından`UnorderedNodeYineleyici` her zaman elde edilen türdür. Bir düğüm kümesinin diğer herhangi bir temsili açıkça talep edilmelidir. |
| Number | `1` | Sonuç, [XPath 1.0] tarafından tanımlanan bir sayıdır. Belge değişikliği, sayıyı geçersiz kılmaz, ancak yeniden değerlendirmenin aynı sayıyı vermeyeceği anlamına gelebilir. |
| String | `2` | Sonuç, [XPath 1.0] tarafından tanımlanan bir dizidir. Belge değişikliği dizeyi geçersiz kılmaz, ancak dizenin artık geçerli belgeye karşılık gelmediği anlamına gelebilir. |
| Boolean | `3` | Sonuç, [XPath 1.0] tarafından tanımlandığı gibi bir booledir. Belge değişikliği boole değerini geçersiz kılmaz, ancak yeniden değerlendirmenin aynı boole değerini vermeyeceği anlamına gelebilir. |
| UnorderedNodeIterator | `4` | Sonuç, yinelemeli olarak erişilecek [XPath 1.0] tarafından tanımlandığı şekilde bir düğüm setidir, , düğümleri belirli bir sırada üretmeyebilir. Belge değişikliği, yinelemesini geçersiz kılar. Bu, sonuç bir düğüm kümesiyse döndürülen varsayılan türdür ve`Herhangi` türü isteniyor. |
| OrderedNodeIterator | `5` | Sonuç, [XPath 1.0] tarafından tanımlandığı şekilde, yinelemeli olarak erişilecek bir düğüm kümesidir, , belge sıralı düğümler üretecektir. Belge değişikliği yinelemeyi geçersiz kılar. |
| UnorderedNodeSnapshot | `6` | Sonuç, [XPath 1.0] tarafından tanımlandığı şekilde, belirli bir sırada olmayabilecek düğümlerin anlık görüntü listesi olarak erişilecek bir düğüm kümesidir. Belge değişikliği anlık görüntüyü geçersiz kılmaz, ancak yeniden değerlendirmenin aynı anlık görüntüyü vermeyeceği anlamına gelebilir ve anlık görüntüdeki düğümler değiştirilmiş, taşınmış veya belgeden kaldırılmış olabilir. |
| OrderedNodeSnapshot | `7` | Sonuç, orijinal belge sırasında olacak düğümlerin anlık görüntüsü listesi olarak erişilecek olan [XPath 1.0] tarafından tanımlanan bir düğüm kümesidir. Belge değişikliği anlık görüntüyü geçersiz kılmaz, ancak yeniden değerlendirmenin aynı anlık görüntüyü vermeyeceği anlamına gelebilir ve anlık görüntüdeki düğümler değiştirilmiş, taşınmış veya belgeden kaldırılmış olabilir. |
| AnyUnorderedNode | `8` | Sonuç, [XPath 1.0] tarafından tanımlanan bir düğüm kümesidir ve tek bir düğüm olarak erişilecektir, ;`hükümsüz`düğüm kümesi boşsa. Belge değişikliği, düğümü geçersiz kılmaz, ancak sonuç düğümünün artık geçerli belgeye karşılık gelmediği anlamına gelebilir. Sonuç kümesindeki herhangi bir düğümü bulunduğunda uygulama durabileceğinden bu, optimizasyona izin veren bir kolaylıktır. Gerçek sonuçta birden fazla düğüm varsa, döndürülen tek düğüm belge sıralamasında ilk olmayabilir. |
| FirstOrderedNode | `9` | Sonuç, [XPath 1.0] tarafından tanımlanan bir düğüm kümesidir ve tek bir düğüm olarak erişilecektir, ;`hükümsüz`düğüm kümesi boşsa. Belge değişikliği, düğümü geçersiz kılmaz, ancak sonuç düğümünün artık geçerli belgeye karşılık gelmediği anlamına gelebilir. Sonuç kümesinin belge sırasındaki ilk düğümü bulunduğunda uygulama durabileceğinden, bu optimizasyona izin veren bir kolaylıktır. Gerçek sonuçta birden fazla düğümü varsa, döndürülen tek düğüm belge sırasına göre ilk olacaktır. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* toplantı [Aspose.HTML](../../)


