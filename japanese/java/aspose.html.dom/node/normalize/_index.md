---
title: "Node.Normalize"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node メソッド。この Node の下位サブツリー全体の深さにあるすべての Text ノード（属性ノードを含む）を、構造（要素、コメント、処理命令、CDATA セクション、エンティティ参照）だけが Text ノードを分離する「正規形」に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。この操作は、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する XPointer ルックアップなどの操作に有用です。Node.ownerDocument に添付された DOMConfiguration オブジェクトのパラメータ normalize-characters が true の場合、このメソッドは Text ノードの文字も完全に正規化します。"
type: docs

url: /ja/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

[`Text`](../../text/) ノードを、この Node の下位サブツリー全体の深さにあるすべて（属性ノードを含む）「正規」形に変換します。構造（例: [`elements`](../../element/)、[`comments`](../../comment/)、[`processing instructions`](../../processinginstruction/)、[`CDATA sections`](../../cdatasection/)、[`entity references`](../../entityreference/)）だけが [`Text`](../../text/) ノードを分離する形です。つまり、隣接する Text ノードや空の Text ノードは存在しません。この操作は、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証し、特定のドキュメントツリー構造に依存する XPointer [XPointer] ルックアップなどの操作に有用です。[`DOMConfiguration`](../../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、[`Node.ownerDocument`](../ownerdocument/) に添付されたこのメソッドは Text ノードの文字も完全に正規化します。

```java
public void Normalize()
```

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
