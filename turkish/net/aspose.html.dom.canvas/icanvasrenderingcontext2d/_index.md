---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D arayüz. ICanvasRenderingContext2D arabirimi tuval öğesine dikdörtgenler metinler resimler ve diğer nesneleri çizmek için kullanılır. Bir tuval öğesinin çizim yüzeyi için 2B oluşturma bağlamı sağlar.
type: docs
weight: 260
url: /tr/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D arabirimi, tuval öğesine dikdörtgenler, metinler, resimler ve diğer nesneleri çizmek için kullanılır. Bir tuval öğesinin çizim yüzeyi için 2B oluşturma bağlamı sağlar.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | HTMLCanvasElement öğesine salt okunur bir geri başvuru. Bir tuval öğesiyle ilişkilendirilmemişse boş olabilir. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Şekillerin içinde kullanmak için renk veya stil. Varsayılan: (siyah). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Şekillere ve resimlere tuval üzerinde birleştirilmeden önce uygulanan alfa değeri. Varsayılan 1.0 (opak). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | globalAlpha uygulandığında bu, şekillerin ve görüntülerin mevcut bitmap üzerine nasıl çizileceğini ayarlar. Varsayılan: (kaynak üzerinden) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Görüntü yumuşatma modu; devre dışı bırakılırsa, ölçeklenirse görüntüler düzgünleştirilmez. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Bulanıklaştırma efektini belirtir. Varsayılan 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Gölgenin rengi. Varsayılan tamamen şeffaf siyah. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Gölgenin kaydırılacağı yatay mesafe. Varsayılan 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Gölgenin kaydırılacağı dikey mesafe. Varsayılan 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Şekillerin etrafındaki çizgiler için kullanılacak renk veya stil. Varsayılan: (siyah). |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Tuvale bir isabet bölgesi ekler. Bu, isabet algılamayı kolaylaştırmanıza, olayları DOM öğelerine yönlendirmenize olanak tanır, ve kullanıcıların tuvali görmeden keşfetmesine olanak tanır. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Alt yolların listesini boşaltarak yeni bir yol başlatır. Yeni bir yol oluşturmak istediğinizde bu yöntemi çağırın. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Tüm isabet alanlarını tuvalden kaldırır. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Başlangıç noktası (x, y) ve boyut (genişlik, yükseklik) tarafından tanımlanan dikdörtgendeki tüm pikselleri saydam siyaha ayarlar ve önceden çizilen içeriği siler. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Sıfır olmayan sarma sayı kuralını kullanarak, geçerli kırpma bölgesi ile yol tarafından açıklanan alanın kesişimini hesaplayarak yeni bir kırpma bölgesi oluşturur. Açık alt yollar, kırpma bölgesi hesaplanırken, gerçek alt yolları etkilemeden dolaylı olarak kapatılmalıdır. . Yeni kırpma bölgesi, geçerli kırpma bölgesinin yerini alır. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Sıfırdan farklı sarma sayısı kuralını kullanarak, geçerli kırpma bölgesi ile yolun tanımladığı alanın kesişimini hesaplayarak yeni bir kırpma bölgesi oluşturur. Kırpma bölgesi hesaplanırken, gerçek alt yolları etkilemeden açık alt yollar dolaylı olarak kapatılmalıdır. Yeni kırpma bölgesi, geçerli kırpma bölgesinin yerini alır. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Sıfırdan farklı sarma sayısı kuralını kullanarak, geçerli kırpma bölgesi ile yolun tanımladığı alanın kesişimini hesaplayarak yeni bir kırpma bölgesi oluşturur. Kırpma bölgesi hesaplanırken, gerçek alt yolları etkilemeden açık alt yollar dolaylı olarak kapatılmalıdır. Yeni kırpma bölgesi, geçerli kırpma bölgesinin yerini alır. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Belirtilen boyutlara sahip yeni, boş bir ImageData nesnesi oluşturur. Yeni nesnedeki tüm pikseller saydam siyahtır. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Belirtilen boyutlara sahip yeni, boş bir ImageData nesnesi oluşturur. Yeni nesnedeki tüm pikseller saydam siyahtır. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Parametreler tarafından temsil edilen koordinatların verdiği çizgi boyunca doğrusal bir gradyan oluşturur. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Belirtilen görüntüyü (bir CanvasImageSource) kullanarak bir desen oluşturur. Tekrarlama bağımsız değişkeni tarafından belirtilen yönlerde kaynağı tekrarlar. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Belirtilen görüntüyü (bir CanvasImageSource) kullanarak bir desen oluşturur. Tekrarlama bağımsız değişkeni tarafından belirtilen yönlerde kaynağı tekrarlar. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Parametrelerle temsil edilen iki dairenin koordinatları tarafından verilen bir radyal gradyan oluşturur. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Belirli bir öğe odaklanırsa, bu yöntem geçerli yolun etrafına bir odak halkası çizer. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Belirtilen görüntüyü çizer. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Belirtilen görüntüyü çizer. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Belirtilen görüntüyü çizer. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Belirtilen görüntüyü çizer. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Belirtilen görüntüyü çizer. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Belirtilen görüntüyü çizer. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Alt yolları geçerli dolgu stili ve varsayılan algoritma ile doldurur CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Alt yolları geçerli dolgu stiliyle doldurur. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Alt yolları geçerli dolgu stili ve varsayılan algoritma ile doldurur CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Alt yolları geçerli dolgu stiliyle doldurur. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | (x, y) konumunda, boyutu genişlik ve yükseklik tarafından belirlenen içi dolu bir dikdörtgen çizer. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Belirli bir metni verilen (x,y) konumuna çizer (doldurur). |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Belirli bir metni verilen (x,y) konumuna çizer (doldurur). |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | (sx, sy) ile başlayan ve bir sw genişliği ve sh yüksekliği olan tuval alanı için temel piksel verilerini temsil eden bir ImageData nesnesi döndürür. Bu yöntem tuval dönüştürme matrisinden etkilenmez. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Belirtilen noktanın geçerli yol içinde olup olmadığını bildirir. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Belirtilen noktanın geçerli yol içinde olup olmadığını bildirir. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Belirtilen noktanın geçerli yol içinde olup olmadığını bildirir. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Belirtilen noktanın geçerli yol içinde olup olmadığını bildirir. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Belirtilen noktanın, bir yolun çizilmesiyle kapsanan alanın içinde olup olmadığını bildirir. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Belirtilen noktanın, bir yolun çizilmesiyle kapsanan alanın içinde olup olmadığını bildirir. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Bir TextMetrics nesnesi döndürür. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Verilen ImageData nesnesindeki verileri bitmap üzerine boyar. Kirli bir dikdörtgen sağlanırsa, yalnızca o dikdörtgenin pikselleri boyanır. Bu yöntem tuval dönüştürme matrisinden etkilenmez. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Verilen ImageData nesnesindeki verileri bitmap üzerine boyar. Kirli bir dikdörtgen sağlanırsa, yalnızca o dikdörtgenin pikselleri boyanır. Bu yöntem tuval dönüştürme matrisinden etkilenmez. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Belirtilen kimliğe sahip isabet bölgesini tuvalden kaldırır. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Geçerli dönüşümü kimlik matrisiyle sıfırlar. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Çizim stili durumunu save(). tarafından kaydedilen 'durum yığınındaki' son öğeye geri yükler. |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Dönüşüm matrisine bir dönüş ekler. Açı bağımsız değişkeni, saat yönünde bir dönüş açısını temsil eder ve radyan cinsinden ifade edilir. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Mevcut çizim stili durumunu bir yığın kullanarak kaydeder, böylece restore(). kullanarak yaptığınız herhangi bir değişikliği geri alabilirsiniz. |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Tuval birimlerine x yatay ve y dikey olarak bir ölçeklendirme dönüşümü ekler. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Geçerli dönüşümü kimlik matrisine sıfırlar ve ardından aynı bağımsız değişkenlerle transform() yöntemini çağırır. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Alt yolları geçerli vuruş stiliyle vurur. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Alt yolları geçerli vuruş stiliyle vurur. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Geçerli kontur stilini kullanarak tuval üzerine (x, y)'de bir başlangıç noktasına ve aw genişliğe ve h yüksekliğe sahip bir dikdörtgen çizer. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Belirli bir metni verilen (x, y) konumunda çizer (vurur). |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Belirli bir metni verilen (x, y) konumunda çizer (vurur). |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Geçerli dönüşüm matrisini bağımsız değişkenleriyle açıklanan matrisle çarpar. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Tuvali ve orijinini ızgara üzerinde x yatay ve y dikey olarak hareket ettirerek bir çeviri dönüşümü ekler. |

### Ayrıca bakınız

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* ad alanı [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* toplantı [Aspose.HTML](../../)


