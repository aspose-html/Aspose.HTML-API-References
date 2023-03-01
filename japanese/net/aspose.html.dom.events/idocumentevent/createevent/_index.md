---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML for .NET API リファレンス
description: IDocumentEvent 方法. を作成しますEvent実装でサポートされているタイプの.
type: docs
weight: 10
url: /ja/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

を作成します[`Event`](../../event/)実装でサポートされているタイプの.

```csharp
public Event CreateEvent(string eventType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| eventType | String | eventType パラメータは、[`Event`](../../event/)作成するインターフェイス. [`Event`](../../event/)指定されたインターフェイスは実装によってサポートされています。このメソッドは new を返します[`Event`](../../event/)要求されたインターフェイス タイプの. [`Event`](../../event/)経由で発送されます[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/)適切な メソッド[`InitEvent`](../../event/initevent/)メソッドは、作成後に初期化するために呼び出す必要があります。[`Event`](../../event/) s values. |

### 戻り値

新しく作成された[`Event`](../../event/)

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 実装が型をサポートしていない場合に発生します[`Event`](../../event/)インターフェイス要求 |

### 関連項目

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* 名前空間 [Aspose.Html.Dom.Events](../../idocumentevent/)
* 組み立て [Aspose.HTML](../../../)


