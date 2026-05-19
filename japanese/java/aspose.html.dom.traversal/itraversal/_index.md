---
title: "ITraversal インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.traversal.ITraversal インターフェイス。イテレータは、NodeList のノード集合や特定の Node が支配する文書サブツリー、クエリ結果、その他任意のノード集合など、一連のノードを順に処理するために使用されます。反復対象のノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は、文書サブツリーの文書順走査のための単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal の createNodeIterator を呼び出すことで作成されます。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

イテレータはノードの集合を順に処理するために使用されます。例えば、NodeList のノード集合、特定のノードが支配する文書サブツリー、クエリの結果、またはその他の任意のノード集合です。イテレートされるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は、文書順にサブツリーを走査するための単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal の createNodeIterator() を呼び出すことで作成されます。

こちらも参照してください: [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。 @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) ノードをフィルタリングするために使用される NodeFilter。 |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) 作成時に指定された NodeIterator のルートノード。 |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) この属性はイテレータを通じて提示されるノードタイプを決定します。利用可能な定数セットは NodeFilter インターフェイスで定義されています。whatToShow で受け入れられないノードはスキップされますが、その子ノードは引き続き考慮される場合があります。なお、このスキップはフィルタが存在する場合でも優先されます。 |

### 関連項目

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
