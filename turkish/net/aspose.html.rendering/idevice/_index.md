---
title: Interface IDevice
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Rendering.IDevice arayüz. Yollar metin ve resimler gibi grafik öğelerinin özel olarak oluşturulmasını destekleyen yöntemleri ve özellikleri tanımlar.
type: docs
weight: 4280
url: /tr/net/aspose.html.rendering/idevice/
---
## IDevice interface

Yollar, metin ve resimler gibi grafik öğelerinin özel olarak oluşturulmasını destekleyen yöntemleri ve özellikleri tanımlar.

```csharp
public interface IDevice : IDisposable
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | Grafik bağlamını alır. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | Oluşturma seçeneklerini alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | Geçerli yola eksiksiz bir alt yol olarak bir dikdörtgen ekler. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | Belgenin işlenmesine başlar. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Öğenin işlenmesine başlar. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | Yeni sayfanın oluşturulmasına başlar. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | Doldurulacak bölgeyi belirlemek için FillMode kuralını kullanarak geçerli kırpma yolunu geçerli yolla kesiştirerek değiştirir. Bu yöntem geçerli yolu sonlandırır. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | Mevcut noktadan alt yolun başlangıç noktasına düz bir çizgi parçası ekleyerek mevcut alt yolu kapatır. Mevcut alt yol zaten kapalıysa, "ClosePath" hiçbir şey yapmaz. Bu işleç mevcut alt yolu sonlandırır. Geçerli yola başka bir parça eklemek yeni bir alt yol başlatır, yeni bölüm "ClosePath" yöntemiyle ulaşılan bitiş noktasında başlasa bile . |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Geçerli yola kübik bir Bézier eğrisi ekler. Eğri, pt1 ve pt2'yi Bézier kontrol noktaları olarak kullanarak mevcut noktadan pt3, noktasına kadar uzanır. Yeni geçerli nokta pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | Belirtilen görüntüyü çizer. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | Belgenin işlenmesini sonlandırır. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | Öğenin işlenmesini sonlandırır. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | Geçerli sayfanın görüntülenmesini sonlandırır. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | Geçerli yolun çevrelediği tüm bölgeyi doldurur. Yol birkaç bağlantısız alt yoldan oluşuyorsa, birlikte ele alınan tüm alt yolların içini doldurur. Bu yöntem geçerli yolu sonlandırır. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda doldurur. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | Tüm verileri çıkış akışına boşaltır. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | Geçerli noktadan noktaya (pt) bir düz çizgi parçası ekler. Yeni geçerli nokta pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | Geçerli noktayı pt parametresinin koordinatlarına taşıyarak yeni bir alt yol başlatır, herhangi bir bağlantı çizgisi parçasını atlar. Geçerli yoldaki önceki yol oluşturma yöntemi de "MoveTo" ise, yeni "MoveTo" onu geçersiz kılar; yolda önceki "MoveTo" işleminin hiçbir izi kalmaz. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | Tüm grafik bağlamını yığından çıkararak önceki değerine geri yükler. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | Tüm grafik içeriğinin bir kopyasını yığına iter. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | Geçerli yol boyunca bir çizgi çizer. Konturlu çizgi, yoldaki her bir düz veya kavisli parçayı takip eder, , kenarları ona paralel olan parçanın üzerinde ortalanır. Yolun alt yollarının her biri ayrı ayrı ele alınır. Bu yöntem geçerli yolu sonlandırır. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | Mevcut yolu konturlar ve doldurur. Bu yöntem mevcut yolu sonlandırır. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda okşar. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Rendering](../../aspose.html.rendering/)
* toplantı [Aspose.HTML](../../)


