---
title: Class KeyboardEvent
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Events.KeyboardEvent クラス. KeyboardEvent インターフェイスはキーボード デバイスに関連付けられた特定のコンテキスト情報を提供します各キーボード イベントは値を使用してキーを参照しますキーボード イベントは通常フォーカスのある要素に向けられます
type: docs
weight: 830
url: /ja/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

KeyboardEvent インターフェイスは、キーボード デバイスに関連付けられた特定のコンテキスト情報を提供します。各キーボード イベントは、値を使用してキーを参照します。キーボード イベントは通常、フォーカスのある要素に向けられます。

```csharp
public class KeyboardEvent : UIEvent
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | の新しいインスタンスを初期化します`KeyboardEvent` class. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | の新しいインスタンスを初期化します`KeyboardEvent` class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | Alt (代替) (または "Option") キー修飾子がアクティブだった場合は true。この属性の初期化されていない値は false でなければなりません. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | イベントがバブリング イベントかどうかを示すために使用されます。イベントがバブルできる場合、値は true、それ以外の場合、値は false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | イベントのデフォルト アクションを防止できるかどうかを示すために使用されます。デフォルト アクションを防止できる場合、値は true であり、それ以外の場合、値は false. です。 |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | コードは、押されている物理キーを識別する文字列を保持します。値は現在のキーボード レイアウトや修飾子の状態の影響を受けないため、特定のキーは常に同じ値を返します. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | Control (コントロール) キー修飾子がアクティブだった場合は true. この属性の初期化されていない値は false でなければなりません. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | を示すために使用されます[`IEventTarget`](../ieventtarget/)だれの[`IEventListener`](../ieventlistener/) は現在処理中です. これは、キャプチャとバブリング中に特に役立ちます. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | cancelable 属性値が true のときに preventDefault() が呼び出された場合は true を返し、それ以外の場合は false を返します。 |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | イベントのタイプに応じて、イベントに関する詳細情報を指定します。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | イベントフローのどのフェーズが現在評価されているかを示すために使用されます. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | キー イベントが合成セッションの一部として発生する場合、つまり、合成開始イベントの後、対応する合成終了イベントの前に発生する場合は true。この属性の初期化されていない値は false でなければなりません. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 属性は、初期化された値を返す必要があります。イベントが作成されたら、属性を false. に初期化する必要があります。 |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | キーは、押されたキーのキー値を保持します。値が印刷された表現である場合、この仕様で定義されているキー値を決定するためのアルゴリズムに準拠する、空でない Unicode 文字列でなければなりません。値が印刷された表現を持たない制御キーである場合、キー値を決定するためのアルゴリズムによって決定されるように、キー値セットで定義されたキー値の 1 つである必要があります。キーを識別できない実装では、キー値 Unidentified. を使用する必要があります。 |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | location 属性には、デバイス上のキーの論理的な場所の表示が含まれています。 |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | メタ (メタ) キー修飾子がアクティブだった場合は true. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | キーが持続的に押された場合は true。キーを押し続けると、イベント keydown、beforeinput、input がこの順序で、システム構成によって決定される速度で繰り返される必要があります。キーの長押し動作を行うモバイル デバイスの場合、repeat 属性値が true の最初のキー イベントは、キーの長押しを示すものとして機能する必要があります。繰り返しを開始するためにキーを押さなければならない時間の長さは、構成に依存します. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | シフト (Shift) キー修飾子がアクティブだった場合は true. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | を示すために使用されます[`IEventTarget`](../ieventtarget/)イベントが最初にディスパッチされた先. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | イベントが作成された時刻 (エポックからのミリ秒単位) を指定するために使用されます。 、値 0 が返されます。 エポック時間の例は、システムの開始時間または 1970 年 1 月 1 日の 0:0:0 UTC です。 |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | イベントの名前 (大文字と小文字を区別しない)。名前は XML 名でなければなりません. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | ビュー属性は、イベントが生成されたウィンドウを識別します. この属性の初期化されていない値は null でなければなりません. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../event/initevent/)メソッドは、の値を初期化するために使用されます[`Event`](../event/) the で作成[`IDocumentEvent`](../idocumentevent/)インターフェイス. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/)メソッドは、イベントがキャンセルされることを示すために使用されます。 は、イベントの結果として実装によって通常実行されるデフォルト アクションが発生しないことを意味します。 |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、イベントが現在のイベントリスナーの後に登録されたイベントリスナーに到達するのを防ぎ、ツリーでディスパッチされたときに、イベントが他のオブジェクトに到達するのを防ぎます. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/)メソッドが使用され、イベント フロー中にイベントがさらに伝播するのを防ぎます。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | アクティブ化されたキーは、左側のキーの場所から発生しました (このキーの可能な場所が複数ある場合)。 |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | キーのアクティブ化は、テンキーまたはテンキーに対応する仮想キーで開始されました (このキーの場所が複数ある場合)。 NumLock キーは常に DOM_KEY_LOCATION_STANDARD. の場所でエンコードする必要があることに注意してください。 |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | キーのアクティベーションは、正しいキーの場所から開始されました (このキーの場所が複数ある場合)。 |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | キーのアクティベーションは、キーの左または右のバージョンとして区別してはならず、(NumLock キー以外) テンキーから発生したものではありません (またはテンキーに対応する仮想キーで発生したものではありません)。 |

### 関連項目

* class [UIEvent](../uievent/)
* 名前空間 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 組み立て [Aspose.HTML](../../)


