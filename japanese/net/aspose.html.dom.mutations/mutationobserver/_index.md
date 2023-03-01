---
title: Class MutationObserver
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Mutations.MutationObserver クラス. AMutationObserverオブジェクトはのツリーへの突然変異を観察するために使用できますNode.
type: docs
weight: 970
url: /ja/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

A`MutationObserver`オブジェクトは、のツリーへの突然変異を観察するために使用できます[`Node`](../../aspose.html.dom/node/).

```csharp
public class MutationObserver : DOMObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | MutationObserver オブジェクトを構築し、その[`MutationCallback`](../mutationcallback/)コールバックします。 コールバックは、MutationRecord オブジェクトのリストを最初の引数として、構築された MutationObserver オブジェクトを 2 番目の引数として呼び出されます。にノードが登録された後に呼び出されます。!:Observe(Node, IMutationObserverInit)メソッド、変異しています. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | オブザーバーがミューテーションを監視するのを停止します。 observe() メソッドが再度使用されるまで、オブザーバーのコールバックは呼び出されません. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | ユーザー エージェントに、指定されたターゲット (ノード) を監視し、オプション (オブジェクト) によって指定された基準に基づいて変更を報告するように指示します。 |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | ユーザー エージェントに、指定されたターゲット (ノード) を監視し、オプション (オブジェクト) によって指定された基準に基づいて変更を報告するように指示します。 |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | メソッドはレコード キューのコピーを返し、レコード キューを空にします。 |

### 関連項目

* class [DOMObject](../../aspose.html.dom/domobject/)
* 名前空間 [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* 組み立て [Aspose.HTML](../../)


