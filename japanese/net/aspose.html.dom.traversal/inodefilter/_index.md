---
title: Interface INodeFilter
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Traversal.INodeFilter インターフェース. フィルターはノードをフィルターで除外する方法を知っているオブジェクトです NodeIterator または TreeWalker に NodeFilter が指定されている場合次の ノードを返す前にフィルターを適用しますフィルターがノードを受け入れるように指示する場合トラバーサル ロジックは it を返しますそれ以外の場合トラバーサルは次のノードを探し拒否された ノードが存在しないふりをします.
type: docs
weight: 2490
url: /ja/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

フィルターは、ノードを「フィルターで除外」する方法を知っているオブジェクトです。 NodeIterator または TreeWalker に NodeFilter が指定されている場合、次の ノードを返す前にフィルターを適用します。フィルターがノードを受け入れるように指示する場合、トラバーサル ロジックは it を返します。それ以外の場合、トラバーサルは次のノードを探し、拒否された ノードが存在しないふりをします.

DOM はフィルターを提供しません。 NodeFilter は、ユーザーが独自のフィルターを提供するために実装できる単なる インターフェイスです。

NodeFilters は、ノード からノードへのトラバース方法を知る必要はなく、 がトラバースされるデータ構造について何も知る必要もありません。 が知っていなければならないことは単一のノードを評価することだけなので、これによりフィルターの作成が非常に簡単になります。 1 つの フィルターをさまざまな種類のトラバーサルで使用でき、 コードの再利用が促進されます.

も参照してください。[ドキュメント オブジェクト モデル (DOM) レベル 2 トラバーサルおよび範囲指定](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM レベル 2

```csharp
public interface INodeFilter
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | 指定されたノードが TreeWalker または NodeIterator の論理ビューに表示されるかどうかをテストします。この関数 は、TreeWalker および NodeIterator の実装によって呼び出されます。通常、 ユーザー コードから直接呼び出されることはありません。 (ただし、同じ フィルターを使用して独自のアプリケーション ロジックをガイドする場合は、そうすることができます。) |

### 関連項目

* 名前空間 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 組み立て [Aspose.HTML](../../)


