---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions sınıf. Uygulamaya özel işleme cihazları için temel sınıfı temsil eder.
type: docs
weight: 4140
url: /tr/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Uygulamaya özel işleme cihazları için temel sınıfı temsil eder.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parametre | Tanım |
| --- | --- |
| TGraphicContext | Geçerli grafik kontrol parametrelerini tutan grafik bağlamı |
| TRenderingOptions | Oluşturma seçenekleri |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | Grafik bağlamını alır |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | Oluşturma seçeneklerini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | Geçerli yola eksiksiz bir alt yol olarak bir dikdörtgen ekler. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | Belgenin işlenmesine başlar. |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Düğümün oluşturulmasına başlar. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | Yeni sayfanın oluşturulmasına başlar. |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | Doldurulacak bölgeyi belirlemek için FillMode kuralını kullanarak geçerli kırpma yolunu geçerli yolla kesiştirerek değiştirir. Bu yöntem geçerli yolu sonlandırır. |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | Mevcut noktadan alt yolun başlangıç noktasına düz bir çizgi parçası ekleyerek mevcut alt yolu kapatır. Mevcut alt yol zaten kapalıysa, "ClosePath" hiçbir şey yapmaz. Bu işleç mevcut alt yolu sonlandırır. Geçerli yola başka bir parça eklemek yeni bir alt yol başlatır, yeni bölüm "ClosePath" yöntemiyle ulaşılan bitiş noktasında başlasa bile . |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Geçerli yola kübik bir Bézier eğrisi ekler. Eğri, pt1 ve pt2'yi Bézier kontrol noktaları olarak kullanarak mevcut noktadan pt2, noktasına kadar uzanır. Yeni geçerli nokta pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | Belirtilen görüntüyü çizer. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | Belgenin işlenmesini sonlandırır. |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | Düğümün işlenmesini sonlandırır. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | Geçerli sayfanın görüntülenmesini sonlandırır. |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | Geçerli yolun çevrelediği tüm bölgeyi doldurur. Yol birkaç bağlantısız alt yoldan oluşuyorsa, birlikte ele alınan tüm alt yolların içini doldurur. Bu yöntem geçerli yolu sonlandırır. |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda doldurur. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | Tüm verileri çıkış akışına boşaltır. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | Geçerli noktadan noktaya (pt) bir düz çizgi parçası ekler. Yeni geçerli nokta pt. |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | Geçerli noktayı pt parametresinin koordinatlarına taşıyarak yeni bir alt yol başlatır, herhangi bir bağlantı çizgisi parçasını atlar. Geçerli yoldaki önceki yol oluşturma yöntemi de "MoveTo" ise, yeni "MoveTo" onu geçersiz kılar; yolda önceki "MoveTo" işleminin hiçbir izi kalmaz. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | Tüm grafik bağlamını yığından çıkararak önceki değerine geri yükler. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | Tüm grafik içeriğinin bir kopyasını yığına iter. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | Geçerli yol boyunca bir çizgi çizer. Konturlu çizgi, yoldaki her bir düz veya kavisli parçayı takip eder, , kenarları ona paralel olan parçanın üzerinde ortalanır. Yolun alt yollarının her biri ayrı ayrı ele alınır. Bu yöntem geçerli yolu sonlandırır. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | Mevcut yolu konturlar ve doldurur. Bu yöntem mevcut yolu sonlandırır. |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda okşar. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | Aygıtlar için yapılandırma nesnesini temsil eder. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | Sayfaları çıktı akışı\akışlarına yazmak için strateji türlerini belirtir. |

### Ayrıca bakınız

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* ad alanı [Aspose.Html.Rendering](../../aspose.html.rendering/)
* toplantı [Aspose.HTML](../../)


