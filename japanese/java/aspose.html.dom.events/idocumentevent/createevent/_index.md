---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IDocumentEvent メソッド。createEvent メソッドは、ユーザーが自分で Event を作成するのが不便または不要な場合に Event を生成するために使用されます。"
type: docs

url: /ja/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

createEvent メソッドは、ユーザーが自ら Event を作成するのが不便または不要な場合に Event を作成するために使用されます。

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| eventType | 文字列 | eventType パラメータは、作成するインターフェイスのタイプを指定します。指定されたインターフェイスが実装でサポートされている場合、このメソッドは要求されたインターフェイス型の新しいオブジェクトを返します。もし is を method 経由でディスパッチする場合、作成後に適切なメソッドを呼び出して値を初期化する必要があります。このメソッドは、ユーザーが自分で s を作成するのが不便または不要な場合に使用されます。実装が不十分な場合、ユーザーは method で使用するために独自の実装を提供できます。 |

### 戻り値

指定されたイベントタイプの新しく作成されたイベントを返します。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 実装が要求されたインターフェイスのタイプをサポートしていない場合に発生します。 |

### 関連項目

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
