---
title: "com.aspose.html.accessibility"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.accessibility パッケージは、Web アクセシビリティに関するすべての操作のためのものです。W3C Web Accessibility Initiative の国際標準に準拠しています。"
type: docs

url: /ja/java/com.aspose.html.accessibility/
---
The **com.aspose.html.accessibility** パッケージは、すべての Web アクセシビリティ関連の操作向けです。W3C Web Accessibility Initiative の国際標準に準拠しています。

## クラス

| クラス | 説明 |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Web コンテンツアクセシビリティガイドライン (WCAG) 2 の要件（成功基準）とテクニックへのクイックリファレンスです。原則のリストが含まれます。 https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | Validator クラスはクイックリファレンスルールを処理します。アクセシビリティをチェックする Validate メソッドを含みます。 |
| [Criterion](./criterion/) | 各推奨項目に対して検証可能な成功基準が提供されているため、コンプライアンステストが必要な領域で WCAG 2.0 を適用できます。 https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | ガイドライン - 原則の次のレベルです。テスト可能ではありませんが、フレームワークや一般的な目標を概説し、作者が成功基準を理解し、テクニックをより適切に適用できるよう支援します。ガイドラインは、タイプ RuleDirectory{Criterion} の受け入れ基準のリストです。 |
| [Principle](./principle/) | アクセシビリティ原則 - Web アクセシビリティの基盤を提供する最高レベルで、タイプ RuleCollection{Guideline} のガイドラインのリストを含みます。このオブジェクトはアセンブリ外で作成できません。 https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Rule の特性を定義し、インターフェイス IRule を実装する抽象クラスです。 |
| [Target](./target/) | クラスはエラーが見つかった HTML または CSS 要素の項目を含みます。 |
| [ValidationBuilder](./validationbuilder/) | ValidationBuilder クラスは構成手順の具体的な実装を提供します。クラス ValidationSettings のメソッドと設定を定義します。 |
| [WebAccessibility](./webaccessibility/) | Web コンテンツアクセシビリティガイドライン (WCAG) 2 の要件（成功基準）とテクニックへのオブジェクトです。 https://www.w3.org/WAI/WCAG21/quickref/ |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IError](./ierror/) | インターフェイスは検証のエラーを記述します。 |
| [IRule](./irule/) | ルールの主要なプロパティを記述するインターフェイス。 |
| [ITechniqueResult](./itechniqueresult/) | 技術検証の結果を記述します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [TargetTypes](./targettypes/) | エラーを含む HTML ドキュメントから生成されるオブジェクトのタイプ列挙です。 |
