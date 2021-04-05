# Adicionando CSS

## Inline

* atributo `style`

```html
<h1 style="color: blue">
    In
    <strong style="color: red">line</strong>
</h1>
```

## <style>

* tag html que irá conter o css

```html
 <style>

    /* No head da página */
    body {
        background: #000;
    }
</style>
```

## <link>

* arquivo css externo 

```html
<!-- No head da página html -->
<link rel="stylesheet" href="style.css">
```

## @import

* arquivo css externo

```css
/* Em um arquivo .css */
@import url('https://fonts.googleapis.com/css2?family=Dela+Gothic+One&display=swap');

/* Para usar, exemplo */

* {
    font-family: 'Dela Gothic One', cursive;
}
```

