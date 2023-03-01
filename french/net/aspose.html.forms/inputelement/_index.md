---
title: Class InputElement
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Forms.InputElement classe. LInputElement représente un wrapper associé à lHTMLInputElement.
type: docs
weight: 2980
url: /fr/net/aspose.html.forms/inputelement/
---
## InputElement class

L'InputElement représente un wrapper associé à l'HTMLInputElement.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | Obtient le type de l'élément. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | Représente l'attribut Id de l'élément d'entrée. |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | Représente une liste d'options |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | Représente l'attribut de nom de l'élément d'entrée. |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | Type du champ de formulaire. |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | Représente la valeur de chaîne de l'élément d'entrée directement mappé à l'attribut 'value'. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | Cette méthode ajoute des fichiers au[`Files`](../../aspose.html/htmlinputelement/files/) collection qui sera envoyée lors de la prochaine requête web. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | Renvoie l'état de vérification pour l'élément d'entrée avec le type de case à cocher . |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | Cette méthode est utilisée pour obtenir la valeur sous forme de couleur. Cette méthode est valide si seul le type de l'élément d'entrée est "color" |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | Cette méthode est utilisée pour obtenir la valeur sous forme deDateTime objet Objet. Cette méthode est valide si seul le type de l'élément d'entrée est "datetime-local" |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | Cette méthode est utilisée pour obtenir la valeur sous forme deDateTime objet. Cette méthode est valide si seul le type de l'élément d'entrée est "date" |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | Cette méthode est utilisée pour obtenir la valeur en tant qu'objet de chaîne d'e-mail. Cette méthode est valide si seul le type de l'élément d'entrée est "email" |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | Cette méthode est utilisée pour obtenir la valeur sous forme deDateTime objet. Cette méthode est valide si seul le type de l'élément d'entrée est "mois" |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | Cette méthode est utilisée pour obtenir la valeur sous forme de nombre. Cette méthode est valide si seul le type de l'élément d'entrée est "number" |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | Cette méthode est utilisée pour obtenir la valeur en tant qu'objet de chaîne de mot de passe. Cette méthode est valide si seul le type de l'élément d'entrée est "password" |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | Renvoie l'état de vérification pour l'élément d'entrée avec le type radio. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | Cette méthode est utilisée pour obtenir la valeur sous forme deTimeSpan objet. Cette méthode est valide si seul le type de l'élément d'entrée est "time" |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | Cette méthode est utilisée pour obtenir la valeur comme[`Url`](../../aspose.html/url/) objet. Cette méthode est valide si seul le type de l'élément d'entrée est "url" |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | Cette méthode est utilisée pour obtenir la valeur sous forme de chaîne de semaine. Cette méthode est valide si seul le type de l'élément d'entrée est "semaine" |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | Définit l'état de vérification pour l'élément d'entrée avec le type de case à cocher. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | Cette méthode est utilisée pour définir la couleur comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "color" |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | Cette méthode est utilisée pour définirDateTimeobjet comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "datetime-local" |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | Cette méthode est utilisée pour définirDateTime objet comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "date" |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | Cette méthode est utilisée pour définir la chaîne de courrier électronique comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "email" |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | Cette méthode est utilisée pour définirDateTimeobjet comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "mois" |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | Cette méthode est utilisée pour définir le nombre comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "numéro" |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | Cette méthode est utilisée pour définir la chaîne de mot de passe comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "password" |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | Définit l'état de vérification pour l'élément d'entrée avec le type radio. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | Cette méthode est utilisée pour définirTimeSpan objet comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "time" |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | Cette méthode est utilisée pour définir[`Url`](../../aspose.html/url/) objet comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "url" |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | Cette méthode est utilisée pour définir la chaîne 'week' comme valeur pour l'élément d'entrée. Cette méthode est valide si seul le type de l'élément d'entrée est "semaine" |

### Voir également

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* espace de noms [Aspose.Html.Forms](../../aspose.html.forms/)
* Assemblée [Aspose.HTML](../../)


