---
title: EpubRenderer.Render
second_title: Référence de l'API Aspose.HTML pour .NET
description: EpubRenderer méthode. Définit la méthode de rendu de plusieurs EPubStream s en spécifiqueIDevice . Le rendu sera effectué une fois quil ny aura plus dopérations réseau pour charger des ressources des minuteries actives des tâches danimation ou un délai dattente spécifié écoulé.
type: docs
weight: 20
url: /fr/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

Définit la méthode de rendu de plusieurs EPubStream s en spécifique[`IDevice`](../../idevice/) . Le rendu sera effectué une fois qu'il n'y aura plus d'opérations réseau pour charger des ressources, des minuteries actives, des tâches d'animation ou un délai d'attente spécifié écoulé.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| device | IDevice | Le périphérique de sortie. |
| timeout | TimeSpan | UNTimeSpan qui représente le nombre de millisecondes à attendre, ou unTimeSpan cela représente -1 milliseconde à attendre indéfiniment. |
| documents | Stream[] | Les documents à rendre. |

### Voir également

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* espace de noms [Aspose.Html.Rendering](../../epubrenderer/)
* Assemblée [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Rend le document EPub dans le format spécifié[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| device | IDevice | Le dispositif. |
| document | Stream | Le document. |
| configuration | Configuration | La configuration. |

### Voir également

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* espace de noms [Aspose.Html.Rendering](../../epubrenderer/)
* Assemblée [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Rend le document EPub dans le format spécifié[`IDevice`](../../idevice/) . Le rendu sera effectué une fois qu'il n'y aura plus d'opérations réseau pour charger des ressources, des minuteries actives, des tâches d'animation ou un délai d'attente spécifié écoulé.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| device | IDevice | Le dispositif. |
| document | Stream | Le document. |
| configuration | Configuration | La configuration. |
| timeout | TimeSpan | UNTimeSpan qui représente le nombre de millisecondes à attendre, ou unTimeSpan cela représente -1 milliseconde à attendre indéfiniment. |

### Voir également

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* espace de noms [Aspose.Html.Rendering](../../epubrenderer/)
* Assemblée [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Rend plusieurs documents EPub dans spécifié[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| device | IDevice | Le dispositif. |
| documents | IList`1 | LeIList de documents à rendre. |
| configuration | Configuration | La configuration. |

### Voir également

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* espace de noms [Aspose.Html.Rendering](../../epubrenderer/)
* Assemblée [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Rend plusieurs documents EPub dans spécifié[`IDevice`](../../idevice/) . Le rendu sera effectué une fois qu'il n'y aura plus d'opérations réseau pour charger des ressources, des minuteries actives, des tâches d'animation ou un délai d'attente spécifié écoulé.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| device | IDevice | Le dispositif. |
| documents | IList`1 | LeIList de documents à rendre. |
| configuration | Configuration | La configuration. |
| timeout | TimeSpan | UNTimeSpan qui représente le nombre de millisecondes à attendre, ou unTimeSpan cela représente -1 milliseconde à attendre indéfiniment. |

### Voir également

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* espace de noms [Aspose.Html.Rendering](../../epubrenderer/)
* Assemblée [Aspose.HTML](../../../)


