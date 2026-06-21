---
title: "KeyboardEvent クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.KeyboardEvent クラス。KeyboardEvent インターフェイスは、キーボードデバイスに関連する特定のコンテキスト情報を提供します。各キーボードイベントは値を使用してキーを参照します。キーボードイベントは通常、フォーカスがある要素に対して発生します。"
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
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) Alt（代替）キー（または "Option" キー）修飾子がアクティブな場合は true です。この属性の未初期化値は必ず false でなければなりません。 |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) イベントがバブリングイベントかどうかを示すために使用されます。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) イベントのデフォルトアクションを防止できるかどうかを示すために使用されます。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) code は、押された物理キーを識別する文字列を保持します。この値は現在のキーボードレイアウトや修飾子の状態の影響を受けないため、特定のキーは常に同じ値を返します。 |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) Control（制御）キー修飾子がアクティブな場合は true です。この属性の未初期化値は必ず false でなければなりません。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 現在処理中の [`IEventListener`](../ieventlistener/) を持つ [`IEventTarget`](../ieventtarget/) を示すために使用されます。これはキャプチャおよびバブリング時に特に有用です。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) イベントの種類に応じた詳細情報を指定します。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 現在評価されているイベントフローのフェーズを示すために使用されます。 |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) キーイベントが合成セッションの一部として発生した場合（つまり、compositionstart イベントの後、対応する compositionend イベントの前）に true です。この属性の未初期化値は必ず false でなければなりません。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted属性は初期化された値を返す必要があります。イベントが作成されるとき、この属性はfalseに初期化されなければなりません。 |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) key は押されたキーのキー値を保持します。値に印刷可能な表現がある場合、空でない Unicode 文字列であり、本仕様で定義されたキー値決定アルゴリズムに従わなければなりません。印刷可能な表現がない制御キーの場合、キー値セットで定義されたキー値のいずれかでなければなりません。キーを識別できない実装は、キー値として Unidentified を使用しなければなりません。 |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) location 属性は、デバイス上のキーの論理的な位置を示す指標を含みます。 |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) meta（Meta）キー修飾子がアクティブな場合は true です。 |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) キーが継続的に押されている場合は true です。キーを押し続けると、システム設定で決定された速度で keydown、beforeinput、input の順にイベントが繰り返されます。長押し動作を持つモバイルデバイスでは、repeat 属性が true の最初のキーイベントが長押しの指標となります。繰り返しが開始されるまでにキーを押し続けなければならない時間は設定に依存します。 |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) shift（Shift）キー修飾子がアクティブな場合は true です。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) イベントが元々ディスパッチされた[`IEventTarget`](../ieventtarget/) を示すために使用されます。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) イベントが作成された時刻（エポックからのミリ秒）を指定するために使用されます。一部のシステムがこの情報を提供しない場合、timeStampの値はすべてのイベントで利用できないことがあります。利用できない場合は0が返されます。エポック時刻の例としてはシステム起動時やUTC 1970年1月1日 0:0:0 があります。 |
| [getType](../../com.aspose.html.dom.events/event/type/) イベントの名前（大文字小文字を区別しない）。名前はXML名でなければなりません。 |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view 属性は、イベントが生成された Window を識別します。この属性の未初期化値は必ず null でなければなりません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | この [`InitEvent`](../event/initevent/) メソッドは、[`IDocumentEvent`](../idocumentevent/) インターフェイスを通じて作成された[`Event`](../event/) の値を初期化するために使用されます。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/) メソッドはイベントがキャンセルされることを示すために使用されます。つまり、イベントの結果として実装が通常行うデフォルトの動作は行われません。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたすべてのイベントリスナーにイベントが到達するのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトにもイベントが到達するのを防止します。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | この [`StopPropagation`](../event/stoppropagation/) メソッドは、イベントフロー中のイベントのさらなる伝播を防止するために使用されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | キーが有効になったのは左側のキー位置からです（このキーに複数の位置が存在する場合）。 |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | キーのアクティベーションは、テンキー上またはテンキーに対応する仮想キーから発生しました（このキーに対して複数の可能な位置がある場合）。NumLockキーは常にDOM_KEY_LOCATION_STANDARDの位置でエンコードされるべきです。 |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | キーのアクティベーションは右側のキー位置から発生しました（このキーに対して複数の可能な位置がある場合）。 |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | キーのアクティベーションは左または右のバージョンとして区別してはならず、（NumLockキーを除き）テンキーから、またはテンキーに対応する仮想キーから発生しませんでした。 |

### 関連項目

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
