---
title: Class FormEditor
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Forms.FormEditor classe. Cette classe représente léditeur sur leHTMLFormElement qui crée un moyen plus simple pour les développeurs .net de modifier les formulaires html.
type: docs
weight: 2930
url: /fr/net/aspose.html.forms/formeditor/
---
## FormEditor class

Cette classe représente l'éditeur sur le[`HTMLFormElement`](../../aspose.html/htmlformelement/) qui crée un moyen plus simple pour les développeurs .net de modifier les formulaires html.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Gestionnaire de formulaires côté serveur. Voir la définition de l'attribut d'action dans HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Le nombre de contrôles de formulaire dans le formulaire. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | L'original[`HTMLFormElement`](../../aspose.html/htmlformelement/) qui est associé à l'instance actuelle de`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Renvoie l'élément par l'index spécifié. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | méthode HTTP [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) utilisé pour soumettre le formulaire. Voir la définition de l'attribut method dans HTML 4.01. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Crée un nouveau`FormEditor` basé sur[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Crée un nouveau`FormEditor` basé sur[`HTMLFormElement`](../../aspose.html/htmlformelement/) sélectionné parmi les[`Forms`](../../aspose.html/htmldocument/forms/) collection par index. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Crée un nouveau`FormEditor` basé sur[`HTMLFormElement`](../../aspose.html/htmlformelement/) sélectionné dans le document par id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Crée un nouveau[`HTMLFormElement`](../../aspose.html/htmlformelement/) et l'a associé à`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) est créé dans l'état détaché du document ; afin de le joindre au document, veuillez sélectionner l'emplacement et l'utilisation appropriés[`AppendChild`](../../aspose.html.dom/node/appendchild/) méthode. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Crée un nouveau[`HTMLElement`](../../aspose.html/htmlelement/) et l'ajoute à la fin du formulaire. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Crée un nouveau[`InputElement`](../inputelement/) et l'ajoute à la fin du formulaire. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Crée un nouveau[`InputElement`](../inputelement/) et l'ajoute à la fin du formulaire. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Libère les ressources non gérées et gérées. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Cette méthode remplit tout le formulaire avec les valeurs spécifiées. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Renvoie l'élément par l'index spécifié. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Renvoie l'élément par le nom spécifié. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Obtient l'énumérateur. |

### Voir également

* class [FormElement](../formelement/)
* espace de noms [Aspose.Html.Forms](../../aspose.html.forms/)
* Assemblée [Aspose.HTML](../../)


