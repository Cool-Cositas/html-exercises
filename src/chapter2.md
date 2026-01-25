# Setting Up

## Project structure

Create a folder somewhere with whatever name, this will be where your files are stored

Add `index.html` and `styles.css` files in that folder. These are the the files that make the webpage

Next, create an `assets` folder, and copy paste the files that you downloaded (or just copy the entire folder into your project folder)

This should be how your project looks

```plaintext
[project folder]/
  index.html
  styles.css
  assets/
  - [all the files from pearson]
```

## Making the HTML file

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

## Linking external CSS Sheet

Within the `<head>` element create a `<link>` tag for the stylesheet file. This is how it should look like:

```html
<link rel="stylesheet" href="styles.css">
```
>`rel` basically tells HTML what typa thing you want to link.<br>`href` is the path to that file you made.

___

## Checkpoint
Your CSS file should be empty for now

And your HTML file should look like this

```html
<!DOCTYPE HTML>
<html lang="en">
  <head>
    <title>My Website</title>
    <meta charset="utf-8">
    <meta name="keywords" content="">
    <meta name="description" content="My description">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    
  </body>
</html>
```