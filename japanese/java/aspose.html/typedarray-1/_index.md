---
title: "TypedArrayT クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.TypedArray1T クラス。TypedArray オブジェクトは、基礎となるバイナリデータバッファの配列のようなビューを提供します"
type: docs

url: /ja/java/com.aspose.html/typedarray-1/
---
## TypedArray&lt;T&gt; class

TypedArray オブジェクトは、基になるバイナリデータバッファの配列のようなビューを提供します。

```java
public abstract class TypedArray<T> : TypedArray
    where T : struct
```

| パラメータ | 説明 |
| --- | --- |
| T | データ型です。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBuffer](../../com.aspose.html/typedarray/buffer/) このインスタンスが参照する ArrayBuffer を取得します。 |
| [getByteLength](../../com.aspose.html/typedarray/bytelength/) byteLength アクセサ プロパティを取得します。このプロパティは ArrayBuffer のバイト単位の長さを表します。 |
| [getByteOffset](../../com.aspose.html/typedarray/byteoffset/) 参照された ArrayBuffer の開始位置からの byteOffset を取得します。 |
| abstract [Item](../../com.aspose.html/typedarray-1/item/) { get; set; } | 指定されたインデックスの !:T を取得または設定します。 |
| [getLength](../../com.aspose.html/typedarray/length/) 型付き配列の長さを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |

### 関連項目

* class [TypedArray](../typedarray/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
