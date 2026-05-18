---
title: "Classe FormEditor"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.forms.FormEditor class. Cette classe représente l'éditeur du HTMLFormElement qui offre une façon plus simple aux développeurs .net d'éditer les formulaires HTML."
type: docs

url: /fr/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Cette classe représente l'éditeur du [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) qui offre une façon plus simple aux développeurs .net d'éditer les formulaires HTML.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Propriétés

| Nom | Description |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) Le nombre de contrôles de formulaire dans le formulaire. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) Le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) original qui est associé à l'instance actuelle de `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Renvoie l'élément par l'index spécifié. (2 indexeurs) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Crée un nouveau `FormEditor` basé sur le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Crée un nouveau `FormEditor` basé sur le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) sélectionné dans la collection [`Forms`](../../com.aspose.html/htmldocument/forms/) par index. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Crée un nouveau `FormEditor` basé sur le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) sélectionné dans le document par id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Crée un nouveau [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) et l'associe à `FormEditor`. Le [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) est créé dans un état détaché du document ; pour l'attacher au document, veuillez sélectionner l'emplacement approprié et utiliser la méthode [`AppendChild`](../../com.aspose.html.dom/node/appendchild/). |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Crée un nouveau [`HTMLElement`](../../com.aspose.html/htmlelement/) et l'ajoute à la fin du formulaire. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Crée un nouveau [`InputElement`](../inputelement/) et l'ajoute à la fin du formulaire. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Crée un nouveau [`InputElement`](../inputelement/) et l'ajoute à la fin du formulaire. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Libère les ressources non gérées et gérées. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Renvoie l'élément par l'index spécifié. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Renvoie l'élément par le nom spécifié. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Obtient l'énumérateur. |

### Voir aussi

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
