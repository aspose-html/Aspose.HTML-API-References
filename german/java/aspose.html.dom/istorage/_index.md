---
title: "IStorage Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.IStorage Schnittstelle. Dieses Interface der Web Storage API bietet Zugriff auf die Sitzungs- oder lokalen Speicher eines bestimmten Domänen. Siehe Web Storage Spezifikation https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /de/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Dieses Interface der Web‑Storage‑API bietet Zugriff auf die Sitzungs‑ oder Local‑Storage eines bestimmten Domänen. Siehe die Web‑Storage‑Spezifikation: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Gibt die Anzahl der Schlüssel/Wert-Paare zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Entfernt alle Schlüssel/Wert-Paare, falls vorhanden. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Gibt den aktuellen Wert zurück, der dem angegebenen Schlüssel zugeordnet ist, oder null, wenn der angegebene Schlüssel nicht existiert. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Gibt den Namen des n‑ten Schlüssels zurück, oder null, wenn n größer oder gleich der Anzahl der Schlüssel/Wert-Paare ist. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Entfernt das Schlüssel/Wert-Paar mit dem angegebenen Schlüssel, falls ein solches Paar existiert. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Setzt den Wert des durch den Schlüssel identifizierten Paares auf value und erstellt ein neues Schlüssel/Wert-Paar, falls zuvor keines für den Schlüssel existierte. |

### Siehe auch

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
