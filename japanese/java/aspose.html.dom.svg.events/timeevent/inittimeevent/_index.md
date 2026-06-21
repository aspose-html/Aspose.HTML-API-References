---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.HTML for Java API リファレンス"
description: "TimeEvent メソッド。initTimeEvent メソッドは DocumentEvent インターフェイスを通じて作成された TimeEvent の値を初期化するために使用されます。このメソッドは、TimeEvent が dispatchEvent メソッドでディスパッチされる前にのみ呼び出すことができ、必要に応じてそのフェーズ中に複数回呼び出すことも可能です。複数回呼び出された場合、最後の呼び出しが優先されます。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent メソッドは、DocumentEvent インターフェイスを介して作成された TimeEvent の値を初期化するために使用されます。このメソッドは、dispatchEvent メソッドで TimeEvent がディスパッチされる前にのみ呼び出すことができ、必要に応じてそのフェーズ中に複数回呼び出すことができます。複数回呼び出された場合、最後の呼び出しが優先されます。

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| typeArg | 文字列 | イベントのタイプを指定します。 |
| viewArg | IAbstractView | イベントの AbstractView を指定します。 |
| detailArg | Int64 | イベントの詳細を指定します。 |

### 関連項目

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
