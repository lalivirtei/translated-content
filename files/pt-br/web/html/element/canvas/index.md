---
title: canvas
slug: Web/HTML/Element/canvas
translation_of: Web/HTML/Element/canvas
---
## Sumário

O elemento HTML _Canvas_ (`<canvas>`) pode ser utilizado para desenhar gráficos utilizando scripts (geralmente [JavaScript](/en/JavaScript "en/JavaScript")). Por exemplo, além de desenhar gráficos, ele pode ser usado para fazer composições de fotos e também para animações. Você poderá colocar conteúdos alternativos dentro do bloco `<canvas>`. Este conteúdo será renderizado também em navegadores antigos e em navegadores com JavaScript desabilitado.

Para mais artigos sobre canvas, veja [canvas topic page](/en/HTML/Canvas "en/HTML/Canvas").

## Contexto de uso

| Conteúdo permitido         | Transparente, tanto [phrasing content](/en/HTML/Content_categories#phrasing_content "en/HTML/Content categories#phrasing content") ou [flow content](/en/HTML/Content_categories#flow_content "en/HTML/Content categories#flow content").          |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Omissão de tags            | Nenhuma, tanto a tag de início quanto a de fim devem ser incluídas.                                                                                                                                                                                |
| Elementos "pai" permitidos | Qualquer elemento que aceite [phrasing content](/en/HTML/Content_categories#phrasing_content "en/HTML/Content categories#phrasing content") ou [flow content](/en/HTML/Content_categories#flow_content "en/HTML/Content categories#flow content"). |
| Documento normativo        | [HTML 5, section 4.8.10](http://www.w3.org/TR/html5/the-canvas-element.html#the-canvas-element)                                                                                                                                                    |

## Atributos

Como qualquer outro elemento HTML, este também tem [global attributes](/en/HTML/Global_attributes "en/HTML/Global attributes").

- {{ htmlattrdef("width") }}
  - : A largura do espaço em pixels CSS. O padrão é 300.
- {{ htmlattrdef("height") }}
  - : A altura do espaço em pixels CSS. O padrão é 150.

{{ Note("The displayed size of the canvas can be changed using a stylesheet. The image is scaled during rendering to fit the styled size.") }}

## Interface DOM

- [HTMLCanvasElement](/en/DOM/HTMLCanvasElement "en/DOM/HTMLCanvasElement")

## Exemplo

```html
<canvas id="canvas" width="300" height="300">
  Desculpe-me, seu navegador não suporta o elemento &lt;canvas&gt;.
</canvas>
```

## Compatibilidade com navegadores

{{Compat("html.elements.canvas")}}

## Veja também

- [MDN canvas portal](/en/HTML/Canvas "https://developer.mozilla.org/en/HTML/Canvas")
- Um [canvas tutorial](/en/Canvas_tutorial "Canvas tutorial")
- [Canvas cheat sheet](http://blog.nihilogic.dk/2009/02/html5-canvas-cheat-sheet.html)
- [Canvas-related demos](/en-US/demos/tag/tech:canvas "https://developer.mozilla.org/en-US/demos/tag/tech:canvas/")

{{ languages( { "de": "de/HTML/Element/canvas", "en": "en/HTML/Element/canvas", "es": "es/HTML/Elemento/canvas", "ja": "ja/HTML/Element/canvas", "ko": "ko/HTML/Element/canvas", "nl": "nl/HTML/HTML\_Tags/canvas", "pl": "pl/HTML/Element/canvas", "ru": "Ru/HTML/Element/canvas", "zh-cn": "cn/HTML/Element/canvas", "fr": "fr/HTML/Element/canvas" } ) }}