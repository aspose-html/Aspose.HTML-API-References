---
title: Interface IEventListener
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Events.IEventListener インターフェース. IEventListenerインターフェイスはイベントを処理するための主要な方法です ユーザーはIEventListenerインターフェイスにリスナーを登録しますEventTargetを使用してAddEventListenermethod. ユーザーも削除する必要がありますIEventListenerそのからEventTargetlistener. の使用が完了した後
type: docs
weight: 800
url: /ja/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

`IEventListener`インターフェイスは、イベントを処理するための主要な方法です。 ユーザーは、`IEventListener`インターフェイスにリスナーを登録します[`EventTarget`](../../aspose.html.dom/eventtarget/)を使用して[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/)method. ユーザーも削除する必要があります`IEventListener`そのから[`EventTarget`](../../aspose.html.dom/eventtarget/)listener. の使用が完了した後

```csharp
public interface IEventListener
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | このメソッドは、そのタイプのイベントが発生するたびに呼び出されます。`IEventListener`インターフェイスが登録されました. |

### 備考

cloneNode メソッドを使用してノードをコピーすると、ソース ノードにアタッチされたイベント リスナーは、コピーされたノードにアタッチされません。

### 関連項目

* 名前空間 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 組み立て [Aspose.HTML](../../)


