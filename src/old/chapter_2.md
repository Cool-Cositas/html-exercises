# Structural Markup

**10)** Which is an example of a Block element display?

```
A)  ▀▀▀▀▀▀▀▀▀▀▀
    ▀▀▀▀▀▀▀▀▀▀▀
    ▀▀▀▀▀▀▀▀▀▀▀
```
```
B)  ███████████ ███████████ ███████████
```
```
C)  ▀▀▀▀▀▀▀▀▀▀▀ ▀▀▀▀▀▀▀▀▀▀▀
    ▀▀▀▀▀▀▀▀▀▀▀ ▀▀▀▀▀▀▀▀▀▀▀
```

___

## Semantic Elements

**11)** When should you use `aside`, `article` and `strong`?

**12)** How does semantic markup help with accessibility?

**13)** What does SEO stand for? Why is it so important for websites?

**14)** Choose suitable semantic elements (one is repeated):

``` html
<!doctype HTML>
<html lang="en">
<body>
    <___>
        <h1>Your Local News</h1>
        <h2>Brought to you by Kasane Teto</h2>
    </___>
    <___>
        <h2>In the news this week:</h2>
        <p>
            <a href="#article1">Changes in bus times</a><br>
            <a href="#article2">What should the speed limit be in town?</a><br>
        </p>
        <hr>
    </___>
    <___ id="article1">
        <h2>Big changes in bus times</h2>
        <p>
            All bus timetables will be changing next 
            month. There will be fewer buses late at 
            night and on Sundays.
        </p>
    </___>
    <___ id="article2">
        <h2>What should the speed limit be in town?</h2>
        <p>
            There is currently a consultation about 
            reducing the spede limit in town. You can 
            give your opinion on the official town 
            hall website.
        </p>
    </___>
    <___>
        <p>Contact us: 
            <a href="mailto:fakeass@email.com">real@email.com</a>
        </p>
</body>
</html>
```

>`<article>`

>`<section>`

>`<footer>`

>`<heading>`