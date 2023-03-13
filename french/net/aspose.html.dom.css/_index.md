---
title: Aspose.Html.Dom.Css
second_title: Référence de l'API Aspose.HTML pour .NET
description: Le Aspose.Html.Dom.Css lespace de noms est pour toutes les manipulations liées à CSS. Il se concentre autour des paires nom de propriété CSS  valeur spécifiées par les documents officiels CSS.
type: docs
weight: 70
url: /fr/net/aspose.html.dom.css/
---
Le **Aspose.Html.Dom.Css** l'espace de noms est pour toutes les manipulations liées à CSS. Il se concentre autour des paires nom de propriété CSS - valeur spécifiées par les documents officiels CSS.

## Des classes

| Classer | La description |
| --- | --- |
| [Counter](./counter/) | L'interface Counter est utilisée pour représenter n'importe quelle valeur de compteur ou de fonction de compteurs. Cette interface reflète les valeurs de la propriété de style sous-jacente. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | L'interface CSSPrimitiveValue représente une seule valeur CSS. Cette interface peut être utilisée pour déterminer la valeur d'une propriété de style spécifique actuellement définie dans un bloc ou pour définir explicitement une propriété de style spécifique dans le bloc. Une instance de cette interface peut être obtenue à partir de la méthode getPropertyCSSValue de l'interface CSSStyleDeclaration. Un objet CSSPrimitiveValue n'apparaît que dans le contexte d'une propriété CSS. |
| [CSSValue](./cssvalue/) | Représente une valeur simple ou complexe. Un objet CSSValue n'apparaît que dans le contexte d'une propriété CSS. |
| [CSSValueList](./cssvaluelist/) | L'interface CSSValueList fournit l'abstraction d'une collection ordonnée de valeurs CSS. |
| [Rect](./rect/) | L'interface Rect est utilisée pour représenter n'importe quelle valeur rect. Cette interface reflète les valeurs de la propriété de style sous-jacente. Par conséquent, les modifications apportées aux objets CSSPrimitiveValue modifient la propriété de style. |
| [RGBColor](./rgbcolor/) | L'interface RGBColor est utilisée pour représenter n'importe quelle valeur de couleur RVB. Cette interface reflète les valeurs de la propriété de style sous-jacente. Par conséquent, les modifications apportées aux objets CSSPrimitiveValue modifient la propriété de style. |
## Interfaces

