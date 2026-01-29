# Styling the website

The fun part. We need to style the website so it looks good, according to the requirements.

Here's a run down

## Requirements
- Use Arial font
- Use external stylesheet
- Use suitable padding/margins

### Header
- Black background (#000000)
- Set Logo font size to 40px
- Set font colour to white (#FFFFFF)
- Embolden the text
- Insert logo as shown
- Set width of logo to 100px

### Content
- Beige background (#F5F5DC)
- Text Area
    - Set width to 380px
    - Insert the headings as shown
    - Set font size of headings to 20px
    - Insert text as shown
    - Justify **About Us** and **Customer Reviews** texts
    - Italicise customer reviews text
    - Set services text to a bulleted list

## Styling

### Colors

Colors are cool or smth

For the header, add a black background

### Font

Let's settle the easiest part: font type.

With the universal css selector (`*`) we can make sure every font is set to arial. Set a fallback just in case

```css
* {
    font-family: 'Arial', sans-serif;
}
```

### Margins/Padding
Let's add padding and margins. First, to the whole site, with `<body>` to `<main>`

Add whatever looks right to you. Something that gives enough space but not too much empty space.

```css
body {
    padding: 1.6em;
}
```