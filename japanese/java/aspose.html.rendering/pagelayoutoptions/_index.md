---
title: "PageLayoutOptions 列挙型"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.PageLayoutOptions 列挙型。 他の PageSetup オプションと組み合わせてページのサイズとレイアウトを決定するフラグを指定します。 これらのフラグは説明に従って組み合わせることができます。"
type: docs

url: /ja/java/com.aspose.html.rendering/pagelayoutoptions/
---
## PageLayoutOptions enumeration

他の PageSetup オプションと組み合わせてページのサイズとレイアウトを決定するフラグを指定します。これらのフラグは、説明に従って組み合わせることができます。

```java
[Flags]
public enum PageLayoutOptions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | PageLayoutOptions がページのサイズやレイアウトに影響しないことを示すデフォルト値です。 |
| FitToContentWidth | `1` | このフラグは、ページ幅が指定されたページ幅ではなく、コンテンツサイズ自体から決定されることを示します。 コンテンツの幅は各ページごとに個別に計算されます。 |
| UseWidestPage | `2` | FitToContentWidth と組み合わせると、すべてのページの幅が同じになり、すべてのページの中で最も広いコンテンツサイズに等しくなることを示します。 |
| FitToWidestContentWidth | `3` | このフラグは、ページ幅が指定されたページ幅ではなく、コンテンツサイズ自体から決定されることを示します。 すべてのページの幅は同じになり、すべてのページの中で最も広いコンテンツサイズに等しくなります。 |
| FitToContentHeight | `10` | このフラグは、ページの高さが指定されたページ高さではなく、コンテンツサイズ自体から決定されることを示します。 このフラグが指定されると、文書全体のコンテンツが単一ページに配置されます。 |
| ScaleToPageWidth | `100` | このフラグは、利用可能なページ幅と重なるコンテンツとの差が最も大きいページに合わせて文書のコンテンツが拡大縮小されることを示します。 FitToContentWidth フラグと競合し、両方が指定された場合は ScaleToPageWidth のみが有効になります。 |
| ScaleToPageHeight | `1000` | このフラグは、文書のコンテンツが最初のページの高さに合わせて拡大縮小されることを示します。 FitToContentHeight フラグと競合し、両方が指定された場合は ScaleToPageHeight のみが有効になります。 文書のコンテンツは単一ページにのみ配置されます。 |

### 関連項目

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
