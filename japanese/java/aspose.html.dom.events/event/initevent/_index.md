---
title: "Event.InitEvent"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Event メソッド。InitEvent メソッドは、theIDocumentEvent インターフェイスを介して作成された Event の値を初期化するために使用されます。"
type: docs

url: /ja/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

`InitEvent` メソッドは、[`Event`](../) を作成する際に [`IDocumentEvent`](../../idocumentevent/) インターフェイスを通じてその値を初期化するために使用されます。

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| type | 文字列 | イベントのタイプです。 |
| bubbles | Boolean | `true` に設定された場合は [bubbles]。 |
| cancelable | Boolean | `true` に設定された場合は [cancelable]。 |

## Remarks

このメソッドは、[`DispatchEvent`](../../ieventtarget/dispatchevent/) メソッドを介して Event がディスパッチされる前にのみ呼び出すことができますが、必要に応じてそのフェーズ中に複数回呼び出すことも可能です。複数回呼び出された場合、最後の呼び出しが優先されます。Event インターフェイスのサブクラスから呼び出された場合、initEvent メソッドで指定された値のみが変更され、他の属性は変更されません。

### 関連項目

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
