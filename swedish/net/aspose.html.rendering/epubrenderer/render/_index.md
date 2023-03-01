---
title: EpubRenderer.Render
second_title: Aspose.HTML för .NET API Referens
description: EpubRenderer metod. Definierar metod för att rendera flera EPubStream är i specifikaIDevice . Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser aktiva timers animeringsuppgifter eller specificerad timeout har förflutit.
type: docs
weight: 20
url: /sv/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

Definierar metod för att rendera flera EPubStream är i specifika[`IDevice`](../../idevice/) . Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animeringsuppgifter eller specificerad timeout har förflutit.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utmatningsenheten. |
| timeout | TimeSpan | ATimeSpan som representerar antalet millisekunder att vänta, eller aTimeSpan som representerar -1 millisekund för att vänta på obestämd tid. |
| documents | Stream[] | Dokumenten som ska återges. |

### Se även

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* namnutrymme [Aspose.Html.Rendering](../../epubrenderer/)
* hopsättning [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Återger EPub-dokument till specificerat[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Enheten. |
| document | Stream | Dokumentet. |
| configuration | Configuration | Konfigurationen. |

### Se även

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* namnutrymme [Aspose.Html.Rendering](../../epubrenderer/)
* hopsättning [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Återger EPub-dokument till specificerat[`IDevice`](../../idevice/) . Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animeringsuppgifter eller specificerad timeout har förflutit.

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Enheten. |
| document | Stream | Dokumentet. |
| configuration | Configuration | Konfigurationen. |
| timeout | TimeSpan | ATimeSpan som representerar antalet millisekunder att vänta, eller aTimeSpan som representerar -1 millisekund för att vänta på obestämd tid. |

### Se även

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* namnutrymme [Aspose.Html.Rendering](../../epubrenderer/)
* hopsättning [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Återger flera EPub-dokument till specificerade[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Enheten. |
| documents | IList`1 | DeIList av dokument att återge. |
| configuration | Configuration | Konfigurationen. |

### Se även

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* namnutrymme [Aspose.Html.Rendering](../../epubrenderer/)
* hopsättning [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Återger flera EPub-dokument till specificerade[`IDevice`](../../idevice/) . Renderingen kommer att utföras när det inte finns några nätverksoperationer för att ladda resurser, aktiva timers, animeringsuppgifter eller specificerad timeout har förflutit.

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Enheten. |
| documents | IList`1 | DeIList av dokument att återge. |
| configuration | Configuration | Konfigurationen. |
| timeout | TimeSpan | ATimeSpan som representerar antalet millisekunder att vänta, eller aTimeSpan som representerar -1 millisekund för att vänta på obestämd tid. |

### Se även

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* namnutrymme [Aspose.Html.Rendering](../../epubrenderer/)
* hopsättning [Aspose.HTML](../../../)


