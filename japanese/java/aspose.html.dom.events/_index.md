---
title: "com.aspose.html.dom.events"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events パッケージは、DOM 更新に関連するすべてのイベント用オブジェクトを提供します。イベントに関連する特定のコンテキスト情報の観測へのサブスクリプションやカスタムイベントの構築を含みます。"
type: docs

url: /ja/java/com.aspose.html.dom.events/
---
The **com.aspose.html.dom.events** パッケージは、DOM 更新に関連するあらゆるイベントのオブジェクトを提供します。イベントに関連する特定のコンテキスト情報の観測へのサブスクリプションや、カスタムイベントの構築も含まれます。

## クラス

| クラス | 説明 |
| --- | --- |
| [CustomEvent](./customevent/) | CustomEvent インターフェイスを使用したイベントは、カスタムデータを運ぶために使用できます。 |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | 要求されたリソースが利用できない場合に DocumentLoadErrorEvent が発生します。 |
| [DOMEventHandler](./domeventhandler/) | Document Object Model (DOM) イベント処理のための汎用コールバックデリゲートを表します。 |
| [ErrorEvent](./errorevent/) | ErrorEvent は、実行時に発生したエラーに関するコンテキスト情報を提供します。 |
| [Event](./event/) | これは、イベントを処理するハンドラに対して、イベントに関するコンテキスト情報を提供するために使用されます。 |
| [FocusEvent](./focusevent/) | FocusEvent インターフェイスは、フォーカスイベントに関連する特定のコンテキスト情報を提供します。 |
| [InputEvent](./inputevent/) | DOM が更新されるたびに、入力イベントが通知として送信されます。 |
| [KeyboardEvent](./keyboardevent/) | KeyboardEvent インターフェイスは、キーボードデバイスに関連する特定のコンテキスト情報を提供します。各キーボードイベントは、値を使用してキーを参照します。キーボードイベントは、通常、フォーカスがある要素に対して送信されます。 |
| [MouseEvent](./mouseevent/) | MouseEvent インターフェイスは、マウスイベントに関連する特定のコンテキスト情報を提供します。 |
| [UIEvent](./uievent/) | UIEvent インターフェイスは、ユーザーインターフェイスイベントに関連する特定のコンテキスト情報を提供します。 |
| [WheelEvent](./wheelevent/) | WheelEvent インターフェイスは、ホイールイベントに関連する特定のコンテキスト情報を提供します。WheelEvent インターフェイスのインスタンスを作成するには、WheelEvent コンストラクタを使用し、オプションの WheelEventInit 辞書を渡します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | DocumentEvent インターフェイスは、実装がサポートするタイプの Event をユーザーが作成できる仕組みを提供します。Event モデルをサポートする実装において、Document インターフェイスを実装する同じオブジェクト上で DocumentEvent インターフェイスが実装されることが期待されています。 |
| [IEventListener](./ieventlistener/) | このインターフェイスは、イベント処理の主要な手段です。ユーザーはインターフェイスを実装し、メソッドを使用してリスナーを登録します。リスナーの使用が完了したら、ユーザーはそれを削除すべきです。 |
| [IEventTarget](./ieventtarget/) | EventTarget インターフェイスは、DOM イベントモデルをサポートする実装におけるすべての Node に実装されています。そのため、このインターフェイスは Node インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用することで取得できます。このインターフェイスは、Event Listener の登録と削除、およびその対象へのイベントディスパッチを可能にします。 |
