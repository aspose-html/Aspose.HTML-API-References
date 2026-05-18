---
title: "Classe MutationObserver"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.mutations.MutationObserver class. Un objet peut être utilisé pour observer les mutations de l'arbre de"
type: docs

url: /fr/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

Un objet peut être utilisé pour observer les mutations de l'arbre de [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | Construit un objet MutationObserver et définit son [`MutationCallback`](../mutationcallback/) comme rappel. Le rappel est invoqué avec une liste d'objets MutationRecord comme premier argument et l'objet MutationObserver construit comme second argument. Il est invoqué après que les nœuds enregistrés avec la méthode !:Observe(Node, IMutationObserverInit) aient été mutés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | Arrête l'observateur d'observer toute mutation. Jusqu'à ce que la méthode observe() soit à nouveau utilisée, le rappel de l'observateur ne sera pas invoqué. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | Ordonne à l'agent utilisateur d'observer une cible donnée (un nœud) et de signaler toute mutation selon les critères fournis par les options (un objet). L'argument options permet de définir les options d'observation des mutations via les membres de l'objet. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | Ordonne à l'agent utilisateur d'observer une cible donnée (un nœud) et de signaler toute mutation selon les critères fournis par les options (un objet). L'argument options permet de définir les options d'observation des mutations via les membres de l'objet. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | La méthode renvoie une copie de la file d'attente des enregistrements puis vide cette file d'attente. |

### Voir aussi

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
