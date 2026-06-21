---
title: "Sandbox 列挙型"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.Sandbox 列挙型。サンドボックスフラグセットは、潜在的に信頼できないリソースの機能を制限するために使用される、以下のフラグの 0 個以上の集合です"
type: docs

url: /ja/java/com.aspose.html/sandbox/
---
## Sandbox enumeration

サンドボックスフラグセットは、以下のフラグの 0 個以上の組み合わせで、潜在的に信頼できないリソースの機能を制限するために使用されます。

```java
[Flags]
public enum Sandbox
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | フラグが設定されていない場合、すべてのサンドボックス機能が許可されます |
| Navigation | `1` | このフラグは、サンドボックス化された閲覧コンテキスト自体（またはその内部にさらにネストされた閲覧コンテキスト）以外の閲覧コンテキスト、補助閲覧コンテキスト（次に定義される sandboxed auxiliary navigation browsing context フラグで保護されます）、およびトップレベル閲覧コンテキスト（以下で定義される sandboxed top-level navigation browsing context フラグで保護されます）へのナビゲーションを防止します。sandboxed auxiliary navigation browsing context フラグが設定されていない場合、特定のケースでは制限にもかかわらずポップアップ（新しいトップレベル閲覧コンテキスト）の開放が許可されることがあります。これらの閲覧コンテキストは常に、作成時に設定される許可されたサンドボックスナビゲータを持ち、作成元の閲覧コンテキストが実際にそれらをナビゲートできるようにします。（そうでなければ、sandboxed navigation browsing context フラグにより、開かれた場合でもナビゲートが阻止されます。） |
| AuxiliaryNavigation | `2` | このフラグは、target 属性の使用や window.open() メソッドなどにより、新しい補助閲覧コンテキストの作成を防止します。 |
| TopLevelNavigation | `4` | このフラグは、コンテンツが自身のトップレベル閲覧コンテキストをナビゲートしたり閉じたりすることを防止します。sandboxed top-level navigation browsing context フラグが設定されていない場合、コンテンツはトップレベル閲覧コンテキストをナビゲートできますが、他の閲覧コンテキストは引き続き sandboxed navigation browsing context フラグおよび場合によっては sandboxed auxiliary navigation browsing context フラグによって保護されます。 |
| Plugins | `8` | このフラグは、embed 要素、object 要素、applet 要素の使用や、ネストされた閲覧コンテキストのナビゲーションを通じてプラグインをインスタンス化することを防止します（ただし、プラグインが保護できる場合は除きます）。 |
| Origin | `10` | このフラグはコンテンツを一意のオリジンに強制し、同一オリジンの他のコンテンツへのアクセスを防止します。 |
| Forms | `20` | このフラグはフォーム送信をブロックします。 |
| PointerLock | `40` | このフラグは Pointer Lock API を無効にします。 |
| Scripts | `80` | このフラグはスクリプトの実行をブロックします。 |
| AutomaticFeatures | `100` | このフラグは、ビデオの自動再生やフォームコントロールの自動フォーカスなど、自動的にトリガーされる機能をブロックします。 |
| Fullscreen | `200` | このフラグは、コンテンツが requestFullscreen() メソッドを使用することを防止します。 |
| DocumentDomain | `400` | このフラグは、コンテンツが document.domain 機能を使用して実効スクリプトオリジンを変更することを防止します。 |
| Images | `800` | このフラグは画像の読み込みを無効にします。 |

### 関連項目

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
