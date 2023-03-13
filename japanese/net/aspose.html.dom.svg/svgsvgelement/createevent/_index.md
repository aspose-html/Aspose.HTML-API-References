---
title: SVGSVGElement.CreateEvent
second_title: Aspose.HTML for .NET API リファレンス
description: SVGSVGElement 方法. を作成しますEvent実装でサポートされているタイプの.
type: docs
weight: 110
url: /ja/net/aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

を作成します[`Event`](../../../aspose.html.dom.events/event/)実装でサポートされているタイプの.

```csharp
public Event CreateEvent(string eventType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| eventType | String | eventType パラメータは、[`Event`](../../../aspose.html.dom.events/event/)作成するインターフェイス. [`Event`](../../../aspose.html.dom.events/event/)指定されたインターフェイスは実装によってサポートされています。このメソッドは new を返します[`Event`](../../../aspose.html.dom.events/event/)要求されたインターフェイス タイプの. [`Event`](../../../aspose.html.dom.events/event/)経由で発送されます[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/)適切な メソッド[`InitEvent`](../../../aspose.html.dom.events/event/initevent/)メソッドは、作成後に初期化するために呼び出す必要があります。[`Event`](../../../aspose.html.dom.events/event/) s values. |

### 戻り値

新しく作成された[`Event`](../../../aspose.html.dom.events/event/)

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 実装が型をサポートしていない場合に発生します[`Event`](../../../aspose.html.dom.events/event/)インターフェイス要求 |

### 関連項目

* class [Event](../../../aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* 名前空間 [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* 組み立て [Aspose.HTML](../../../)


