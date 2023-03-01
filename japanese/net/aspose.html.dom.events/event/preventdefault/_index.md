---
title: Event.PreventDefault
second_title: Aspose.HTML for .NET API リファレンス
description: Event 方法. イベントがキャンセル可能な場合PreventDefaultメソッドはイベントがキャンセルされることを示すために使用されます はイベントの結果として実装によって通常実行されるデフォルト アクションが発生しないことを意味します
type: docs
weight: 120
url: /ja/net/aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

イベントがキャンセル可能な場合、`PreventDefault`メソッドは、イベントがキャンセルされることを示すために使用されます。 は、イベントの結果として実装によって通常実行されるデフォルト アクションが発生しないことを意味します。

```csharp
public void PreventDefault()
```

### 備考

イベント フローのいずれかの段階で、`PreventDefault`メソッドが呼び出され、イベントがキャンセルされます。 イベントに関連付けられたデフォルト アクションは発生しません。 キャンセル不可のイベントに対してこのメソッドを呼び出しても効果はありません。 1 回`PreventDefault`呼び出された後は、イベントの伝播の残りの部分で有効です. このメソッドは、イベント フローのどの段階でも使用できます.

### 関連項目

* class [Event](../)
* 名前空間 [Aspose.Html.Dom.Events](../../event/)
* 組み立て [Aspose.HTML](../../../)


