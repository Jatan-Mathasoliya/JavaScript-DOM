## **1. Accessing Elements :**
 **There are some multiple methodes for access elements from HTML :**

- `getElementById`: Selects element by their id.
- `getElementByClassName` : Selects elements by their class name.
- `getElementByTagName`: Selects elements by their tag name.
- `qureySelector`: Selects first element by their CSS selector.
- `querySelectorAll`: Selects all elements by their CSS selector.

## **Code Example**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DOM Selectors</title>
</head>
<body>
  <h1 id="title">Hello, DOM!</h1>
  <p class="paragraph">This is a paragraph.</p>
  <p class="paragraph">This is another paragraph.</p>
  <button id="btn">Click Me</button>

  <script>
    // Using getElementById
    const title = document.getElementById('title');
    console.log('getElementById:', title);

    // Using getElementsByClassName
    const paragraphs = document.getElementsByClassName('paragraph');
    console.log('getElementsByClassName:', paragraphs);

    // Using getElementsByTagName
    const buttons = document.getElementsByTagName('button');
    console.log('getElementsByTagName:', buttons);

    // Using querySelector
    const firstParagraph = document.querySelector('.paragraph');
    console.log('querySelector:', firstParagraph);

    // Using querySelectorAll
    const allParagraphs = document.querySelectorAll('.paragraph');
    console.log('querySelectorAll:', allParagraphs);
  </script>
</body>
</html>
```