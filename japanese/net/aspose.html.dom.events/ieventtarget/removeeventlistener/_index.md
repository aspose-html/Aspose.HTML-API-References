---
title: IEventTarget.RemoveEventListener
second_title: Aspose.HTML for .NET API リファレンス
description: IEventTarget 方法. このメソッドを使用するとイベント ターゲットからイベント リスナーを削除できますIEventListenerから削除されますEventTargetイベントの処理中は現在のアクションによってトリガーされません. イベントリスナーは削除された後は呼び出されません.
type: docs
weight: 30
url: /ja/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../../ieventlistener/)から削除されます[`EventTarget`](../../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| type | String | のイベント タイプを指定します。[`IEventListener`](../../ieventlistener/)削除されています。 |
| listener | IEventListener | の[`IEventListener`](../../ieventlistener/)パラメータは[`IEventListener`](../../ieventlistener/)削除する必要があります。 |

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 名前空間 [Aspose.Html.Dom.Events](../../ieventtarget/)
* 組み立て [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../../ieventlistener/)から削除されます[`EventTarget`](../../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| type | String | のイベント タイプを指定します。[`IEventListener`](../../ieventlistener/)削除されています。 |
| listener | IEventListener | の[`IEventListener`](../../ieventlistener/)パラメータは[`IEventListener`](../../ieventlistener/)削除する必要があります。 |
| useCapture | Boolean | 削除される EventListener がキャプチャー リスナーとして登録されているかどうかを指定します。 リスナーが 2 回登録された場合 (1 つはキャプチャーあり、もう 1 つはキャプチャーなし)、それぞれを個別に削除する必要があります。 キャプチャー リスナーの削除は、非キャプチャー バージョンには影響しません。同じリスナーの、およびその逆。 |

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* 名前空間 [Aspose.Html.Dom.Events](../../ieventtarget/)
* 組み立て [Aspose.HTML](../../../)


