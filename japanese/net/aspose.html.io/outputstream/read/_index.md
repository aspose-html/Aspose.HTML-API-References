---
title: OutputStream.Read
second_title: Aspose.HTML for .NET API リファレンス
description: OutputStream 方法. ラップされた出力 stream から一連のバイトを読み取り読み取ったバイト数だけストリーム内の位置を進めます
type: docs
weight: 100
url: /ja/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

ラップされた出力 stream から一連のバイトを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| buffer | Byte[] | バイトの配列。このメソッドが戻ると、バッファには指定された バイト配列が含まれ、オフセットと(オフセット+カウント-1)の間の値が、ラップされた出力ストリームから読み取られた バイトに置き換えられます。 |
| offset | Int32 | ラップされた出力ストリームからのデータ read の格納を開始するバッファー内のゼロベースのバイト オフセット。 |
| count | Int32 | ラップされた出力ストリームから読み取られる最大バイト数。 |

### 戻り値

バッファーに読み取られた合計バイト数。これは、要求されたバイト数が現在利用できない場合は、要求されたバイト数 よりも少なくなる可能性があります。ストリームの最後に達した場合は、ゼロ (0) になります。

### 関連項目

* class [OutputStream](../)
* 名前空間 [Aspose.Html.IO](../../outputstream/)
* 組み立て [Aspose.HTML](../../../)


