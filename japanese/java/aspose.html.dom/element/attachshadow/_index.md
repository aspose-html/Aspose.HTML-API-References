---
title: "Element.AttachShadow"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Element メソッド。shadow root を作成し、現在の要素にアタッチします"
type: docs

url: /ja/java/com.aspose.html.dom/element/attachshadow/
---
## Element.AttachShadow method

シャドウルートを作成し、現在の要素に添付します。

```java
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| モード | ShadowRootMode | shadow root が作成されるモード。 |

### 戻り値

作成された [`ShadowRoot`](../../shadowroot/)。

### 例外

| 例外 | 条件 |
| --- | --- |
| エラー | NotSupportedError: Element は shadow tree をサポートしていません。 |
| エラー | InvalidStateError: Element はすでに shadow tree を持っています。 |

### 関連項目

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
