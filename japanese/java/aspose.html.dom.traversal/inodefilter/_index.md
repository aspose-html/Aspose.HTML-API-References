---
title: "INodeFilter Interface"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.traversal.INodeFilter インターフェイス。フィルタはノードを除外する方法を知っているオブジェクトです。NodeIterator または TreeWalker に NodeFilter が与えられた場合、次のノードを返す前にフィルタを適用します。フィルタがノードの受け入れを指示した場合、走査ロジックはそのノードを返します。そうでなければ、走査は次のノードを探し、拒否されたノードが存在しなかったかのように振る舞います。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filters はノードを「除外」する方法を知っているオブジェクトです。NodeIterator または TreeWalker に NodeFilter が与えられた場合、次のノードを返す前にフィルタを適用します。フィルタがノードを受け入れると、走査ロジックはそのノードを返します。そうでない場合、走査は次のノードを探し、拒否されたノードが存在しなかったかのように振る舞います。

DOM はフィルタを提供していません。NodeFilter は、ユーザーが独自のフィルタを実装できるインターフェイスにすぎません。

NodeFilters はノード間の走査方法を知る必要も、走査対象のデータ構造について何も知る必要もありません。これにより、フィルタを書くことが非常に簡単になります。なぜなら、フィルタが行うべきことは単一のノードを評価することだけだからです。1 つのフィルタはさまざまな種類の走査で使用でき、コードの再利用を促進します。

こちらも参照してください: [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。 @since DOM Level 2

```java
public interface INodeFilter
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | 指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出されますが、通常はユーザーコードから直接呼び出されません。（同じフィルタを使用して独自のアプリケーションロジックを導く場合は、呼び出すことも可能です。） |

### 関連項目

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
