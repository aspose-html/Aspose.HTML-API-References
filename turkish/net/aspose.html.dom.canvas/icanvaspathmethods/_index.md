---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods arayüz. ICanvasPathMethods arabirimi nesnelerin yollarını değiştirmek için kullanılır.
type: docs
weight: 240
url: /tr/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods arabirimi, nesnelerin yollarını değiştirmek için kullanılır.

```csharp
public interface ICanvasPathMethods
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | StartAngle'da başlayıp endAngle'da biten r yarıçaplı (x, y) konumunda ortalanmış yola, saat yönünün tersine (varsayılanı saat yönündedir) giden bir yay ekler. |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | StartAngle'da başlayıp endAngle'da biten r yarıçaplı (x, y) konumunda ortalanmış yola, saat yönünün tersine (varsayılanı saat yönündedir) giden bir yay ekler. |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Verilen kontrol noktaları ve yarıçap ile yola bir yay ekler ve önceki noktaya düz bir çizgi ile bağlanır. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Yola kübik bir Bézier eğrisi ekler. Üç puan gerektirir. İlk iki nokta kontrol noktalarıdır ve üçüncüsü bitiş noktasıdır. Başlangıç noktası, geçerli yoldaki son noktadır, , Bézier eğrisini oluşturmadan önce moveTo() kullanılarak değiştirilebilen. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Kalemin ucunun mevcut alt yolun başına geri gitmesine neden olur. Geçerli noktadan başlangıca düz bir çizgi çizmeye çalışır. Şekil zaten kapalıysa veya yalnızca bir noktası varsa, bu işlev hiçbir şey yapmaz. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | StartAngle 'de başlayıp endAngle'da biten, yarıçapX ve yarıçapı ile (x, y) konumunda ortalanmış yola bir elips ekler (varsayılan olarak saat yönündedir). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | StartAngle 'de başlayıp endAngle'da biten, yarıçapX ve yarıçapı ile (x, y) konumunda ortalanmış yola bir elips ekler (varsayılan olarak saat yönündedir). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Alt yoldaki son noktayı düz bir çizgiyle x, y koordinatlarına bağlar. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Yeni bir alt yolun başlangıç noktasını (x, y) koordinatlarına taşır. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Geçerli yola ikinci dereceden bir Bézier eğrisi ekler. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | (x, y) konumunda, boyutu genişlik ve yükseklik tarafından belirlenen bir dikdörtgen için bir yol oluşturur. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* toplantı [Aspose.HTML](../../)


