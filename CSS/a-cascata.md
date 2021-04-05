# A cascata (cascading)

* A escolha do browser de qual aplicar a regra, caso haja muitas regras para o mesmo elemento.

* Seu estilo é lido de cima para baixo

É levado em consideração 3 fatores:

1. Origem do estilo
2. Especificidade
3. Importância

### Origem do estilo (níveis de força)

inline > tag style > tag link

### Especificidade

É um calculo matemático, onde cada tipo de seletor e origem do estilo, possuem valores a serem considerados.

0. Universal selector(padrão para todos *), combinators e negation pseudo-class (:not())
1. Element type selector(id, div, ...) e pseudo-elements (::before, ::after)
10. Classes e attributes selectors ([type="radio"])
100. ID selector
1000. Inline

* exemplos:

```css
    /* Força 100 */
    #my-title {
        color:gray;
    }

    /* Força 10 */
    .title {
        color: red;
    }

    /* Força 2 */
    body h1 {
        color: blue;
    }

    /* Força 0 */
    * {
        color: green;
    }
    
```

### A regra !important
