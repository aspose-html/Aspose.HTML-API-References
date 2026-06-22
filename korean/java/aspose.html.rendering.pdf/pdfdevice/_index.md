---
title: "PdfDevice 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.rendering.pdf.PdfDevice 클래스. PDF 문서에 대한 렌더링을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

PDF 문서로의 렌더링을 나타냅니다.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | `PdfDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | `PdfDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | `PdfDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | 렌더링 옵션 및 스트림 제공자를 사용하여 `PdfDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | 렌더링 옵션 및 출력 스트림을 사용하여 `PdfDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | 렌더링 옵션 및 출력 파일 이름을 사용하여 `PdfDevice` 클래스의 새 인스턴스를 초기화합니다. |

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
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | PdfDevice에 대한 현재 그래픽 제어 매개변수를 보유합니다. 이 매개변수들은 그래픽 연산자가 실행되는 전역 프레임워크를 정의합니다. |

### 또 보기

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
