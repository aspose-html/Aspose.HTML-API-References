---
title: IEventTarget.DispatchEvent
second_title: Aspose.HTML for .NET API リファレンス
description: IEventTarget 方法. このメソッドによりイベントを実装イベント モデルにディスパッチできます
type: docs
weight: 20
url: /ja/net/aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

このメソッドにより、イベントを実装イベント モデルにディスパッチできます。

```csharp
public bool DispatchEvent(Event @event)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| event | Event | イベントの処理に使用するイベントの種類、動作、およびコンテキスト情報を指定します。 |

### 戻り値

の戻り値[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/)呼び出されたイベントを処理したリスナーのいずれかが呼び出されたかどうかを示します[`PreventDefault`](../../event/preventdefault/). の場合[`PreventDefault`](../../event/preventdefault/)呼び出された場合、値は false です。それ以外の場合、値は true. です。

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) |  |

### 備考

この方法でディスパッチされたイベントは、実装によって直接ディスパッチされたイベントと同じキャプチャおよびバブリング動作を行います。 イベントのターゲットは、[`EventTarget`](../../../aspose.html.dom/eventtarget/)どの上で[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/)と呼ばれます.

### 関連項目

* class [Event](../../event/)
* interface [IEventTarget](../)
* 名前空間 [Aspose.Html.Dom.Events](../../ieventtarget/)
* 組み立て [Aspose.HTML](../../../)


