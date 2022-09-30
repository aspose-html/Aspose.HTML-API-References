---
title: AddEventListener
second_title: Référence de l'API Aspose.HTML pour .NET
description: Cette méthode permet lenregistrement des écouteurs dévénement sur la cible de lévénement.
type: docs
weight: 10
url: /fr/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Le type d'événement pour lequel l'utilisateur s'inscrit |
| handler | DOMEventHandler | Prend un[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler) à appeler lorsque l'événement se produit. |
| useCapture | Boolean | Si vrai, useCapture indique que l'utilisateur souhaite lancer la capture. Après avoir lancé la capture, tous les événements du type spécifié seront distribués à l'enregistré [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) avant d'être envoyés à des cibles d'événements en dessous d'eux dans l'arborescence. Les événements qui bouillonnent vers le haut dans l'arborescence ne déclencheront pas de[`IEventListener`](../../../aspose.html.dom.events/ieventlistener) désigné pour utiliser la capture. |

### Remarques

Si un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener) est ajouté à un[`EventTarget`](../../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours, mais peut être déclenché lors d'une étape ultérieure du flux d'événements, comme la phase de bouillonnement.

Si plusieurs Event Listeners identiques sont enregistrés sur le même[`EventTarget`](../../eventtarget)avec les mêmes paramètres, les instances en double sont rejetées. Elles ne provoquent pas la[`IEventListener`](../../../aspose.html.dom.events/ieventlistener) pour être appelés deux fois et puisqu'ils sont jetés, ils n'ont pas besoin d'être supprimés avec the [`RemoveEventListener`](../removeeventlistener) méthode.

### Voir également

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler)
* class [EventTarget](../../eventtarget)
* espace de noms [Aspose.Html.Dom](../../eventtarget)
* Assemblée [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Le type d'événement pour lequel l'utilisateur s'inscrit |
| listener | IEventListener | Prend une interface implémentée par l'utilisateur qui contient les méthodes à appeler lorsque l'événement se produit. |

### Remarques

Si un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener) est ajouté à un[`EventTarget`](../../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours, mais peut être déclenché lors d'une étape ultérieure du flux d'événements, comme la phase de bouillonnement.

Si plusieurs Event Listeners identiques sont enregistrés sur le même[`EventTarget`](../../eventtarget)avec les mêmes paramètres, les instances en double sont rejetées. Elles ne provoquent pas la[`IEventListener`](../../../aspose.html.dom.events/ieventlistener) pour être appelés deux fois et puisqu'ils sont jetés, ils n'ont pas besoin d'être supprimés avec the [`RemoveEventListener`](../removeeventlistener) méthode.

### Voir également

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* espace de noms [Aspose.Html.Dom](../../eventtarget)
* Assemblée [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| type | String | Le type d'événement pour lequel l'utilisateur s'inscrit |
| listener | IEventListener | Prend une interface implémentée par l'utilisateur qui contient les méthodes à appeler lorsque l'événement se produit. |
| useCapture | Boolean | Si vrai, useCapture indique que l'utilisateur souhaite lancer la capture. Après avoir lancé la capture, tous les événements du type spécifié seront distribués à l'enregistré [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) avant d'être envoyés à des cibles d'événements en dessous d'eux dans l'arborescence. Les événements qui bouillonnent vers le haut dans l'arborescence ne déclencheront pas de[`IEventListener`](../../../aspose.html.dom.events/ieventlistener) désigné pour utiliser la capture. |

### Remarques

Si un[`IEventListener`](../../../aspose.html.dom.events/ieventlistener) est ajouté à un[`EventTarget`](../../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours, mais peut être déclenché lors d'une étape ultérieure du flux d'événements, comme la phase de bouillonnement.

Si plusieurs Event Listeners identiques sont enregistrés sur le même[`EventTarget`](../../eventtarget)avec les mêmes paramètres, les instances en double sont rejetées. Elles ne provoquent pas la[`IEventListener`](../../../aspose.html.dom.events/ieventlistener) pour être appelés deux fois et puisqu'ils sont jetés, ils n'ont pas besoin d'être supprimés avec the [`RemoveEventListener`](../removeeventlistener) méthode.

### Voir également

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* espace de noms [Aspose.Html.Dom](../../eventtarget)
* Assemblée [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
