# Comentário

* Não irá afetar o seu código
* Ajuda a lembrar todos os blocos de código
* Deixa dicas para a leitura
* Ajuda outros a entenderem
* Nunca esqueça de fechar um cometário aberto

Comentários começam com `/*` e terminam com `*/`.

```css
/*Básico*/
/* --------------------------- */

body {
    font:1em/150;
    padding: 1em;
    margin: 0 auto;
    max-width: 33em;
}

@media (min-width: 70%) {
    /* Let's special case the global fony-size. On large screen or window, we increse the font size for better readability*/
    body {
        font-size: 130;
    }

    /* Elementos específicos */
    div p + p {
        margin: 0;
        padding: 1em;
    }
}
```
  
* Você poderá utilizar para desabilitar partes do seu código

```css
    /*
    .special {
        color: gray;
    }
    */

    p {
        color: red;
    }
```