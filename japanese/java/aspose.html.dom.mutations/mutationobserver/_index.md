---
title: "MutationObserver クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.mutations.MutationObserver クラス。オブジェクトはツリーへの変異を観測するために使用できます。"
type: docs

url: /ja/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

オブジェクトは [`.`](../../com.aspose.html.dom/node/) のツリーへの変異を観測するために使用できます。

```java
public class MutationObserver : DOMObject
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | MutationObserver オブジェクトを構築し、その [`MutationCallback`](../mutationcallback/) をコールバックに設定します。コールバックは MutationRecord オブジェクトのリストを第一引数に、構築された MutationObserver オブジェクトを第二引数にして呼び出されます。これは !:Observe(Node, IMutationObserverInit) メソッドで登録されたノードが変異した後に呼び出されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | オブザーバーが変異の観測を停止します。observe() メソッドが再度使用されるまで、オブザーバーのコールバックは呼び出されません。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | ユーザーエージェントに指定されたターゲット（ノード）を観測させ、options（オブジェクト）で指定された基準に基づいて変異を報告させます。options 引数はオブジェクトのメンバーを通じて変異観測オプションを設定できるようにします。 |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | ユーザーエージェントに指定されたターゲット（ノード）を観測させ、options（オブジェクト）で指定された基準に基づいて変異を報告させます。options 引数はオブジェクトのメンバーを通じて変異観測オプションを設定できるようにします。 |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | このメソッドはレコードキューのコピーを返し、キューを空にします。 |

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
