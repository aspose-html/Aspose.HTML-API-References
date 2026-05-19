---
title: "KeyboardEvent クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.KeyboardEvent クラス。KeyboardEvent インターフェイスはキーボードデバイスに関連する特定のコンテキスト情報を提供します。各キーボードイベントは値を使用してキーを参照します。キーボードイベントは通常、フォーカスがある要素に対して発生します。"
type: docs

url: /ja/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent インターフェイスは、キーボードデバイスに関連する特定のコンテキスト情報を提供します。各キーボードイベントは、値を使用してキーを参照します。キーボードイベントは、通常、フォーカスがある要素に対して送信されます。

```java
public class KeyboardEvent : UIEvent
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | `KeyboardEvent` クラスの新しいインスタンスを初期化します。 |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) Alt（代替）キー（または \"Option\" キー）修飾子がアクティブな場合は true。属性の未初期化値は false でなければなりません。 |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) イベントがバブリングイベントかどうかを示すために使用されます。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) イベントのデフォルトアクションを防止できるかどうかを示すために使用されます。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) code は、押された物理キーを識別する文字列を保持します。この値は現在のキーボードレイアウトや修飾子の状態の影響を受けないため、特定のキーは常に同じ値を返します。 |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) Control（制御）キー修飾子がアクティブな場合は true。属性の未初期化値は false でなければなりません。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 現在処理中の [`IEventTarget`](../ieventtarget/) と、その [`IEventListener`](../ieventlistener/) がどれかを示すために使用されます。これはキャプチャおよびバブリング時に特に有用です。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) イベントの種類に応じた詳細情報を指定します。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 現在評価されているイベントフローのフェーズを示すために使用されます。 |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) キーイベントが合成セッションの一部として発生した場合（すなわち compositionstart イベントの後、対応する compositionend イベントの前）に true。属性の未初期化値は false でなければなりません。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted 属性は初期化された値を返す必要があります。イベントが作成されると、この属性は false に初期化されなければなりません。 |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) key は押されたキーのキー値を保持します。値に印刷可能な表現がある場合、空でない Unicode 文字列であり、本仕様で定義されたキー値決定アルゴリズムに従う必要があります。印刷可能な表現がない制御キーの場合、キー値セットで定義されたキー値のいずれかでなければなりません。キーを特定できない実装はキー値として Unidentified を使用しなければなりません。 |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) location 属性はデバイス上のキーの論理的な位置を示す指標を含みます。 |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) meta（Meta）キー修飾子がアクティブな場合は true。 |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) キーが継続的に押されている場合は true。キーを押し続けると、システム設定で決定されたレートで keydown、beforeinput、input の順にイベントが繰り返されなければなりません。長押し動作を持つモバイルデバイスでは、repeat 属性が true の最初のキーイベントが長押しの指標となります。繰り返しが開始されるまでにキーを押し続ける必要がある時間は設定に依存します。 |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) shift（Shift）キー修飾子がアクティブな場合は true。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) イベントが元々ディスパッチされた [`IEventTarget`](../ieventtarget/) を示すために使用されます。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) イベントが作成された時刻（エポックからのミリ秒）を指定するために使用されます。一部のシステムがこの情報を提供しない場合、timeStamp の値はすべてのイベントで利用できないことがあります。利用できない場合は 0 が返されます。エポック時刻の例としてはシステム起動時や 1970年1月1日 0:0:0 UTC が挙げられます。 |
| [getType](../../com.aspose.html.dom.events/event/type/) イベントの名前（大文字小文字を区別しない）。名前は XML 名でなければなりません。 |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view 属性はイベントが生成された Window を識別します。属性の未初期化値は null でなければなりません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) メソッドは、[`IDocumentEvent`](../idocumentevent/) インターフェイスを介して作成された [`Event`](../event/) の値を初期化するために使用されます。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/) メソッドはイベントをキャンセルすることを示すために使用されます。つまり、イベントの結果として実装が通常行うデフォルトの動作は実行されません。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたすべてのイベントリスナーにイベントが届くのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトにもイベントが届くのを防止します。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) メソッドは、イベントフロー中のイベントのさらなる伝搬を防止するために使用されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | このキーがアクティブになったのは左側のキー位置からです（このキーに複数の位置が存在する場合）。 |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | The key activation originated on the numeric keypad or with a virtual key corresponding to the numeric keypad (when there is more than one possible location for this key). Note that the NumLock key should always be encoded with a location of DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | The key activation originated from the right key location (when there is more than one possible location for this key). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | The key activation MUST NOT be distinguished as the left or right version of the key, and (other than the NumLock key) did not originate from the numeric keypad (or did not originate with a virtual key corresponding to the numeric keypad). |

### 関連項目

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
