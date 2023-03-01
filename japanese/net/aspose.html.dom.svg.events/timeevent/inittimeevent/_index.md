---
title: TimeEvent.InitTimeEvent
second_title: Aspose.HTML for .NET API リファレンス
description: TimeEvent 方法. initTimeEvent メソッドはDocumentEvent インターフェイスを介して作成された TimeEvent の値を初期化するために使用されますこのメソッドはTimeEvent が dispatchEvent メソッドを介してディスパッチされる前にのみ呼び出すことができますが必要に応じてそのフェーズ中に複数回呼び出すことができます複数回呼び出された場合最後の呼び出しが優先されます
type: docs
weight: 30
url: /ja/net/aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

initTimeEvent メソッドは、DocumentEvent インターフェイスを介して作成された TimeEvent の値を初期化するために使用されます。このメソッドは、TimeEvent が dispatchEvent メソッドを介してディスパッチされる前にのみ呼び出すことができますが、必要に応じてそのフェーズ中に複数回呼び出すことができます。複数回呼び出された場合、最後の呼び出しが優先されます。

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| typeArg | String | イベントの種類を指定します。 |
| viewArg | IAbstractView | イベントの AbstractView を指定します。 |
| detailArg | Int64 | イベントの詳細を指定します。 |

### 関連項目

* interface [IAbstractView](../../../aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* 名前空間 [Aspose.Html.Dom.Svg.Events](../../timeevent/)
* 組み立て [Aspose.HTML](../../../)


