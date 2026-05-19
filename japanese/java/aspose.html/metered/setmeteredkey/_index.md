---
title: "Metered.SetMeteredKey"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Metered メソッド。メータード パブリック キーとプライベート キーを設定します。アプリケーション起動時にメータード ライセンスを購入した場合、この API を通常通り呼び出すだけで十分です。ただし、消費データのアップロードに常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を回避するため、ライセンスステータスを定期的に確認し、評価ステータスの場合は再度この API を呼び出してください。"
type: docs

url: /ja/java/com.aspose.html/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

メータ付きの公開キーとプライベートキーを設定します。メータ付きライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があり、通常はこれだけで十分です。ただし、使用量データのアップロードが常に失敗し 24 時間を超えると、ライセンスは評価版ステータスに設定されます。そのような事態を防ぐため、ライセンスステータスを定期的に確認し、評価版ステータスである場合は再度この API を呼び出してください。

```java
public void SetMeteredKey(String publicKey, String privateKey)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| publicKey | 文字列 | パブリックキー |
| privateKey | 文字列 | プライベートキー |

### 関連項目

* class [Metered](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
