## 4. **Traversing the DOM**
   - `parentNode`: Selects the parent node.
   - `children`: Selects all child elements.
   - `nextElementSibling`: Selects the next sibling element.
   - `previousElementSibling`: Selects the previous sibling element.

### **Code Example**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DOM Traversal</title>
</head>
<body>
  <ul>
    <li>Item 1</li>
    <li id="item2">Item 2</li>
    <li>Item 3</li>
  </ul>

  <script>
    const item2 = document.getElementById('item2');

    // Access the parent node
    console.log('Parent Node:', item2.parentNode);

    // Access all child nodes
    console.log('Children of Parent:', item2.parentNode.children);

    // Access the next sibling
    console.log('Next Sibling:', item2.nextElementSibling);

    // Access the previous sibling
    console.log('Previous Sibling:', item2.previousElementSibling);
  </script>
</body>
</html>
```