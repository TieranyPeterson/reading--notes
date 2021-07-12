#CSS Notes

**What is Css**
-(Cascading Style Sheets)CSS is a language for specifying how documents are presented to users,how they are styled,and laid out.
EX: of Css 
-h1 {
    color: red;
    font-size: 5em;
}
**Three Ways to insert a style sheet:**

-External CSS
-Internal CSS
-Inline CSS

**External Css**
*External styles are defined within the <link> element, inside the <head> section of an HTML page:*
```<head>
<link rel="stylesheet" href="mystyle.css">**<<<<EXAMPLE**
</head>```

**Internal Css**
The internal style is defined inside the <style> element, inside the head section.
**EXAMPLE**```<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>```

**Inline Css**
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
**EXAMPLE**
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>