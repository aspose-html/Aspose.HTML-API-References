---
title: "Node.LookupPrefix"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node メソッド。Node インターフェイスの lookupPrefix メソッドは、指定されたパッケージ URI に対するプレフィックスが存在すればそれを含む文字列を、存在しなければ null を返します。複数のプレフィックスが可能な場合は、最初のプレフィックスが返されます"
type: docs

url: /ja/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

lookupPrefix() メソッドは、Node インターフェイスのもので、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し、存在しなければ null を返します。複数のプレフィックスが可能な場合は、最初のプレフィックスが返されます。

```java
public String LookupPrefix(String packageURI)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| packageURI | 文字列 | プレフィックスを検索するパッケージを含む文字列です。 |

### 戻り値

対応するプレフィックスを含む文字列、または見つからなければ null です。パッケージが null、または空文字列の場合、lookupPrefix() は null を返します。

ノードが [`DocumentType`](../../documenttype/) または [`DocumentFragment`](../../documentfragment/) の場合、lookupPrefix() は常に null を返します。

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
