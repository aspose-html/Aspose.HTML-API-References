---
title: "MediaQueryList クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.window.MediaQueryList クラス。MediaQueryList オブジェクトは、ドキュメントに適用されたメディアクエリに関する情報を保持し、ドキュメントの状態に対する即時およびイベント駆動のマッチングの両方をサポートします。CSSOM View Module 仕様をご覧ください https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /ja/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

MediaQueryList オブジェクトは、ドキュメントに適用されたメディアクエリに関する情報を保存し、ドキュメントの状態に対する即時マッチングとイベント駆動マッチングの両方をサポートします。CSSOM View Module の仕様をご覧ください: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) コンテキストオブジェクトに関連付けられたドキュメント。 |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) ドキュメントが現在メディアクエリリストにマッチしている場合は true を返し、そうでない場合は false を返すブール値。 |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) シリアライズされたメディアクエリを表す文字列。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/)` インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに配送されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | MediaQueryList の matches 状態変化イベントリスナーを追加します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) にイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | MediaQueryList の matches 状態変化イベントリスナーを削除します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | matches 状態が変化したときに MediaQueryList で発生するイベント。 |

### 関連項目

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
