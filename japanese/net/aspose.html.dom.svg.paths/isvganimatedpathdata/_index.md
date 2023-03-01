---
title: Interface ISVGAnimatedPathData
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData インターフェース. SVGAnimatedPathData インターフェイスはSVG パス データを保持するd属性を持つ要素をサポートしその属性をアニメーション化する機能をサポートします
type: docs
weight: 1680
url: /ja/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData インターフェイスは、SVG パス データを保持する「d」属性を持つ要素をサポートし、その属性をアニメーション化する機能をサポートします。

```csharp
public interface ISVGAnimatedPathData
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | SVG の構文と 1 対 1 で一致する形式で、'd' 属性の現在のアニメーション化されたコンテンツへのアクセスを提供します。指定された属性またはプロパティがアニメーション化されている場合、属性またはプロパティの現在のアニメーション化された値が含まれ、オブジェクト自体とそのコンテンツの両方が読み取り専用になります。指定された属性またはプロパティが現在アニメーション化されていない場合、pathSegList. と同じ値が含まれます。 |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | SVG の構文と 1 対 1 で一致する形式で、'd' 属性の基本 (静的) コンテンツへのアクセスを提供します。 したがって、「d」属性に「absolute moveto (M)」コマンドと「absolute arcto (A)」コマンドがある場合、pathSegList には SVG_PATHSEG_MOVETO_ABS と SVG_PATHSEG_ARC_ABS の 2 つのエントリが含まれます。 |

### 関連項目

* 名前空間 [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* 組み立て [Aspose.HTML](../../)


