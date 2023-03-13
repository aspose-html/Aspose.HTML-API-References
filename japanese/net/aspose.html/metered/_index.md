---
title: Class Metered
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Metered クラス. メータリング キーを設定するメソッドを提供します
type: docs
weight: 3830
url: /ja/net/aspose.html/metered/
---
## Metered class

メータリング キーを設定するメソッドを提供します。

```csharp
public class Metered
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Metered](metered/)() | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | 従量制の公開鍵と秘密鍵を設定します。 従量制ライセンスを購入した場合、アプリ起動時にこの API を呼び出す必要がありますが、通常はこれで十分です。 ただし、常に消費データのアップロードに失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます. そのような場合を避けるために、定期的にライセンスステータスを確認し、評価ステータスである場合は、この API を再度呼び出す必要があります. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | 消費クレジットを取得 |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | 消費ファイルサイズを取得 |

### 例

この例では、従量制の公開鍵と秘密鍵を設定しようとします

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

コンポーネント jar ファイル:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 関連項目

* 名前空間 [Aspose.Html](../../aspose.html/)
* 組み立て [Aspose.HTML](../../)


