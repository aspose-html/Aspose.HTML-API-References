---
title: "ErrorEvent クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.ErrorEvent クラス。ErrorEvent は、実行時に発生したエラーに関するコンテキスト情報を提供します"
type: docs

url: /ja/java/com.aspose.html.dom.events/errorevent/
---
## ErrorEvent class

ErrorEvent は、実行時に発生したエラーに関するコンテキスト情報を提供します。

```java
public class ErrorEvent : Event
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | `ErrorEvent` クラスの新しいインスタンスを初期化します。 |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;String, object&gt;) |  |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) イベントがバブリングイベントかどうかを示すために使用されます。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) イベントのデフォルトアクションを防止できるかどうかを示すために使用されます。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) colno 属性は初期化された値を返す必要があります。オブジェクトが作成されると、この属性は 0 に初期化されます。これはスクリプト内でエラーが発生した列番号を表します。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 現在処理中の [`IEventTarget`](../ieventtarget/) と、その [`IEventListener`](../ieventlistener/) がどれかを示すために使用されます。これはキャプチャおよびバブリング時に特に有用です。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) error 属性は初期化された値を返す必要があります。オブジェクトが作成されると、この属性は null に初期化されます。適切な場合、エラーを表すオブジェクト（例：捕捉されていない DOM 例外の場合の例外オブジェクト）に設定されます。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 現在評価されているイベントフローのフェーズを示すために使用されます。 |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) filename 属性は初期化された値を返す必要があります。オブジェクトが作成されると、この属性は空文字列に初期化されます。これはエラーが元々発生したスクリプトの絶対 URL を表します。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted 属性は初期化された値を返す必要があります。イベントが作成されると、この属性は false に初期化されなければなりません。 |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) lineno 属性は初期化された値を返す必要があります。オブジェクトが作成されると、この属性は 0 に初期化されなければなりません。これはスクリプト内でエラーが発生した行番号を表します。 |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) message 属性は初期化された値を返す必要があります。オブジェクトが作成されると、この属性は空文字列に初期化されなければなりません。これはエラーメッセージを表します。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) イベントが元々ディスパッチされた [`IEventTarget`](../ieventtarget/) を示すために使用されます。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) イベントが作成された時刻（エポックからのミリ秒）を指定するために使用されます。一部のシステムがこの情報を提供しない場合、timeStamp の値はすべてのイベントで利用できないことがあります。利用できない場合は 0 が返されます。エポック時刻の例としてはシステム起動時や 1970年1月1日 0:0:0 UTC が挙げられます。 |
| [getType](../../com.aspose.html.dom.events/event/type/) イベントの名前（大文字小文字を区別しない）。名前は XML 名でなければなりません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) メソッドは、[`IDocumentEvent`](../idocumentevent/) インターフェイスを介して作成された [`Event`](../event/) の値を初期化するために使用されます。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/) メソッドはイベントをキャンセルすることを示すために使用されます。つまり、イベントの結果として実装が通常行うデフォルトの動作は実行されません。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたすべてのイベントリスナーにイベントが届くのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトにもイベントが届くのを防止します。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) メソッドは、イベントフロー中のイベントのさらなる伝搬を防止するために使用されます。 |

### 関連項目

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
