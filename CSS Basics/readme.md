## Inline Styles:

**This method allows you to apply styles directly to an HTML element using the style attribute. This method is useful for making quick, one-off style changes.**

```
<h1 style="color: red;">This heading containt red color</h1>
```

<hr>

## Internal Style Sheets:

**This method allows you to define the styles within the < head > section of your HTML document, using the < style > tag. This method is useful when you want to apply styles to a specific page only.**

```
<head>
  <style>
    h1 {
      color: red;
    }
  </style>
</head>
```

<hr>

## External Style Sheets:

**In this method, you can define the styles in a separate CSS file, which is then linked to your HTML document using the <link> tag. This method allows you to maintain consistent styles across multiple pages.**

```
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>

```
