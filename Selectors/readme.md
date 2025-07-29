# Element Selectors

Selects HTML elements based on their tag names

```
h1{
  color:red
}
```

# Universal Selectors

Targets and styles all elements on a webpage. Use Asterisk(\*) Method

```
*{
  margin:0
  padding:0
}
```

# id Property

Assign a unique identifier to a singlr HTML element. Use hash(#) method

```
<style>
  #heading{
    color:blue
  }
</style>
<body>
  <div id="heading">Use ID Property</div>
</body>
```

# class Property

Allows grouping of multiple HTML elements of style them collectively. Use dot(.) method

```
<style>
  .heading{
    color:blue
  }
</style>
<body>
  <div class="heading">Use class Property</div>
</body>
```

# Group Selector

Style multiple elements simultaneously. Seprates selectors with commas(,)

```
<style>
  h1 , p{
    color:blue
  }
</style>
<body>
  <h1>Group Selectors</h1>
  <p>This is paragraph for group selectors</p>
</body>
```
