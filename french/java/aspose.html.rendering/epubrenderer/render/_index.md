---
title: "EpubRenderer.Render"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode EpubRenderer. Définit une méthode pour rendre plusieurs flux EPub dans un IDevice spécifique. Le rendu sera effectué une fois qu'il n'y a aucune opération réseau de chargement de ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié est écoulé."
type: docs

url: /fr/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Définit une méthode pour rendre plusieurs flux EPub dans un [`IDevice`](../../idevice/) spécifique. Le rendu sera effectué une fois qu'il n'y a aucune opération réseau de chargement de ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié est écoulé.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| timeout | TimeSpan | Un TimeSpan qui représente le nombre de millisecondes à attendre, ou un TimeSpan qui représente -1 milliseconde pour attendre indéfiniment. |
| documents | Stream[] | Les documents à rendre. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Définit une méthode pour rendre plusieurs documents EPub dans un [`IDevice`](../../idevice/) spécifique, en utilisant un jeton d'annulation pour demander l'annulation de l'opération.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| cancellationToken | CancellationToken | Un CancellationToken à observer pendant l'attente de l'achèvement de la tâche. |
| sources | Stream[] | Les documents EPub à rendre. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Rend le document EPub dans le [`IDevice`](../../idevice/) spécifié.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Rend le document EPub dans le [`IDevice`](../../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y a aucune opération réseau de chargement de ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié est écoulé.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Rend plusieurs documents EPub dans le [`IDevice`](../../idevice/) spécifié.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Rend plusieurs documents EPub dans le [`IDevice`](../../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y a aucune opération réseau de chargement de ressources, aucun minuteur actif, aucune tâche d'animation ou que le délai spécifié est écoulé.

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
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
