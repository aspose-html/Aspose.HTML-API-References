---
title: Class MutationObserver
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Mutations.MutationObserver classe. AMutationObserver objet peut être utilisé pour observer les mutations de larbre deNode .
type: docs
weight: 970
url: /fr/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

A`MutationObserver` objet peut être utilisé pour observer les mutations de l'arbre de[`Node`](../../aspose.html.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Construit un objet MutationObserver et définit son[`MutationCallback`](../mutationcallback/) à rappeler. Le rappel est invoqué avec une liste d'objets MutationRecord comme premier argument et l'objet construit MutationObserver comme deuxième argument. Il est appelé après que les nœuds se soient enregistrés auprès du!:Observe(Node, IMutationObserverInit) méthode, sont mutés. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | Empêche l'observateur d'observer les mutations. Jusqu'à ce que la méthode observe() soit à nouveau utilisée, le rappel de l'observateur ne sera pas invoqué. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Ordonne à l'agent utilisateur d'observer une cible donnée (un nœud) et de signaler toute mutation en fonction des critères donnés par les options (un objet). L'argument options permet de définir les options d'observation des mutations via les membres de l'objet. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Ordonne à l'agent utilisateur d'observer une cible donnée (un nœud) et de signaler toute mutation en fonction des critères donnés par les options (un objet). L'argument options permet de définir les options d'observation des mutations via les membres de l'objet. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | La méthode renvoie une copie de la file d'attente d'enregistrement, puis vide la file d'attente d'enregistrement. |

### Voir également

* class [DOMObject](../../aspose.html.dom/domobject/)
* espace de noms [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* Assemblée [Aspose.HTML](../../)


