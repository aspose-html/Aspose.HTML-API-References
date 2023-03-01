---
title: Event.InitEvent
second_title: Aspose.HTML for .NET API リファレンス
description: Event 方法. InitEventメソッドはの値を初期化するために使用されますEvent the で作成IDocumentEventインターフェイス.
type: docs
weight: 110
url: /ja/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

`InitEvent`メソッドは、の値を初期化するために使用されます[`Event`](../) the で作成[`IDocumentEvent`](../../idocumentevent/)インターフェイス.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| type | String | イベントの種類。 |
| bubbles | Boolean | に設定した場合`真実` [泡]。 |
| cancelable | Boolean | に設定した場合`真実` 【キャンセル可能】。 |

### 備考

このメソッドは、イベントが[`DispatchEvent`](../../ieventtarget/dispatchevent/)メソッド、 ただし、必要に応じてそのフェーズ中に複数回呼び出される場合があります。 複数回呼び出された場合、最後の呼び出しが優先されます。 Event インターフェイスのサブクラスから呼び出された場合、initEvent メソッドで指定された値のみが変更され、他のすべての属性が変更されます。変更されません.

### 関連項目

* class [Event](../)
* 名前空間 [Aspose.Html.Dom.Events](../../event/)
* 組み立て [Aspose.HTML](../../../)


