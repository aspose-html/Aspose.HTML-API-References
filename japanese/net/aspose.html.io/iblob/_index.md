---
title: Interface IBlob
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.IO.IBlob インターフェース. Blob オブジェクトはバイト シーケンスを参照しバイト シーケンスの合計バイト数である size 属性とバイト シーケンスのメディア タイプを表す小文字の ASCII エンコード文字列である type 属性を持ちます .
type: docs
weight: 3700
url: /ja/net/aspose.html.io/iblob/
---
## IBlob interface

Blob オブジェクトはバイト シーケンスを参照し、バイト シーケンスの合計バイト数である size 属性と、バイト シーケンスのメディア タイプを表す小文字の ASCII エンコード文字列である type 属性を持ちます。 .

```csharp
public interface IBlob
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | バイト シーケンスのサイズをバイト数で返します。 取得時に、適合するユーザー エージェントは、FileReader または FileReaderSync オブジェクトによって読み取ることができる合計バイト数を返す必要があります。Blob に読み取るバイトがない場合は 0 を返します。 . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | Blob のメディア タイプを表す小文字の ASCII エンコード文字列。シーケンス、これは解析可能な MIME タイプ、 、またはタイプを特定できない場合は空の文字列 (0 バイト) です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | オプションの start パラメーターからオプションの end パラメーター までの範囲のバイトと、オプションの contentType パラメーターの値である type 属性を持つ新しい Blob オブジェクトを返します。 |

### 関連項目

* 名前空間 [Aspose.Html.IO](../../aspose.html.io/)
* 組み立て [Aspose.HTML](../../)


