---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGSVGElement メソッド。実装がサポートするタイプの Event を作成します。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

実装がサポートするタイプの [`Event`](../../../com.aspose.html.dom.events/event/) を作成します。

```java
public Event CreateEvent(String eventType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| eventType | String | eventType パラメータは、作成される [`Event`](../../../com.aspose.html.dom.events/event/) インターフェイスのタイプを指定します。指定された [`Event`](../../../com.aspose.html.dom.events/event/) インターフェイスが実装でサポートされている場合、このメソッドは要求されたインターフェイス型の新しい[`Event`](../../../com.aspose.html.dom.events/event/) を返します。[`Event`](../../../com.aspose.html.dom.events/event/) を [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) メソッドでディスパッチする場合、作成後に適切な[`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) メソッドを呼び出して、[`Event`](../../../com.aspose.html.dom.events/event/) の値を初期化する必要があります。 |

### 戻り値

新しく作成された [`Event`](../../../com.aspose.html.dom.events/event/)

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 要求された [`Event`](../../../com.aspose.html.dom.events/event/) インターフェイスのタイプが実装でサポートされていない場合に発生します |

### 関連項目

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
