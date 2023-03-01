---
title: Aspose.Html.Dom.Events
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Events名前空間はオブジェクト for DOM の更新に関連するすべてのイベントを提供しますイベントに関連付けられた 固有のコンテキスト情報observation へのサブスクリプションとカスタムイベントの構築が含まれます.
type: docs
weight: 80
url: /ja/net/aspose.html.dom.events/
---
**Aspose.Html.Dom.Events**名前空間は、オブジェクト for DOM の更新に関連するすべてのイベントを提供します。イベントに関連付けられた 固有のコンテキスト情報observation へのサブスクリプションと、カスタムイベントの構築が含まれます.

## クラス

| クラス | 説明 |
| --- | --- |
| [CustomEvent](./customevent/) | CustomEvent インターフェイスを使用するイベントは、カスタム データを運ぶために使用できます。 |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | [`DocumentLoadErrorEvent`](../aspose.html.dom.events/documentloaderrorevent/)要求されたリソースが利用できない場合に発生します. |
| [DOMEventHandler](./domeventhandler/) | イベント処理のコールバックを表します。 |
| [ErrorEvent](./errorevent/) | [`ErrorEvent`](../aspose.html.dom.events/errorevent/)実行時に発生したエラーに関するコンテキスト情報を提供します. |
| [Event](./event/) | [`Event`](../aspose.html.dom.events/event/)イベントに関するコンテキスト情報を、イベントを処理するハンドラーに提供するために使用されます。 |
| [FocusEvent](./focusevent/) | FocusEvent インターフェイスは、Focus イベントに関連する特定のコンテキスト情報を提供します。 |
| [InputEvent](./inputevent/) | 入力イベントは、DOM が更新されるたびに通知として送信されます。 |
| [KeyboardEvent](./keyboardevent/) | KeyboardEvent インターフェイスは、キーボード デバイスに関連付けられた特定のコンテキスト情報を提供します。各キーボード イベントは、値を使用してキーを参照します。キーボード イベントは通常、フォーカスのある要素に向けられます。 |
| [MouseEvent](./mouseevent/) | MouseEvent インターフェイスは、マウス イベントに関連する特定のコンテキスト情報を提供します。 |
| [UIEvent](./uievent/) | UIEvent インターフェイスは、ユーザー インターフェイス イベントに関連する特定のコンテキスト情報を提供します。 |
| [WheelEvent](./wheelevent/) | WheelEvent インターフェイスは、ホイール イベントに関連する特定のコンテキスト情報を提供します。 WheelEvent インターフェイスのインスタンスを作成するには、WheelEvent コンストラクターを使用して、オプションの WheelEventInit 辞書を渡します。 |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | [`IDocumentEvent`](../aspose.html.dom.events/idocumentevent/)インターフェイスは、ユーザーが作成できるメカニズムを提供します[`Event`](../aspose.html.dom.events/event/)実装でサポートされているタイプの. |
| [IEventListener](./ieventlistener/) | [`IEventListener`](../aspose.html.dom.events/ieventlistener/)インターフェイスは、イベントを処理するための主要な方法です。 ユーザーは、[`IEventListener`](../aspose.html.dom.events/ieventlistener/)インターフェイスにリスナーを登録します[`EventTarget`](../aspose.html.dom/eventtarget/)を使用して[`AddEventListener`](../aspose.html.dom/eventtarget/addeventlistener/)method. ユーザーも削除する必要があります[`IEventListener`](../aspose.html.dom.events/ieventlistener/)そのから[`EventTarget`](../aspose.html.dom/eventtarget/)listener. の使用が完了した後 |
| [IEventTarget](./ieventtarget/) | [`EventTarget`](../aspose.html.dom/eventtarget/)インターフェイスは、DOM イベント モデルをサポートする実装ですべてのノードによって実装されます。 したがって、このインターフェイスは、Node インターフェイスのインスタンスでバインディング固有のキャスト メソッドを使用して取得できます。 インターフェイスにより、イベント リスナーの登録と削除が可能になります。を[`EventTarget`](../aspose.html.dom/eventtarget/)それにイベントをディスパッチする[`IEventTarget`](../aspose.html.dom.events/ieventtarget/). |


