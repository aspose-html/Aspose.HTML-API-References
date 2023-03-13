---
title: Class Path2D
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Canvas.Path2D sınıf. Canvas 2D APIsinin Path2D arayüzü daha sonra CanvasRenderingContext2D nesnelerinde kullanılacak yolları bildirmek için kullanılır. CanvasRenderingContext2D arabiriminin yol yöntemleri de bu arabirimde bulunur ve bir tuval üzerinde gerektiği gibi koruyabileceğiniz ve yeniden yürütebileceğiniz yolları oluşturmanıza olanak tanır.
type: docs
weight: 290
url: /tr/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Canvas 2D API'sinin Path2D arayüzü, daha sonra CanvasRenderingContext2D nesnelerinde kullanılacak yolları bildirmek için kullanılır. CanvasRenderingContext2D arabiriminin yol yöntemleri de bu arabirimde bulunur ve bir tuval üzerinde gerektiği gibi koruyabileceğiniz ve yeniden yürütebileceğiniz yolları oluşturmanıza olanak tanır.

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Path2D](path2d/#constructor)() | , yeni oluşturulmuş bir Path2D nesnesi döndürür |
| [Path2D](path2d/#constructor_1)(Path2D) | , bağımsız değişken olarak başka bir yolla yeni oluşturulmuş bir Path2D nesnesi döndürür (bir kopya oluşturur) |
| [Path2D](path2d/#constructor_2)(string) | , SVG yol verilerinden oluşan bir dizeyle yeni oluşturulmuş bir Path2D nesnesi döndürür. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Argüman tarafından verilen yolu yola ekler. |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Argüman tarafından verilen yolu yola ekler. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | StartAngle'da başlayıp endAngle'da biten r yarıçaplı (x, y) konumunda ortalanmış yola, saat yönünün tersine (varsayılanı saat yönündedir) giden bir yay ekler. |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | StartAngle'da başlayıp endAngle'da biten r yarıçaplı (x, y) konumunda ortalanmış yola, saat yönünün tersine (varsayılanı saat yönündedir) giden bir yay ekler. |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Verilen kontrol noktaları ve yarıçap ile yola bir yay ekler ve önceki noktaya düz bir çizgi ile bağlanır. |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Yola kübik bir Bézier eğrisi ekler. Üç puan gerektirir. İlk iki nokta kontrol noktalarıdır ve üçüncüsü bitiş noktasıdır. Başlangıç noktası, geçerli yoldaki son noktadır, , Bézier eğrisini oluşturmadan önce moveTo() kullanılarak değiştirilebilen. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | Kalemin ucunun mevcut alt yolun başına geri gitmesine neden olur. Geçerli noktadan başlangıca düz bir çizgi çizmeye çalışır. Şekil zaten kapalıysa veya yalnızca bir noktası varsa, bu işlev hiçbir şey yapmaz. |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | Nesneyi ortadan kaldırır. |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | StartAngle 'de başlayıp endAngle'da biten, yarıçapX ve yarıçapı ile (x, y) konumunda ortalanmış yola bir elips ekler (varsayılan olarak saat yönündedir). |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | StartAngle 'de başlayıp endAngle'da biten, yarıçapX ve yarıçapı ile (x, y) konumunda ortalanmış yola bir elips ekler (varsayılan olarak saat yönündedir). |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | Alt yoldaki son noktayı düz bir çizgiyle x, y koordinatlarına bağlar. |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | Yeni bir alt yolun başlangıç noktasını (x, y) koordinatlarına taşır. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Geçerli yola ikinci dereceden bir Bézier eğrisi ekler. |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | (x, y) konumunda, boyutu genişlik ve yükseklik tarafından belirlenen bir dikdörtgen için bir yol oluşturur. |

### Ayrıca bakınız

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* ad alanı [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* toplantı [Aspose.HTML](../../)


