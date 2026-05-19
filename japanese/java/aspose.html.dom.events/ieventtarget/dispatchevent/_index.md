---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IEventTarget メソッド。指定された EventTarget に対してイベントを同期的にディスパッチし、影響を受けた EventListener を適切な順序で呼び出します。キャプチャフェーズやオプションのバブリングフェーズを含む通常のイベント処理規則は、dispatchEvent で手動にディスパッチされたイベントにも適用されます。"
type: docs

url: /ja/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

指定された EventTarget に対してイベントをディスパッチし（同期的に）、影響を受けた EventListeners を適切な順序で呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、dispatchEvent() で手動にディスパッチされたイベントに適用されます。

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| イベント | イベント | イベント処理に使用するイベントタイプ、動作、およびコンテキスト情報を指定します。 |

### 戻り値

戻り値は、イベントを処理したリスナーが呼び出されたかどうかを示します。呼び出された場合は false、そうでない場合は true です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | イベントハンドラでスローされた例外は、未捕捉例外として報告されます。イベントハンドラはネストされたコールスタック上で実行され、完了するまで呼び出し元をブロックしますが、例外は呼び出し元へ伝搬しません。 |

## Remarks

この方法でディスパッチされたイベントは、実装が直接ディスパッチするイベントと同じキャプチャおよびバブリングの動作を持ちます。イベントのターゲットは、呼び出された対象です。

### 関連項目

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
