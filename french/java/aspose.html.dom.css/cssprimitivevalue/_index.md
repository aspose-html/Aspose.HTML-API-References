---
title: "Classe CSSPrimitiveValue"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.css.CSSPrimitiveValue. L'interface CSSPrimitiveValue dérive de l'interface CSSValue et représente la valeur calculée actuelle d'une propriété CSS."
type: docs

url: /fr/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

L'interface CSSPrimitiveValue dérive de l'interface CSSValue et représente la valeur calculée actuelle d'une propriété CSS.

Remarque : Cette interface faisait partie d'une tentative de créer un modèle d'objet CSS typé. Cette tentative a été abandonnée, et la plupart des navigateurs ne l'implémentent pas.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Propriétés

| Nom | Description |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | La propriété cssText de l'interface [`CSSValue`](../cssvalue/) représente la valeur actuelle calculée de la propriété CSS. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Un code définissant le type de la valeur. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) Le type de la valeur tel que défini par les constantes spécifiées ci-dessus. |

## Méthodes

| Nom | Description |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Détermine si l'objet spécifié est égal à cette instance. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Cette méthode est utilisée pour obtenir la valeur du Counter. Si cette valeur CSS ne contient pas de valeur de compteur, une DOMException est levée. La modification de la propriété de style correspondante peut être effectuée à l'aide de l'interface Counter. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Cette méthode est utilisée pour obtenir une valeur flottante dans une unité spécifiée. Si cette valeur CSS ne contient pas de valeur flottante ou ne peut pas être convertie dans l'unité spécifiée, une DOMException est levée. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Renvoie un code de hachage pour cette instance. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Cette méthode est utilisée pour obtenir une valeur entière dans une unité spécifiée. Si cette valeur CSS ne contient pas de valeur entière ou ne peut pas être convertie dans l'unité spécifiée, une DOMException est levée. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Cette méthode est utilisée pour récupérer le type d'objet ECMAScript. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Cette méthode est utilisée pour obtenir la valeur Rect. Si cette valeur CSS ne contient pas de valeur rect, une DOMException est levée. La modification de la propriété de style correspondante peut être effectuée en utilisant l'interface Rect. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Cette méthode est utilisée pour obtenir la couleur RGB. Si cette valeur CSS ne contient pas de valeur de couleur RGB, une DOMException est levée. La modification de la propriété de style correspondante peut être effectuée en utilisant l'interface RGBColor. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Cette méthode est utilisée pour obtenir la valeur String. Si la valeur CSS ne contient pas de valeur String, une DOMException est levée. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Une méthode pour définir la valeur flottante avec une unité spécifiée. Si la propriété associée à cette valeur ne peut pas accepter l'unité spécifiée ou la valeur flottante, la valeur restera inchangée et une DOMException sera levée. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Une méthode pour définir la valeur entière avec une unité spécifiée. Si la propriété associée à cette valeur ne peut pas accepter l'unité spécifiée ou la valeur entière, la valeur restera inchangée et une DOMException sera levée. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | Une méthode pour définir la valeur String avec l'unité spécifiée. Si la propriété associée à cette valeur ne peut pas accepter l'unité spécifiée ou la valeur String, la valeur restera inchangée et une DOMException sera levée. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | La valeur est une fonction d'attribut. La valeur peut être obtenue en utilisant la méthode getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | La valeur est une longueur (ch). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | La valeur est une longueur (cm). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | La valeur est une fonction counter ou counters. La valeur peut être obtenue en utilisant la méthode GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | La valeur est un angle (deg). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | La valeur est un nombre avec une dimension inconnue. La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | La valeur est des points par centimètre (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | La valeur est des points par pouce (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | La valeur est des points par unité ‘px’ (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | La valeur est une longueur (ems). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | La valeur est une longueur (exs). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | La valeur est un angle (grad). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | La valeur est une fréquence (Hz). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | La valeur est un identifiant. La valeur peut être obtenue en utilisant la méthode getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | La valeur est une longueur (in). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | La valeur est une fréquence (kHz). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | La valeur est une longueur (mm). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | La valeur est un temps (ms). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | La valeur est un nombre simple. La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | La valeur est une longueur (pc). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | La valeur est un pourcentage. La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | La valeur est une longueur (pt). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | La valeur est une longueur (px). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | La valeur est un angle (rad). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | La valeur est une fonction rect. La valeur peut être obtenue en utilisant la méthode GetRectValue. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | La valeur est une longueur (rem). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | La valeur est une couleur RGB. La valeur peut être obtenue en utilisant la méthode GetRGBColorValue. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | La valeur est un temps (s). La valeur peut être obtenue en utilisant la méthode getFloatValue. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | La valeur est une STRING. La valeur peut être obtenue en utilisant la méthode getStringValue. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | La valeur n'est pas une valeur CSS2 reconnue. La valeur ne peut être obtenue qu'en utilisant l'attribut cssText. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | La valeur est une URI. La valeur peut être obtenue en utilisant la méthode getStringValue. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | La valeur est un pourcentage de la hauteur totale du viewport. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | La valeur est un pourcentage de la largeur ou de la hauteur du viewport, selon la plus grande. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | La valeur est un pourcentage de la largeur ou de la hauteur du viewport, selon la plus petite. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | La valeur est un pourcentage de la largeur totale du viewport. |

### Voir aussi

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
