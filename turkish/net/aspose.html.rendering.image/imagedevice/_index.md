---
title: Class ImageDevice
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Rendering.Image.ImageDevice sınıf. Tarama biçimlerine dönüştürmeyi temsil eder jpeg png bmp gif tiff.
type: docs
weight: 4300
url: /tr/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Tarama biçimlerine dönüştürmeyi temsil eder: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Yeni bir örneğini başlatır.`ImageDevice` sınıf. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Yeni bir örneğini başlatır.`ImageDevice` sınıf. |
| [ImageDevice](imagedevice/#constructor_5)(string) | Yeni bir örneğini başlatır.`ImageDevice` sınıf. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Yeni bir örneğini başlatır.`ImageDevice` oluşturma seçeneklerine ve akış sağlayıcısına göre sınıf. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Yeni bir örneğini başlatır.`ImageDevice`işleme seçeneklerine ve çıktı akışına göre sınıf. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | Yeni bir örneğini başlatır.`ImageDevice` işleme seçeneklerine ve çıktı dosyası adına göre sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Graphics. örneğini alır |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | Geçerli yola eksiksiz bir alt yol olarak bir dikdörtgen ekler. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | Belgenin işlenmesine başlar. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | Öğenin işlenmesine başlar. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | Yeni sayfanın oluşturulmasına başlar. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | Doldurulacak bölgeyi belirlemek için FillMode kuralını kullanarak geçerli kırpma yolunu geçerli yolla kesiştirerek değiştirir. Bu yöntem geçerli yolu sonlandırır. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | Mevcut noktadan alt yolun başlangıç noktasına düz bir çizgi parçası ekleyerek mevcut alt yolu kapatır. Mevcut alt yol zaten kapalıysa, "ClosePath" hiçbir şey yapmaz. Bu işleç mevcut alt yolu sonlandırır. Geçerli yola başka bir parça eklemek yeni bir alt yol başlatır, yeni bölüm "ClosePath" yöntemiyle ulaşılan bitiş noktasında başlasa bile . |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | Geçerli yola kübik bir Bézier eğrisi ekler. Eğri, pt1 ve pt2'yi Bézier kontrol noktaları olarak kullanarak mevcut noktadan pt2, noktasına kadar uzanır. Yeni geçerli nokta pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | Belirtilen görüntüyü çizer. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | Belgenin işlenmesini sonlandırır. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | Öğenin işlenmesini sonlandırır. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | Geçerli sayfanın görüntülenmesini sonlandırır. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | Geçerli yolun çevrelediği tüm bölgeyi doldurur. Yol birkaç bağlantısız alt yoldan oluşuyorsa, birlikte ele alınan tüm alt yolların içini doldurur. Bu yöntem geçerli yolu sonlandırır. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda doldurur. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | Tüm verileri çıkış akışına boşaltır. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | Geçerli noktadan noktaya (pt) bir düz çizgi parçası ekler. Yeni geçerli nokta pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | Geçerli noktayı pt parametresinin koordinatlarına taşıyarak yeni bir alt yol başlatır, herhangi bir bağlantı çizgisi parçasını atlar. Geçerli yoldaki önceki yol oluşturma yöntemi de "MoveTo" ise, yeni "MoveTo" onu geçersiz kılar; yolda önceki "MoveTo" işleminin hiçbir izi kalmaz. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | Tüm grafik bağlamını yığından çıkararak önceki değerine geri yükler. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | Tüm grafik içeriğinin bir kopyasını yığına iter. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | Geçerli yol boyunca bir çizgi çizer. Konturlu çizgi, yoldaki her bir düz veya kavisli parçayı takip eder, , kenarları ona paralel olan parçanın üzerinde ortalanır. Yolun alt yollarının her biri ayrı ayrı ele alınır. Bu yöntem geçerli yolu sonlandırır. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | Mevcut yolu konturlar ve doldurur. Bu yöntem mevcut yolu sonlandırır. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda okşar. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | için geçerli grafik kontrol parametrelerini tutar.`ImageDevice` . Bu parametreler, grafik işleçlerinin yürüttüğü genel çerçeveyi tanımlar. |

### Ayrıca bakınız

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* ad alanı [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* toplantı [Aspose.HTML](../../)


