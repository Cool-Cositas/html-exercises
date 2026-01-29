# Making the Layout

## HTML Layout

```html
<!DOCTYPE HTML>
<html lang="en">
    <head>
        <title>Clean and Gleam</title>
        <meta charset="utf-8">
        <meta name="keywords" content="">
        <meta name="description" content="My description">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <main>
            <header></header>
            <section></section>
            <footer></footer>
        </main>
    </body>
</html>

```

> From here on, I won't show the whole file, just from the body (takes a lotta space yk how it goes). <br>Here's how that would look like

```html
<main>
    <header></header>
    <section></section>
    <footer></footer>
</main>
```

Why did I add a `<main>` element? Well, we need some way to organise all the sections, and using `<main>` is the best choice for something like this (as it's the main content of the page)

Let's also add suitable classes

```html
<main class="grid-wrapper">
    <header class="header"></header>
    <section class="content"></section>
    <footer class="footer"></footer>
</main>
```

>`header` and `footer` don't exactly need a class, they're already a very specific element, as we wouldn't have multiple footers in one page. The same thing with `main`, usually there is only 1 main element in any website, but just to be in the safe side, I added a class to be more specific for the grid layout.

## CSS Styling

So that the page would be displayed properly, we'll use our css file to style the layout.

- First, we want to get rid of the margin that `<body>` has by default

- Next, we want both `<body>` and `<main>` to cover the whole page

- `<main>` should be displayed as a grid, with 3 rows. The first should be the minimum, the second should be automatic to fill rest of the space, and the third should be minimum, just like the first.

<br>

Try making these thingies yourself. Visual Studio Code has built-in auto-complete/hints (i believe it's <kbd>CTRL</kbd> + <kbd>Space</kbd> to activate it, but idk). 

Here's the HTML you would use for now (it's easier to see the layout)

And btw there's a little copy button to the right of the code, in case you didn't know
```html
<main class="grid-wrapper" style="background: #290000; padding: 20px; box-sizing: border-box; gap: 4px;">
    <header style="background: red;" class="header">Header</header>
    <section style="background: green;" class="content">Content</section>
    <footer style="background: blue;" class="footer">Footer</footer>
</main>
```

I'll remind you a couple things about CSS syntax

```css
selector {
    property: value;
    property: value;
}
```
Selector could be a mix of any of the following:
- `element`
- `.class`
- `#id`
- `[attribute]`

So this would be a valid selector: `main.grid-wrapper`

Define rows with `grid-template-rows: [values];`

## Gotchas to look out for
- With `<body>`, you can't just set the `height` or `width` to 100% (at least not reliably).

    - The correct way you would do this is using viewport relative measurements, like vw or vh.
    - `<main>` is fine with width and height being 100%, it's just `<body>` that has a problem.

___

This is what your layout should look like

<img src="assets/3-1css.png">

(Solution is in the next page)