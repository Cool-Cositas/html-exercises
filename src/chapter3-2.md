# Layout CSS

```css
body {
    margin: 0;
    width: 100vw;
    height: 100vh;
}

main {
    width: 100%;
    height: 100%;
    display: grid;
    grid-template-rows: min-content auto min-content;
}
```

Got rid of the margins in `body`, and made it cover the whole screen

Added 3 rows to the grid. `min-content` will try to shrink that element as much as it can. `auto` will try expand that element as much as it can.

If you don't like your site looking like an Alex Turner presentation, then you can go back to your old HTML structure

```html
<main class="grid-wrapper">
    <header></header>
    <section class="content"></section>
    <footer></footer>
</main>
```