---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML for .NET API リファレンス
description: IEventTarget 方法. このメソッドを使用するとイベント ターゲットにイベント リスナーを登録できます
type: docs
weight: 10
url: /ja/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| type | String | ユーザーが登録しているイベントの種類 |
| listener | IEventListener | イベントが発生したときに呼び出されるメソッドを含む、ユーザーによって実装されたインターフェイスを取ります。 |

### 備考

[`IEventListener`](../../ieventlistener/)に追加されます[`EventTarget`](../../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガー されませんが、バブリング フェーズなど、イベント フローの後の段階でトリガーされる場合があります.

同じイベントリスナーが複数登録されている場合[`EventTarget`](../../../aspose.html.dom/eventtarget/)同じパラメーターを使用すると、重複するインスタンスは破棄されます. それらは、[`IEventListener`](../../ieventlistener/)これらは破棄されるため、the で削除する必要はありません。[`RemoveEventListener`](../removeeventlistener/) メソッド.

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 名前空間 [Aspose.Html.Dom.Events](../../ieventtarget/)
* 組み立て [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| type | String | ユーザーが登録しているイベントの種類 |
| listener | IEventListener | イベントが発生したときに呼び出されるメソッドを含む、ユーザーによって実装されたインターフェイスを取ります。 |
| useCapture | Boolean | true の場合、useCapture は、ユーザーがキャプチャを開始したいことを示します。 キャプチャを開始した後、指定されたタイプのすべてのイベントが registered にディスパッチされます[`IEventListener`](../../ieventlistener/) は、ツリー内でその下にあるイベント ターゲットにディスパッチされる前に発生します。[`IEventListener`](../../ieventlistener/)キャプチャを使用するように指定されています。 |

### 備考

[`IEventListener`](../../ieventlistener/)に追加されます[`EventTarget`](../../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガー されませんが、バブリング フェーズなど、イベント フローの後の段階でトリガーされる場合があります.

同じイベントリスナーが複数登録されている場合[`EventTarget`](../../../aspose.html.dom/eventtarget/)同じパラメーターを使用すると、重複するインスタンスは破棄されます. それらは、[`IEventListener`](../../ieventlistener/)これらは破棄されるため、the で削除する必要はありません。[`RemoveEventListener`](../removeeventlistener/) メソッド.

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 名前空間 [Aspose.Html.Dom.Events](../../ieventtarget/)
* 組み立て [Aspose.HTML](../../../)


