---
title: Class MutationRecord
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Mutations.MutationRecord klass. En MutationRecord representerar en individuell DOMmutation. Det är föremålet som skickas tillMutationObserver sMutationCallback .
type: docs
weight: 990
url: /sv/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

En MutationRecord representerar en individuell DOM-mutation. Det är föremålet som skickas till[`MutationObserver`](../mutationobserver/) s[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | Returnera noderna som lagts till. |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | Returnerar det lokala namnet på det ändrade attributet och null annars. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | Returnerar namnutrymmet för det ändrade attributet och null annars. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | Returnera nästa syskon till de tillagda eller borttagna noderna, eller null. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | Returvärdet beror på typ. För "attribut" är det värdet på det ändrade attributet före ändringen. För "characterData" är det data från den ändrade noden före ändringen. För "childList" är det null. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | Returnerar föregående syskon till de tillagda eller borttagna noderna, eller null. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | Returnera noderna borttagna. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | Returnerar noden som mutationen påverkade, beroende på typen. För "attribut" är det elementet vars attribut ändrades. För "characterData" är det CharacterData-noden. För "childList" är det noden vars barn har ändrats. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | Returnerar "attribut" om det var en attributmutation, "characterData" om det var en mutation till en CharacterData-nod och "childList" om det var en mutation till nodträdet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |

### Se även

* class [DOMObject](../../aspose.html.dom/domobject/)
* namnutrymme [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* hopsättning [Aspose.HTML](../../)


