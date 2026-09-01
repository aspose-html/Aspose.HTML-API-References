---
title: "IBlob インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.io.IBlob インターフェイス。Blob オブジェクトはバイトシーケンスを指し、size 属性はバイトシーケンスの総バイト数を示し、type 属性はメディアタイプを表す小文字の ASCII エンコード文字列です。"
type: docs

url: /ja/java/com.aspose.html.io/iblob/
---
## IBlob interface

Blob オブジェクトはバイトシーケンスを指し、バイトシーケンスの総バイト数である size 属性と、バイトシーケンスのメディアタイプを表す小文字の ASCII エンコード文字列である type 属性を持ちます。

```java
public interface IBlob
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) バイトシーケンスのサイズ（バイト数）を返します。取得時、準拠するユーザーエージェントは FileReader または FileReaderSync オブジェクトで読み取れる総バイト数を返す必要があり、Blob に読み取れるバイトがない場合は 0 を返します。 |
| [getType](../../com.aspose.html.io/iblob/type/) Blob のメディアタイプを表す小文字の ASCII エンコード文字列です。取得時、ユーザーエージェントは Blob のタイプを小文字の ASCII エンコード文字列として返す必要があり、バイトシーケンスに変換したときに解析可能な MIME タイプであるか、タイプが判定できない場合は空文字列（バイト数 0）を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | オプションの start パラメータからオプションの end パラメータ（end は含まない）までのバイト範囲を持ち、type 属性がオプションの contentType パラメータの値である新しい Blob オブジェクトを返します。 |

### 関連項目

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
