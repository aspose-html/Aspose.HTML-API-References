---
title: "MhtmlRenderer.Render"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode MhtmlRenderer. Rend plusieurs documents MHTML dans un IDevice spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, les minuteries actives, les tâches d'animation ou que le délai spécifié sera écoulé"
type: docs

url: /fr/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Rend plusieurs documents MHTML dans un [`IDevice`](../../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, les minuteries actives, les tâches d'animation ou que le délai spécifié sera écoulé.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif. |
| timeout | TimeSpan | Un TimeSpan qui représente le nombre de millisecondes à attendre, ou un TimeSpan qui représente -1 milliseconde pour attendre indéfiniment. |
| documents | Stream[] | Les documents à rendre. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Définit une méthode pour rendre plusieurs documents MHTML dans un [`IDevice`](../../idevice/) spécifique, en utilisant un jeton d'annulation pour demander l'annulation de l'opération.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| cancellationToken | CancellationToken | Un CancellationToken à observer pendant l'attente de l'achèvement de la tâche. |
| sources | Stream[] | Les documents MHTML à rendre. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Rend le document MHTML dans le [`IDevice`](../../idevice/) spécifié.

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif. |
| document | Flux | Le document. |
| configuration | Configuration | La configuration. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Rend le document MHTML dans le [`IDevice`](../../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour charger des ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai d'attente spécifié sera écoulé.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif. |
| document | Flux | Le document. |
| configuration | Configuration | La configuration. |
| timeout | TimeSpan | Un TimeSpan qui représente le nombre de millisecondes à attendre, ou un TimeSpan qui représente -1 milliseconde pour attendre indéfiniment. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Rend plusieurs documents MHTML dans le [`IDevice`](../../idevice/) spécifié.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif. |
| documents | IList`1 | La IList des documents à rendre. |
| configuration | Configuration | La configuration. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Rend plusieurs documents MHTML dans un [`IDevice`](../../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, les minuteries actives, les tâches d'animation ou que le délai spécifié sera écoulé.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif. |
| documents | IList`1 | La IList des documents à rendre. |
| configuration | Configuration | La configuration. |
| timeout | TimeSpan | Un TimeSpan qui représente le nombre de millisecondes à attendre, ou un TimeSpan qui représente -1 milliseconde pour attendre indéfiniment. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