| Interface | La description |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Fournit une interface pour la manipulation des valeurs des ensembles de propriétés CSS2 dans le contexte de certains éléments HTML |
| [ICSSCharsetRule](./icsscharsetrule/) | L'interface CSSCharsetRule représente une règle @charset dans une feuille de style CSS. La valeur de l'attribut encoding n'affecte pas l'encodage des données textuelles dans les objets DOM ; cet encodage est toujours UTF-16. Après le chargement d'une feuille de style, la valeur de l'attribut encoding est la valeur trouvée dans la règle @charset. S'il n'y avait pas de @charset dans le document d'origine, aucun CSSCharsetRule n'est créé. La valeur de l'attribut d'encodage peut également être utilisée comme indice pour l'encodage utilisé lors de la sérialisation de la feuille de style. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | La règle @counter-style permet aux auteurs de définir un style de compteur personnalisé. |
| [ICSSFontFaceRule](./icssfontfacerule/) | L'interface CSSFontFaceRule représente une règle @font-face dans une feuille de style CSS. La règle @font-face est utilisée pour contenir un ensemble de descriptions de polices. |
| [ICSSImportRule](./icssimportrule/) | L'interface CSSImportRule représente une règle @import dans une feuille de style CSS. La règle @import est utilisée pour importer des règles de style à partir d'autres feuilles de style. |
| [ICSSKeyframeRule](./icsskeyframerule/) | L'interface CSSKeyframeRule représente la règle de style pour une seule clé. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | L'interface CSSKeyframesRule représente un ensemble complet d'images clés pour une seule animation |
| [ICSSMarginRule](./icssmarginrule/) | L'interface CSSMarginRule représente une marge at-rule. |
| [ICSSMediaRule](./icssmediarule/) | L'interface CSSMediaRule représente une règle @media dans une feuille de style CSS. Une règle @media peut être utilisée pour délimiter les règles de style pour des types de médias spécifiques. |
| [ICSSPageRule](./icsspagerule/) | L'interface CSSPageRule représente une règle @page dans une feuille de style CSS. La règle @page est utilisée pour spécifier les dimensions, l'orientation, les marges, etc. d'une zone de page pour les médias paginés. |
| [ICSSRule](./icssrule/) | L'interface CSSRule est l'interface de base abstraite pour tout type d'instruction CSS. Cela inclut à la fois les ensembles de règles et les règles at. Une implémentation est censée préserver toutes les règles spécifiées dans une feuille de style CSS, même si la règle n'est pas reconnue par l'analyseur. Les règles non reconnues sont représentées à l'aide de la!:ICSSUnknownRule interface. |
| [ICSSRuleList](./icssrulelist/) | L'interface CSSRuleList fournit l'abstraction d'une collection ordonnée de règles CSS. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | L'interface CSSStyleDeclaration représente un seul bloc de déclaration CSS. Cette interface peut être utilisée pour déterminer les propriétés de style actuellement définies dans un bloc ou pour définir explicitement les propriétés de style dans le bloc. |
| [ICSSStyleRule](./icssstylerule/) | L'interface CSSStyleRule représente un ensemble de règles unique dans une feuille de style CSS. |
| [ICSSStyleSheet](./icssstylesheet/) | L'interface CSSStyleSheet est une interface concrète permettant de représenter une feuille de style CSS c'est à dire une feuille de style dont le type de contenu est "text/css". |
| [ICSSUnknownRule](./icssunknownrule/) | L'interface CSSUnknownRule représente une règle at non prise en charge par cet agent utilisateur. |
| [ICSSValueList](./icssvaluelist/) | L'interface fournit l'abstraction d'une collection ordonnée de valeurs CSS. |
| [IDocumentCSS](./idocumentcss/) | Cette interface représente un document avec une vue CSS. |
| [IDocumentStyle](./idocumentstyle/) | L'interface DocumentStyle fournit un mécanisme par lequel les feuilles de style incorporées dans un document peuvent être récupérées. L'attente est qu'une instance de l'interface DocumentStyle peut être obtenue en utilisant des méthodes de transtypage spécifiques à la liaison sur une instance de l'interface Document. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Les informations de style en ligne attachées aux éléments sont exposées via l'attribut style. Cela représente le contenu de l'attribut STYLE pour les éléments HTML (ou les éléments d'autres schémas ou DTD qui utilisent l'attribut STYLE de la même manière). |
| [ILinkStyle](./ilinkstyle/) | L'interface LinkStyle fournit un mécanisme par lequel une feuille de style peut être récupérée à partir du nœud responsable de la lier dans un document. Une instance de l'interface LinkStyle peut être obtenue à l'aide de méthodes de transtypage spécifiques à la liaison sur une instance d'un nœud de liaison (HTMLLinkElement, HTMLStyleElement ou ProcessingInstruction dans DOM niveau 2). |
| [IMediaList](./imedialist/) | L'interface MediaList fournit l'abstraction d'une collection ordonnée de médias, sans définir ni contraindre la façon dont cette collection est implémentée. Une liste vide est identique à une liste qui contient le support "all". |
| [IStyleSheet](./istylesheet/) | L'interface StyleSheet est l'interface de base abstraite pour tout type de feuille de style. Il représente une seule feuille de style associée à un document structuré. |
| [IStyleSheetList](./istylesheetlist/) | L'interface StyleSheetList fournit l'abstraction d'une collection ordonnée de feuilles de style. |
| [IViewCSS](./iviewcss/) | Cette interface représente une vue CSS. |
## Énumération

| Énumération | La description |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Spécifie le mode CSSEngine |


