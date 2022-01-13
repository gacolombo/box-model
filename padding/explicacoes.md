
## padding

Preenchimento interno da caixa

- padding-top | padding-right | padding-bottom | padding-left
- values: `<length>` | `<percentage>` | auto

```css
div{
    /*shorthand*/
    /*sentido horario: top, right, bottom e left quando tem 4 elementos*/
    padding: 12px 16px 10px 4px;
    /*3 elementos: top, laterias e bottom*/
    padding: 12px 16px 0;
    /*2 elementos: top e bottom > laterais*/
    padding: 8px 16px;
    /*1 unico elemento: todos os 4 lados com a mesma margem*/
    padding: 8px;
}
```

    * Padding poderá causar diferença na largura de um elemento