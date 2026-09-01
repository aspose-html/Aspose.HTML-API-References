---
title: "ImageDevice 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.rendering.image.ImageDevice 클래스. jpeg png bmp gif tiff 래스터 형식으로의 렌더링을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

래스터 형식인 jpeg, png, bmp, gif, tiff에 대한 렌더링을 나타냅니다.

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | 새 `ImageDevice` 클래스 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | 새 `ImageDevice` 클래스 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_5)(String) | 새 `ImageDevice` 클래스 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | 렌더링 옵션과 스트림 공급자를 사용하여 `ImageDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | 렌더링 옵션과 출력 스트림을 사용하여 `ImageDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | 렌더링 옵션과 출력 파일 이름을 사용하여 `ImageDevice` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) |  |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) |  |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() |  |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) |  |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() |  |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) |  |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) |  |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() |  |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) |  |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) |  |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() |  |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) |  |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | `ImageDevice`에 대한 현재 그래픽 제어 매개변수를 보유합니다. 이러한 매개변수는 그래픽 연산자가 실행되는 전역 프레임워크를 정의합니다. |

### 또 보기

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
