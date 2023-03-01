---
title: Interface IEventTarget
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Events.IEventTarget インターフェース. EventTargetインターフェイスはDOM イベント モデルをサポートする実装ですべてのノードによって実装されます したがってこのインターフェイスはNode インターフェイスのインスタンスでバインディング固有のキャスト メソッドを使用して取得できます インターフェイスによりイベント リスナーの登録と削除が可能になりますをEventTargetそれにイベントをディスパッチするIEventTarget.
type: docs
weight: 810
url: /ja/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

[`EventTarget`](../../aspose.html.dom/eventtarget/)インターフェイスは、DOM イベント モデルをサポートする実装ですべてのノードによって実装されます。 したがって、このインターフェイスは、Node インターフェイスのインスタンスでバインディング固有のキャスト メソッドを使用して取得できます。 インターフェイスにより、イベント リスナーの登録と削除が可能になります。を[`EventTarget`](../../aspose.html.dom/eventtarget/)それにイベントをディスパッチする`IEventTarget`.

```csharp
public interface IEventTarget
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | このメソッドにより、イベントを実装イベント モデルにディスパッチできます。 |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../ieventlistener/)から削除されます[`EventTarget`](../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../ieventlistener/)から削除されます[`EventTarget`](../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません. |

### 関連項目

* 名前空間 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 組み立て [Aspose.HTML](../../)


