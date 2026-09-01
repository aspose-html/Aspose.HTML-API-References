---
title: "HtmlRenderer.Render"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode HtmlRenderer. Définit la méthode de rendu de plusieurs HTMLDocuments dans un IDevice spécifique"
type: docs

url: /fr/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

Définit la méthode de rendu de plusieurs [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s dans un [`IDevice`](../../idevice/) spécifique.

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| timeout | TimeSpan | Un TimeSpan qui représente le nombre de millisecondes à attendre, ou un TimeSpan qui représente -1 milliseconde pour attendre indéfiniment. |
| sources | HTMLDocument[] | Les documents HTML à rendre. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

Définit une méthode de rendu de plusieurs [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s dans un [`IDevice`](../../idevice/) spécifique, en utilisant un jeton d'annulation pour demander l'annulation de l'opération.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dispositif | IDevice | Le dispositif de sortie. |
| cancellationToken | CancellationToken | Un CancellationToken à observer pendant l'attente de l'achèvement de la tâche. |
| sources | HTMLDocument[] | Les documents HTML à rendre. |

### Voir aussi

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
