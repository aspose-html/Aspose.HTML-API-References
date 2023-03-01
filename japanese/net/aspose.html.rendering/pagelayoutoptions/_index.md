---
title: Enum PageLayoutOptions
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Rendering.PageLayoutOptions 列挙. 他の PageSetup オプションとともにページのサイズとレイアウトを決定するフラグを指定します これらのフラグは説明に従って組み合わせることができます
type: docs
weight: 4380
url: /ja/net/aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

他の PageSetup オプションとともに、ページのサイズとレイアウトを決定するフラグを指定します。 これらのフラグは、説明に従って組み合わせることができます。

```csharp
[Flags]
public enum PageLayoutOptions
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| None | `0` | PageLayoutOptions がページのサイズとレイアウトに影響しないことを示すデフォルト値. |
| FitToContentWidth | `1` | このフラグは、ページの幅が、指定されたページ幅ではなく、コンテンツ サイズ自体から決定されることを示します。 コンテンツの幅は、ページごとに個別に計算されます。 |
| UseWidestPage | `2` | と組み合わせるとFitToContentWidthすべてのページの幅が同じになり、すべてのページの中で最も幅の広いコンテンツ サイズに等しくなることを示します. |
| FitToWidestContentWidth | `3` | このフラグは、指定されたページ幅からではなく、コンテンツ サイズ自体からページの幅が決定されることを示します。 すべてのページの幅は同じになり、すべてのページの中で最も広いコンテンツ サイズに等しくなります。 |
| FitToContentHeight | `10` | このフラグは、指定されたページの高さではなく、コンテンツのサイズ自体からページの高さが決定されることを示します。 |
| ScaleToPageWidth | `100` | このフラグは、使用可能なページ幅とオーバーラップするコンテンツとの差が最も大きいページに合わせて、ドキュメントのコンテンツがスケーリングされることを示します。 と衝突します。FitToContentWidth flag および両方のフラグが指定されている場合のみScaleToPageWidth有効になります. |
| ScaleToPageHeight | `1000` | このフラグは、ドキュメントのコンテンツが最初のページの高さに合わせてスケーリングされることを示します。 と衝突します。FitToContentHeight flag および両方のフラグが指定されている場合のみScaleToPageHeightが有効になります. すべてのドキュメント コンテンツは、単一のページにのみ配置されます. |

### 関連項目

* 名前空間 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 組み立て [Aspose.HTML](../../)


