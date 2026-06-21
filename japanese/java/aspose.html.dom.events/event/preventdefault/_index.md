---
title: "Event.PreventDefault"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Event のメソッドです。イベントがキャンセル可能な場合、PreventDefault メソッドはイベントがキャンセルされることを示すために使用され、実装が通常イベントの結果として行うデフォルトの動作は行われません。"
type: docs

url: /ja/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

イベントがキャンセル可能な場合、`PreventDefault` メソッドはイベントがキャンセルされることを示すために使用され、実装が通常イベントの結果として行うデフォルトの動作は行われません。

```java
public void PreventDefault()
```

## 備考

イベントフローの任意の段階で `PreventDefault` メソッドが呼び出された場合、イベントはキャンセルされます。イベントに関連付けられたデフォルトの動作は実行されません。キャンセル不可能なイベントに対してこのメソッドを呼び出しても効果はありません。`PreventDefault` が一度呼び出されると、イベントの伝搬が残りの間ずっと有効です。このメソッドはイベントフローの任意の段階で使用できます。

### 関連項目

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
