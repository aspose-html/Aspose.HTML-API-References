---
title: Class DocDevice
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Rendering.Doc.DocDevice sınıf. Bir DOCX belgesine dönüştürmeyi temsil eder.
type: docs
weight: 4170
url: /tr/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Bir DOCX belgesine dönüştürmeyi temsil eder.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Yeni bir örneğini başlatır.`DocDevice` sınıf. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Yeni bir örneğini başlatır.`DocDevice` çıktı akışına göre sınıf. |
| [DocDevice](docdevice/#constructor_5)(string) | Yeni bir örneğini başlatır.`DocDevice` çıktı dosyası adına göre sınıf. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Yeni bir örneğini başlatır.`DocDevice` oluşturma seçeneklerine ve akış sağlayıcısına göre sınıf. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Yeni bir örneğini başlatır.`DocDevice` işleme seçenekleri ve çıkış akışı ile sınıf. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | Yeni bir örneğini başlatır.`DocDevice` işleme seçeneklerine ve çıktı dosyası adına göre sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Geçerli yola eksiksiz bir alt yol olarak bir dikdörtgen ekler. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Belgenin işlenmesine başlar. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Html düğümünün işlenmesine başlar. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Yeni sayfanın oluşturulmasına başlar. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Doldurulacak bölgeyi belirlemek için FillMode kuralını kullanarak geçerli kırpma yolunu geçerli yolla kesiştirerek değiştirir. Bu yöntem geçerli yolu sonlandırır. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | Mevcut noktadan alt yolun başlangıç noktasına düz bir çizgi parçası ekleyerek mevcut alt yolu kapatır. Mevcut alt yol zaten kapalıysa, "ClosePath" hiçbir şey yapmaz. Bu işleç mevcut alt yolu sonlandırır. Geçerli yola başka bir parça eklemek yeni bir alt yol başlatır, yeni bölüm "ClosePath" yöntemiyle ulaşılan bitiş noktasında başlasa bile . |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Geçerli yola kübik bir Bézier eğrisi ekler. Eğri, pt1 ve pt2'yi Bézier kontrol noktaları olarak kullanarak mevcut noktadan pt2, noktasına kadar uzanır. Yeni geçerli nokta pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Belirtilen görüntüyü çizer. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | HTML düğümünün işlenmesini sonlandırır. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | Geçerli sayfanın görüntülenmesini sonlandırır. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Geçerli yolun çevrelediği tüm bölgeyi doldurur. Yol birkaç bağlantısız alt yoldan oluşuyorsa, birlikte ele alınan tüm alt yolların içini doldurur. Bu yöntem geçerli yolu sonlandırır. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda doldurur. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | Tüm verileri çıkış akışına boşaltır. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Geçerli noktadan noktaya (pt) bir düz çizgi parçası ekler. Yeni geçerli nokta pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Geçerli noktayı pt parametresinin koordinatlarına taşıyarak yeni bir alt yol başlatır, herhangi bir bağlantı çizgisi parçasını atlar. Geçerli yoldaki önceki yol oluşturma yöntemi de "MoveTo" ise, yeni "MoveTo" onu geçersiz kılar; yolda önceki "MoveTo" işleminin hiçbir izi kalmaz. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Tüm grafik bağlamını yığından çıkararak önceki değerine geri yükler. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Tüm grafik içeriğinin bir kopyasını yığına iter. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | Geçerli yol boyunca bir çizgi çizer. Konturlu çizgi, yoldaki her bir düz veya kavisli parçayı takip eder, , kenarları ona paralel olan parçanın üzerinde ortalanır. Yolun alt yollarının her biri ayrı ayrı ele alınır. Bu yöntem geçerli yolu sonlandırır. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Mevcut yolu konturlar ve doldurur. Bu yöntem mevcut yolu sonlandırır. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda okşar. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | DocDevice için geçerli grafik kontrol parametrelerini tutar. Bu parametreler, grafik işleçlerinin yürüttüğü genel çerçeveyi tanımlar. |

### Ayrıca bakınız

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* ad alanı [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* toplantı [Aspose.HTML](../../)


