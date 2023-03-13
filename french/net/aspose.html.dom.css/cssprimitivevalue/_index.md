---
title: Class CSSPrimitiveValue
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Css.CSSPrimitiveValue classe. Linterface CSSPrimitiveValue représente une seule valeur CSS. Cette interface peut être utilisée pour déterminer la valeur dune propriété de style spécifique actuellement définie dans un bloc ou pour définir explicitement une propriété de style spécifique dans le bloc. Une instance de cette interface peut être obtenue à partir de la méthode getPropertyCSSValue de linterface CSSStyleDeclaration. Un objet CSSPrimitiveValue napparaît que dans le contexte dune propriété CSS.
type: docs
weight: 330
url: /fr/net/aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

L'interface CSSPrimitiveValue représente une seule valeur CSS. Cette interface peut être utilisée pour déterminer la valeur d'une propriété de style spécifique actuellement définie dans un bloc ou pour définir explicitement une propriété de style spécifique dans le bloc. Une instance de cette interface peut être obtenue à partir de la méthode getPropertyCSSValue de l'interface CSSStyleDeclaration. Un objet CSSPrimitiveValue n'apparaît que dans le contexte d'une propriété CSS.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Propriétés

| Nom | La description |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Une représentation sous forme de chaîne de la valeur actuelle. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Un code définissant le type de la valeur. |
| [PrimitiveType](../../aspose.html.dom.css/cssprimitivevalue/primitivetype/) { get; } | Le type de la valeur tel que défini par les constantes spécifiées ci-dessus. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Détermine si la valeur spécifiéeObject est égal à cette instance. |
| abstract [GetCounterValue](../../aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Cette méthode est utilisée pour obtenir la valeur du compteur. Si cette valeur CSS ne contient pas de valeur de compteur, une DOMException est levée. La modification de la propriété de style correspondante peut être réalisée à l'aide de l'interface Counter. |
| abstract [GetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Cette méthode est utilisée pour obtenir une valeur flottante dans une unité spécifiée. Si cette valeur CSS ne contient pas de valeur flottante ou ne peut pas être convertie dans l'unité spécifiée, une DOMException est levée. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Renvoie un code de hachage pour cette instance. |
| abstract [GetIntValue](../../aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Cette méthode est utilisée pour obtenir une valeur int dans une unité spécifiée. Si cette valeur CSS ne contient pas de valeur int ou ne peut pas être convertie dans l'unité spécifiée, une DOMException est levée. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| abstract [GetRectValue](../../aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Cette méthode est utilisée pour obtenir la valeur Rect. Si cette valeur CSS ne contient pas de valeur rect, une exception DOMException est levée. La modification de la propriété de style correspondante peut être réalisée à l'aide de l'interface Rect. |
| abstract [GetRGBColorValue](../../aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Cette méthode est utilisée pour obtenir la couleur RVB. Si cette valeur CSS ne contient pas de valeur de couleur RVB, une exception DOMException est levée. La modification de la propriété de style correspondante peut être réalisée à l'aide de l'interface RGBColor. |
| abstract [GetStringValue](../../aspose.html.dom.css/cssprimitivevalue/getstringvalue/)() | Cette méthode est utilisée pour obtenir la valeur de la chaîne. Si la valeur CSS ne contient pas de valeur de chaîne, une exception DOMException est levée. |
| abstract [SetFloatValue](../../aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Une méthode pour définir la valeur flottante avec une unité spécifiée. Si la propriété attachée avec cette valeur ne peut pas accepter l'unité spécifiée ou la valeur flottante, la valeur sera inchangée et une DOMException sera levée. |
| abstract [SetIntValue](../../aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Une méthode pour définir la valeur int avec une unité spécifiée. Si la propriété attachée avec cette valeur ne peut pas accepter l'unité spécifiée ou la valeur int, la valeur sera inchangée et une DOMException sera levée. |
| abstract [SetStringValue](../../aspose.html.dom.css/cssprimitivevalue/setstringvalue/)(ushort, string) | Une méthode pour définir la valeur de chaîne avec l'unité spécifiée. Si la propriété attachée à cette valeur ne peut pas accepter l'unité spécifiée ou la valeur de chaîne, la valeur sera inchangée et une DOMException sera levée. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [CSS_ATTR](../../aspose.html.dom.css/cssprimitivevalue/css_attr/) | La valeur est une fonction d'attribut. La valeur peut être obtenue en utilisant la méthode getStringValue. |
| const [CSS_CH](../../aspose.html.dom.css/cssprimitivevalue/css_ch/) | La valeur est une longueur (ch). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_CM](../../aspose.html.dom.css/cssprimitivevalue/css_cm/) | La valeur est une longueur (cm). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_COUNTER](../../aspose.html.dom.css/cssprimitivevalue/css_counter/) | La valeur est un compteur ou une fonction de compteurs. La valeur peut être obtenue en utilisant la méthode GetCounterValue. |
| const [CSS_DEG](../../aspose.html.dom.css/cssprimitivevalue/css_deg/) | La valeur est un angle (deg). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_DIMENSION](../../aspose.html.dom.css/cssprimitivevalue/css_dimension/) | La valeur est un nombre avec une dimension inconnue. La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_DPCM](../../aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | La valeur est un point par centimètre (dpcm). |
| const [CSS_DPI](../../aspose.html.dom.css/cssprimitivevalue/css_dpi/) | La valeur est un point par pouce (dpi). |
| const [CSS_DPPX](../../aspose.html.dom.css/cssprimitivevalue/css_dppx/) | La valeur est un point par unité 'px' (dppx). |
| const [CSS_EMS](../../aspose.html.dom.css/cssprimitivevalue/css_ems/) | La valeur est une longueur (ems). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_EXS](../../aspose.html.dom.css/cssprimitivevalue/css_exs/) | La valeur est une longueur (exs). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_GRAD](../../aspose.html.dom.css/cssprimitivevalue/css_grad/) | La valeur est un angle (grad). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_HZ](../../aspose.html.dom.css/cssprimitivevalue/css_hz/) | La valeur est une fréquence (Hz). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_IDENT](../../aspose.html.dom.css/cssprimitivevalue/css_ident/) | La valeur est un identifiant. La valeur peut être obtenue en utilisant la méthode getStringValue. |
| const [CSS_IN](../../aspose.html.dom.css/cssprimitivevalue/css_in/) | La valeur est une longueur (po). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_KHZ](../../aspose.html.dom.css/cssprimitivevalue/css_khz/) | La valeur est une fréquence (kHz). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_MM](../../aspose.html.dom.css/cssprimitivevalue/css_mm/) | La valeur est une longueur (mm). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_MS](../../aspose.html.dom.css/cssprimitivevalue/css_ms/) | La valeur est un temps (ms). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_NUMBER](../../aspose.html.dom.css/cssprimitivevalue/css_number/) | La valeur est un simple nombre. La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_PC](../../aspose.html.dom.css/cssprimitivevalue/css_pc/) | La valeur est une longueur (pc). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.html.dom.css/cssprimitivevalue/css_percentage/) | La valeur est un pourcentage. La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_PT](../../aspose.html.dom.css/cssprimitivevalue/css_pt/) | La valeur est une longueur (pt). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_PX](../../aspose.html.dom.css/cssprimitivevalue/css_px/) | La valeur est une longueur (px). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_RAD](../../aspose.html.dom.css/cssprimitivevalue/css_rad/) | La valeur est un angle (rad). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_RECT](../../aspose.html.dom.css/cssprimitivevalue/css_rect/) | La valeur est une fonction rect. La valeur peut être obtenue en utilisant la méthode GetRectValue. |
| const [CSS_REM](../../aspose.html.dom.css/cssprimitivevalue/css_rem/) | La valeur est une longueur (rem). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | La valeur est une couleur RVB. La valeur peut être obtenue en utilisant la méthode GetRGBColorValue. |
| const [CSS_S](../../aspose.html.dom.css/cssprimitivevalue/css_s/) | La valeur est un temps (s). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_STRING](../../aspose.html.dom.css/cssprimitivevalue/css_string/) | La valeur est une CHAÎNE. La valeur peut être obtenue en utilisant la méthode getStringValue. |
| const [CSS_UNKNOWN](../../aspose.html.dom.css/cssprimitivevalue/css_unknown/) | La valeur n'est pas une valeur CSS2 reconnue. La valeur ne peut être obtenue qu'en utilisant l'attribut cssText. |
| const [CSS_URI](../../aspose.html.dom.css/cssprimitivevalue/css_uri/) | La valeur est un URI. La valeur peut être obtenue en utilisant la méthode getStringValue. |
| const [CSS_VH](../../aspose.html.dom.css/cssprimitivevalue/css_vh/) | La valeur est un pourcentage de la hauteur totale de la fenêtre. |
| const [CSS_VMAX](../../aspose.html.dom.css/cssprimitivevalue/css_vmax/) | La valeur est un pourcentage de la largeur ou de la hauteur de la fenêtre, selon la valeur la plus grande. |
| const [CSS_VMIN](../../aspose.html.dom.css/cssprimitivevalue/css_vmin/) | La valeur est un pourcentage de la largeur ou de la hauteur de la fenêtre, selon la valeur la plus petite. |
| const [CSS_VW](../../aspose.html.dom.css/cssprimitivevalue/css_vw/) | La valeur est un pourcentage de la largeur totale de la fenêtre. |

### Voir également

* class [CSSValue](../cssvalue/)
* espace de noms [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* Assemblée [Aspose.HTML](../../)


