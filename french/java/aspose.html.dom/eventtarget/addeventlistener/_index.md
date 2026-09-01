---
title: "EventTarget.AddEventListener"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode EventTarget. La méthode addEventListener de l'interface EventTarget configure une fonction qui sera appelée chaque fois que l'événement spécifié est livré à la cible"
type: docs

url: /fr/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible.

Cela fonctionne en ajoutant une fonction, ou un objet qui implémente [EventListener](T:com.aspose.html.dom.events.IEventListener), à la liste des écouteurs d'événements pour le type d'événement spécifié sur le EventTarget sur lequel il est appelé. Si la fonction ou l'objet est déjà présent dans la liste des écouteurs d'événements pour cette cible, ils ne sont pas ajoutés une seconde fois.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Le type d'événement pour lequel l'utilisateur s'inscrit |
| gestionnaire | DOMEventHandler | Prend un(e) à appeler lorsque l'événement se produit. |
| useCapture | Boolean | Si true, useCapture indique que l'utilisateur souhaite initier la capture. Après avoir initié la capture, tous les événements du type spécifié seront dispatchés aux enregistrements avant d'être dispatchés à tout Event Targets situé en dessous d'eux dans l'arbre. Les événements qui remontent par bouillonnement à travers l'arbre ne déclencheront pas un désigné pour utiliser la capture. |

## Remarques

Si un est ajouté à un pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours mais pourra l'être lors d'une étape ultérieure du flux d'événement, comme la phase de bouillonnement. Si plusieurs écouteurs d'événements identiques sont enregistrés sur le même avec les mêmes paramètres, les instances dupliquées sont rejetées. Elles ne provoquent pas l'appel du deux fois et, comme elles sont rejetées, elles n'ont pas besoin d'être supprimées avec la méthode.

### Voir aussi

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

La méthode addEventListener() de l'interface [`EventTarget `](../) configure une fonction qui sera appelée chaque fois que l'événement spécifié est livré à la cible.

Cela fonctionne en ajoutant une fonction, ou un objet qui implémente [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/), à la liste des écouteurs d'événements pour le type d'événement spécifié sur le EventTarget sur lequel il est appelé. Si la fonction ou l'objet est déjà présent dans la liste des écouteurs d'événements pour cette cible, ils ne sont pas ajoutés une seconde fois.

```java
public void AddEventListener(String type, IEventListener listener)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Le type d'événement pour lequel l'utilisateur s'inscrit |
| écouteur | IEventListener | Prend une interface implémentée par l'utilisateur qui contient les méthodes à appeler lorsque l'événement se produit. |

## Remarques

Si un est ajouté à un pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours mais pourra l'être lors d'une étape ultérieure du flux d'événement, comme la phase de bouillonnement. Si plusieurs écouteurs d'événements identiques sont enregistrés sur le même avec les mêmes paramètres, les instances dupliquées sont rejetées. Elles ne provoquent pas l'appel du deux fois et, comme elles sont rejetées, elles n'ont pas besoin d'être supprimées avec la méthode.

### Voir aussi

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

La méthode addEventListener() de l'interface [EventTarget ](T:com.aspose.html.dom.EventTarget) configure une fonction qui sera appelée chaque fois que l'événement spécifié est délivré à la cible.

Cela fonctionne en ajoutant une fonction, ou un objet qui implémente [EventListener](T:com.aspose.html.dom.events.IEventListener), à la liste des écouteurs d'événements pour le type d'événement spécifié sur le EventTarget sur lequel il est appelé. Si la fonction ou l'objet est déjà présent dans la liste des écouteurs d'événements pour cette cible, ils ne sont pas ajoutés une seconde fois.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Le type d'événement pour lequel l'utilisateur s'inscrit |
| écouteur | IEventListener | Prend une interface implémentée par l'utilisateur qui contient les méthodes à appeler lorsque l'événement se produit. |
| useCapture | Boolean | Si true, useCapture indique que l'utilisateur souhaite initier la capture. Après avoir initié la capture, tous les événements du type spécifié seront dispatchés aux enregistrements avant d'être dispatchés à tout Event Targets situé en dessous d'eux dans l'arbre. Les événements qui remontent par bouillonnement à travers l'arbre ne déclencheront pas un désigné pour utiliser la capture. |

## Remarques

Si un est ajouté à un pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours mais pourra l'être lors d'une étape ultérieure du flux d'événement, comme la phase de bouillonnement. Si plusieurs écouteurs d'événements identiques sont enregistrés sur le même avec les mêmes paramètres, les instances dupliquées sont rejetées. Elles ne provoquent pas l'appel du deux fois et, comme elles sont rejetées, elles n'ont pas besoin d'être supprimées avec la méthode.

### Voir aussi

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
