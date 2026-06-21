---
title: "IElementTraversal インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.traversal.IElementTraversal インターフェイス。ElementTraversal インターフェイスは、文書内の要素間を簡単にナビゲートできるようにする読み取り専用属性の集合です。Element Traversal の準拠実装では、Element を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装しなければなりません。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal インターフェイスは、ドキュメント内の要素間を簡単にナビゲートできるようにする読み取り専用属性の集合です。Element Traversal の準拠実装では、Element を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装しなければなりません。

```java
public interface IElementTraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) この要素の子である要素ノードの現在の数を返します。nodeType が 1 の子ノードがない場合は 0 です。 |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null です。 |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null です。 |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) この要素の次の兄弟要素ノードを返します。文書ツリーでこの要素の後に続く要素兄弟ノードがない場合は null です。 |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) この要素の前の兄弟要素ノードを返します。文書ツリーでこの要素の前にある要素兄弟ノードがない場合は null です。 |

### 関連項目

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
