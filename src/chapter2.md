# Setting Up
All HTML files follow a simple structure.

They first start by declaring what type of document it is

`<!DOCTYPE HTML>`

Next you add opening and closing tags to describe your html content. It’s a good idea to add a language attribute so the web browser can detect what language it is

```html
<!DOCTYPE HTML>
<html lang="en">
  <head></head>
  <body></body>
</html>
```
This is the general structure you will use when writing HTML files

You should add `<title>` in `<meta>` tags in the `<head>` . Title is shown at the top of the browser window, and meta provides information about the page which can help web browser display data and search engines to know what the site is about. 

```html
<title>My Website</title>
<meta charset="utf-8">
<meta name="keywords" content="">
<meta name="description" content="My description">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

___

You should have something that looks like this

```html
<!DOCTYPE HTML>
<html lang="en">
  <head>
    <title>My Website</title>
    <meta charset="utf-8">
    <meta name="keywords" content="">
    <meta name="description" content="My description">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>
    
  </body>
</html>
```