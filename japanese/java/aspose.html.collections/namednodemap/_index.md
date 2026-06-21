---
title: "NamedNodeMap クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.collections.NamedNodeMap クラス。名前でアクセスできる属性のコレクションを表します。"
type: docs

url: /ja/java/com.aspose.html.collections/namednodemap/
---
## NamedNodeMap class

名前でアクセスできる属性のコレクションを表します。

```java
public class NamedNodeMap : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getItem](../../com.aspose.html.collections/namednodemap/item/) マップ内のインデックス番目の項目を返します。インデックスがこのマップのノード数以上の場合は null を返します。（2 つのインデクサー） |
| [getLength](../../com.aspose.html.collections/namednodemap/length/) このマップ内のノード数です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getNamedItem](../../com.aspose.html.collections/namednodemap/getnameditem/)(String) | 名前で指定されたノードを取得します。 |
| [getNamedItemNS](../../com.aspose.html.collections/namednodemap/getnameditemns/)(String, String) | ローカル名とパッケージ URI で指定されたノードを取得します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [removeNamedItem](../../com.aspose.html.collections/namednodemap/removenameditem/)(String) | 名前で指定されたノードを削除します。 |
| [removeNamedItemNS](../../com.aspose.html.collections/namednodemap/removenameditemns/)(String, String) | ローカル名とパッケージ URI で指定されたノードを削除します。 |
| [setNamedItem](../../com.aspose.html.collections/namednodemap/setnameditem/)(Attr) | nodeName 属性を使用してノードを追加します。その名前のノードが既にこのマップに存在する場合、新しいノードで置き換えられます。自分自身のノードを置き換えても効果はありません。 |
| [setNamedItemNS](../../com.aspose.html.collections/namednodemap/setnameditemns/)(Attr) | packageURI と localName を使用してノードを追加します。そのパッケージ URI とローカル名のノードが既にこのマップに存在する場合、新しいノードで置き換えられます。自分自身のノードを置き換えても効果はありません。 |

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.collections](../../com.aspose.html.collections/)
* package [Aspose.HTML](../../)
