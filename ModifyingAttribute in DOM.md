## 3. **Modifying Attributes**
   - `setAttribute`: Sets an attribute on an element.
   - `getAttribute`: Gets the value of an attribute.
   - `removeAttribute`: Removes an attribute.

### **Code Example**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Modify Attributes</title>
</head>
<body>
  <img id="image" src="http://codinggita.com/placeholder.jpg" alt="Placeholder" />

  <script>
    const img = document.getElementById('image');

    // Get the src attribute
    console.log('Original src:', img.getAttribute('src'));

    // Modify the src attribute
    img.setAttribute('src', 'http://codinggita.com/new-image.jpg');
    console.log('Updated src:', img.getAttribute('src'));

    // Remove the alt attribute
    img.removeAttribute('alt');
    console.log('Alt attribute removed.');
  </script>
</body>
</html>
```
