---
title: "ValidationBuilder クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.accessibility.ValidationBuilder クラス。ValidationBuilder クラスは構成手順の具体的な実装を提供します。クラス ValidationSettings のメソッドと設定を定義します。"
type: docs

url: /ja/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

ValidationBuilder クラスは構成手順の具体的な実装を提供します。クラス ValidationSettings のメソッドと設定を定義します。

```java
public class ValidationBuilder
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) すべてのレベルとすべてのテクノロジー設定を含みます。 |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) デフォルト設定：General テクノロジーのみが使用され、最低基準レベルです。 |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) 設定なし - パラメーターは指定されていません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | すべての基準レベルを設定するメソッドです。また、ドキュメントが3つすべてのレベルの基準に従ってチェックされることを示します。 |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | テスト基準に対してすべてのテクノロジーを設定するメソッドです。 |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | チェックする HTML タグのリスト。タグが明示的に指定されていない場合、タグ配列は空になり、すべてを対象にチェックが行われます。 |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | ルールのセットに CSS テクノロジーを含めるメソッドです。 |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | ルールのセットに Failures を含めるメソッドです。 |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | ルールのセットに General テクノロジーを含めるメソッドです。 |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | ルールで基準の最高レベル AAA を使用します。 |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | ルールのセットに HTML テクノロジーを含めるメソッドです。 |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | ルールで基準の最低レベル A を使用します。 |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | ルールで基準の中間レベル AA を使用します。 |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | ルールのセットに ClientSideScript テクノロジーを含めるメソッドです。 |

### 関連項目

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
