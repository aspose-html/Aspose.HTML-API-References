---
title: "ISSVGAnimatedPathData インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData インターフェイス。SVGAnimatedPathData インターフェイスは、d 属性に SVG パスデータを保持し、その属性をアニメーション化する機能をサポートする要素をサポートします"
type: docs

url: /ja/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

この SVGAnimatedPathData インターフェイスは、SVG パスデータを保持する ‘d’ 属性を持つ要素をサポートし、その属性をアニメーション化する機能もサポートします。

```java
public interface ISVGAnimatedPathData
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) 現在のアニメーション化された ‘d’ 属性の内容に、SVG の構文と 1 対 1 に一致する形式でアクセスできるようにします。指定された属性またはプロパティがアニメーション化されている場合、属性またはプロパティの現在のアニメーション値を含み、オブジェクト自体とその内容は読み取り専用です。指定された属性またはプロパティが現在アニメーション化されていない場合、pathSegList と同じ値を含みます。 |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) 基本（静的）な ‘d’ 属性の内容に、SVG の構文と 1 対 1 に一致する形式でアクセスできます。したがって、‘d’ 属性に「絶対 moveto (M)」と「絶対 arcto (A)」コマンドがある場合、pathSegList には 2 つのエントリ、SVG_PATHSEG_MOVETO_ABS と SVG_PATHSEG_ARC_ABS が含まれます。 |

### 関連項目

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
