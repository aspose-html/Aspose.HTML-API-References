---
title: "IEventTarget.AddEventListener"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IEventTarget. La méthode EventTarget addEventListener configure une fonction qui sera appelée chaque fois que l'événement spécifié est livré à la cible."
type: docs

url: /fr/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

La méthode addEventListener() de EventTarget configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible.

Les cibles courantes sont Element, Document et Window, mais la cible peut être tout objet qui prend en charge les événements (comme XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Une chaîne sensible à la casse représentant le type d'événement à écouter. |
| écouteur | IEventListener | Prend une interface implémentée par l'utilisateur qui contient les méthodes à appeler lorsque l'événement se produit. |

## Remarques

Si un est ajouté à un pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours mais pourra l'être lors d'une étape ultérieure du flux d'événement, comme la phase de bouillonnement. Si plusieurs écouteurs d'événements identiques sont enregistrés sur le même avec les mêmes paramètres, les instances dupliquées sont rejetées. Elles ne provoquent pas l'appel du deux fois et, comme elles sont rejetées, elles n'ont pas besoin d'être supprimées avec la méthode.

### Voir aussi

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

La méthode addEventListener() de EventTarget configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible.

Les cibles courantes sont Element, Document et Window, mais la cible peut être tout objet qui prend en charge les événements (comme XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Une chaîne sensible à la casse représentant le type d'événement à écouter. |
| écouteur | IEventListener | Prend une interface implémentée par l'utilisateur qui contient les méthodes à appeler lorsque l'événement se produit. |
| useCapture | Boolean | Si true, useCapture indique que l'utilisateur souhaite initier la capture. Après avoir initié la capture, tous les événements du type spécifié seront dispatchés aux enregistrements avant d'être dispatchés à tout Event Targets situé en dessous d'eux dans l'arbre. Les événements qui remontent par bouillonnement à travers l'arbre ne déclencheront pas un désigné pour utiliser la capture. |

## Remarques

Si un est ajouté à un pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours mais pourra l'être lors d'une étape ultérieure du flux d'événement, comme la phase de bouillonnement. Si plusieurs écouteurs d'événements identiques sont enregistrés sur le même avec les mêmes paramètres, les instances dupliquées sont rejetées. Elles ne provoquent pas l'appel du deux fois et, comme elles sont rejetées, elles n'ont pas besoin d'être supprimées avec la méthode.

### Voir aussi

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
