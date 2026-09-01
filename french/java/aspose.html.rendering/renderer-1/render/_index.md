---
title: "Renderer-1.Render"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Renderer. Définit une méthode pour rendre TDocument dans un IDevice spécifié"
type: docs

url: /fr/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Définit une méthode pour rendre !:TDocument dans un [`IDevice`](../../idevice/) spécifié.

```java
public void Render(IDevice device, TSource source)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| document | TSource | Le document. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Définit une méthode pour rendre !:TDocument dans un [`IDevice`](../../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, les minuteries actives, les tâches d'animation ou que le délai spécifié sera écoulé.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| document | TSource | Le document. |
| timeout | TimeSpan | Un TimeSpan qui représente le nombre de millisecondes à attendre, ou un TimeSpan qui représente -1 milliseconde pour attendre indéfiniment. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Définit une méthode pour rendre !:TDocument dans un [`IDevice`](../../idevice/) spécifié. Le rendu sera effectué une fois qu'il n'y aura aucune opération réseau pour le chargement des ressources, les minuteries actives, les tâches d'animation ou que le délai spécifié sera écoulé.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| document | TSource | Le document. |
| timeout | Int32 | Un nombre de millisecondes qui représente le nombre de millisecondes à attendre, ou -1 milliseconde pour attendre indéfiniment. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### Voir aussi

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
