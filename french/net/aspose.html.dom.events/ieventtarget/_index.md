---
title: Interface IEventTarget
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Events.IEventTarget interface. LeEventTarget est implémentée par tous les nœuds dans une implémentation qui prend en charge le modèle dévénement DOM. Par conséquent cette interface peut être obtenue en utilisant des méthodes de conversion spécifiques à la liaison sur une instance de linterface de nœud. Linterface permet lenregistrement et la suppression des écouteurs dévénement sur unEventTarget et lenvoi dévénements à ceIEventTarget .
type: docs
weight: 810
url: /fr/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Le[`EventTarget`](../../aspose.html.dom/eventtarget/) est implémentée par tous les nœuds dans une implémentation qui prend en charge le modèle d'événement DOM. Par conséquent, cette interface peut être obtenue en utilisant des méthodes de conversion spécifiques à la liaison sur une instance de l'interface de nœud. L'interface permet l'enregistrement et la suppression des écouteurs d'événement sur un[`EventTarget`](../../aspose.html.dom/eventtarget/) et l'envoi d'événements à ce`IEventTarget` .

```csharp
public interface IEventTarget
```

## Méthodes

| Nom | La description |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Cette méthode permet de répartir les événements dans le modèle d'événement des implémentations. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../ieventlistener/) est retiré d'un[`EventTarget`](../../aspose.html.dom/eventtarget/) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../ieventlistener/) est retiré d'un[`EventTarget`](../../aspose.html.dom/eventtarget/) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |

### Voir également

* espace de noms [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* Assemblée [Aspose.HTML](../../)


