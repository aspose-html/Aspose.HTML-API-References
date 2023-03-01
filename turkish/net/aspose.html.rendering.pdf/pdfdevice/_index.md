---
title: Class PdfDevice
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Rendering.Pdf.PdfDevice sınıf. Bir pdf belgesine dönüştürmeyi temsil eder.
type: docs
weight: 4440
url: /tr/net/aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Bir pdf belgesine dönüştürmeyi temsil eder.

```csharp
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Yeni bir örneğini başlatır.`PdfDevice` sınıf. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Yeni bir örneğini başlatır.`PdfDevice` sınıf. |
| [PdfDevice](pdfdevice/#constructor_5)(string) | Yeni bir örneğini başlatır.`PdfDevice` sınıf. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Yeni bir örneğini başlatır.`PdfDevice` oluşturma seçeneklerine ve akış sağlayıcısına göre sınıf. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Yeni bir örneğini başlatır.`PdfDevice`işleme seçeneklerine ve çıktı akışına göre sınıf. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, string) | Yeni bir örneğini başlatır.`PdfDevice` işleme seçeneklerine ve çıktı dosyası adına göre sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.pdf/pdfdevice/addrect/)(RectangleF) | Geçerli yola eksiksiz bir alt yol olarak bir dikdörtgen ekler. |
| override [BeginDocument](../../aspose.html.rendering.pdf/pdfdevice/begindocument/)(Document) | Belgenin işlenmesine başlar. |
| override [BeginElement](../../aspose.html.rendering.pdf/pdfdevice/beginelement/)(Element, RectangleF) | Öğenin işlenmesine başlar. |
| override [BeginPage](../../aspose.html.rendering.pdf/pdfdevice/beginpage/)(SizeF) | Yeni sayfanın oluşturulmasına başlar. |
| override [Clip](../../aspose.html.rendering.pdf/pdfdevice/clip/)(FillMode) | Doldurulacak bölgeyi belirlemek için FillMode kuralını kullanarak geçerli kırpma yolunu geçerli yolla kesiştirerek değiştirir. Bu yöntem geçerli yolu sonlandırır. |
| override [ClosePath](../../aspose.html.rendering.pdf/pdfdevice/closepath/)() | Mevcut noktadan alt yolun başlangıç noktasına düz bir çizgi parçası ekleyerek mevcut alt yolu kapatır. Mevcut alt yol zaten kapalıysa, "ClosePath" hiçbir şey yapmaz. Bu işleç mevcut alt yolu sonlandırır. Geçerli yola başka bir parça eklemek yeni bir alt yol başlatır, yeni bölüm "ClosePath" yöntemiyle ulaşılan bitiş noktasında başlasa bile . |
| override [CubicBezierTo](../../aspose.html.rendering.pdf/pdfdevice/cubicbezierto/)(PointF, PointF, PointF) | Geçerli yola kübik bir Bézier eğrisi ekler. Eğri, pt1 ve pt2'yi Bézier kontrol noktaları olarak kullanarak mevcut noktadan pt2, noktasına kadar uzanır. Yeni geçerli nokta pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.pdf/pdfdevice/drawimage/)(byte[], ImageType, RectangleF) | Belirtilen görüntüyü çizer. |
| override [EndDocument](../../aspose.html.rendering.pdf/pdfdevice/enddocument/)() | Belgenin işlenmesini sonlandırır. |
| override [EndElement](../../aspose.html.rendering.pdf/pdfdevice/endelement/)(Element) | Öğenin işlenmesini sonlandırır. |
| override [EndPage](../../aspose.html.rendering.pdf/pdfdevice/endpage/)() | Geçerli sayfanın görüntülenmesini sonlandırır. |
| override [Fill](../../aspose.html.rendering.pdf/pdfdevice/fill/)(FillMode) | Geçerli yolun çevrelediği tüm bölgeyi doldurur. Yol birkaç bağlantısız alt yoldan oluşuyorsa, birlikte ele alınan tüm alt yolların içini doldurur. Bu yöntem geçerli yolu sonlandırır. |
| override [FillText](../../aspose.html.rendering.pdf/pdfdevice/filltext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda doldurur. |
| override [Flush](../../aspose.html.rendering.pdf/pdfdevice/flush/)() | Tüm verileri çıkış akışına boşaltır. |
| override [LineTo](../../aspose.html.rendering.pdf/pdfdevice/lineto/)(PointF) | Geçerli noktadan noktaya (pt) bir düz çizgi parçası ekler. Yeni geçerli nokta pt. |
| override [MoveTo](../../aspose.html.rendering.pdf/pdfdevice/moveto/)(PointF) | Geçerli noktayı pt parametresinin koordinatlarına taşıyarak yeni bir alt yol başlatır, herhangi bir bağlantı çizgisi parçasını atlar. Geçerli yoldaki önceki yol oluşturma yöntemi de "MoveTo" ise, yeni "MoveTo" onu geçersiz kılar; yolda önceki "MoveTo" işleminin hiçbir izi kalmaz. |
| override [RestoreGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/restoregraphiccontext/)() | Tüm grafik bağlamını yığından çıkararak önceki değerine geri yükler. |
| override [SaveGraphicContext](../../aspose.html.rendering.pdf/pdfdevice/savegraphiccontext/)() | Tüm grafik içeriğinin bir kopyasını yığına iter. |
| override [Stroke](../../aspose.html.rendering.pdf/pdfdevice/stroke/)() | Geçerli yol boyunca bir çizgi çizer. Konturlu çizgi, yoldaki her bir düz veya kavisli parçayı takip eder, , kenarları ona paralel olan parçanın üzerinde ortalanır. Yolun alt yollarının her biri ayrı ayrı ele alınır. Bu yöntem geçerli yolu sonlandırır. |
| override [StrokeAndFill](../../aspose.html.rendering.pdf/pdfdevice/strokeandfill/)(FillMode) | Mevcut yolu konturlar ve doldurur. Bu yöntem mevcut yolu sonlandırır. |
| override [StrokeText](../../aspose.html.rendering.pdf/pdfdevice/stroketext/)(string, PointF) | Belirtilen metin dizesini belirtilen konumda okşar. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [PdfGraphicContext](pdfdevice.pdfgraphiccontext/) | PdfDevice için geçerli grafik kontrol parametrelerini tutar. Bu parametreler, grafik işleçlerinin yürüttüğü genel çerçeveyi tanımlar. |

### Ayrıca bakınız

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* ad alanı [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* toplantı [Aspose.HTML](../../)


