---
title: "IMediaList 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.css.IMediaList 인터페이스. MediaList 인터페이스는 컬렉션이 어떻게 구현되는지를 정의하거나 제한하지 않고, 순서가 있는 미디어 컬렉션의 추상화를 제공합니다. 빈 리스트는 모든 매체를 포함하는 리스트와 동일합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList 인터페이스는 이 컬렉션이 어떻게 구현되는지를 정의하거나 제한하지 않고, 미디어의 순서가 있는 컬렉션 추상화를 제공합니다. 빈 리스트는 미디어 \"all\"을 포함하는 리스트와 동일합니다.

또한 [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface)를 참조하십시오.

```java
public interface IMediaList : IEnumerable<String>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) item(index) 메서드는 지정된 인덱스에 해당하는 미디어 쿼리 컬렉션의 직렬화를 반환해야 하며, 인덱스가 컬렉션의 미디어 쿼리 수보다 크거나 같으면 null을 반환합니다. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) length 속성은 미디어 쿼리 컬렉션에 포함된 미디어 쿼리의 수를 반환해야 합니다. 유효한 미디어의 범위는 0부터 length-1까지(포함)입니다. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) MediaList를 텍스트로 나타내는 DOMString을 반환하는 Stringifier이며, 새로운 MediaList를 설정할 수도 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | 새로운 매체 newMedium를 리스트 끝에 추가합니다. newMedium가 이미 사용 중이면 먼저 제거됩니다. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | oldMedium으로 지정된 매체를 리스트에서 삭제합니다. |

## 비고

참고: MediaList는 실시간 리스트이며, 아래에 나열된 속성이나 메서드를 사용해 리스트를 업데이트하면 문서의 동작이 즉시 업데이트됩니다.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## 예제

다음 코드는 현재 문서에 적용된 첫 번째 스타일시트의 MediaList 텍스트 표현을 콘솔에 로그합니다.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### 또 보기

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
