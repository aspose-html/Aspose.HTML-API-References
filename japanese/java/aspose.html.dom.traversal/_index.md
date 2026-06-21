---
title: "com.aspose.html.dom.traversal"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.traversal パッケージには、要素間をナビゲートし、ノードとその子を文書順に走査するイテレータやツリーワーカーを作成するメソッドが含まれています。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/
---
**com.aspose.html.dom.traversal** パッケージには、要素間をナビゲートし、ドキュメント順にノードとその子ノードを走査するイテレータやツリーワーカーを作成するメソッドが含まれています。

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal には、ノードとその子を文書順（深さ優先、先行順走査で、文書のテキスト表現における開始タグの出現順と同等）に走査するイテレータやツリーワーカーを作成するメソッドが含まれています。Traversal 機能をサポートする DOM では、DocumentTraversal は Document インターフェイスを実装するオブジェクトと同じオブジェクトによって実装されます。 |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal インターフェイスは、ドキュメント内の要素間を簡単にナビゲートできるようにする読み取り専用属性の集合です。Element Traversal の準拠実装では、Element を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装しなければなりません。 |
| [INodeFilter](./inodefilter/) | Filters はノードを「除外」する方法を知っているオブジェクトです。NodeIterator または TreeWalker に NodeFilter が与えられた場合、次のノードを返す前にフィルタを適用します。フィルタがノードを受け入れると、走査ロジックはそのノードを返します。そうでない場合、走査は次のノードを探し、拒否されたノードが存在しなかったかのように振る舞います。 |
| [INodeIterator](./inodeiterator/) | Iterators はノードの集合を順に処理するために使用されます。例えば NodeList のノード集合、特定の Node が支配する文書サブツリー、クエリの結果、またはその他の任意のノード集合です。反復対象となるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は文書順にサブツリーを走査するための単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal の createNodeIterator() を呼び出すことで作成されます。 |
| [ITraversal](./itraversal/) | Iterators はノードの集合を順に処理するために使用されます。例えば NodeList のノード集合、特定の Node が支配する文書サブツリー、クエリの結果、またはその他の任意のノード集合です。反復対象となるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は文書順にサブツリーを走査するための単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal の createNodeIterator() を呼び出すことで作成されます。 |
| [ITreeWalker](./itreewalker/) | TreeWalker オブジェクトは、whatToShow フラグとフィルタ（存在する場合）で定義された文書のビューを使用して、文書ツリーまたはサブツリーをナビゲートするために使用されます。TreeWalker を使用してナビゲーションを行うすべての関数は、TreeWalker が定義する任意のビューを自動的にサポートします。 |
