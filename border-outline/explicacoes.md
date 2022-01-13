## border ( e outline )

As bordas da baixa

- value: `<border-style>` | `<border-width>` | `<border-color>`
    - style: solid | dotted | dashed | double | groove | ridge | inset | outset
    - width: `<length>`
    - color: `<color>`

```css
div {
    /* shorthand */
    border-top: solid 2px; /* top | right | bottom | left */

    /* style */
    border: solid;

    /* width <length> | style */
    border: 2px dotted;

    /* style | color */
    border: outset #f33;

    /* width | style | color */
    border: medium dashed green;
}
```
https://developer.mozilla.org/en-US/docs/Web/CSS/border

### E outline?

- diferente em 4 sentidos:
    - não modifica o tamanho da caixa, pois não é parte do Box Model
    - Poderá ser diferente de retargular
    - Não permite ajuste individuais
    - Mais usado pelo user agent para acessibilidade