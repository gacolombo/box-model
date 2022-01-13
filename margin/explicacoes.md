## margin

Espaços entre os elementos

— margin-top | margin-right | margin-bottom | margin-left
— values `<length>` | `<percentage>` | auto

```css
div{
    /* shorthand */
    /*sentido horario: top, right, bottom e left quando tem 4 elementos*/
    margin: 12px 16px 10px 4px;
    /*3 elementos: top, laterias e bottom*/
    margin: 12px 16px 0;
    /*2 elementos: top e bottom > laterais*/
    margin: 8px 16px;
    /*1 unico elemento: todos os 4 lados com a mesma margem*/
    margin: 8px;
}
```

    * Cuidado com margin collapsing (top se junta ao bottom )