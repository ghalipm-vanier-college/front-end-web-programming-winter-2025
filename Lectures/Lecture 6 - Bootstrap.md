***Bootstrap*** is one of the most popular HTML, CSS, and JavaScript frameworks for building responsive, mobile-first websites. A closely related alternative is ***Tailwind CSS***, which takes a different approach to styling and design.  

Both **Bootstrap** and **Tailwind CSS** are widely used CSS frameworks for web development, each designed with a **mobile-first approach**. However, they differ significantly in their methodology and intended use cases.  

- **Bootstrap** provides **pre-built components** and a **grid system**, enabling **rapid development** with minimal custom styling.  
- **Tailwind CSS** follows a **utility-first approach**, offering highly customizable and flexible designs without relying on predefined components.  

Bootstrap requires specific metadata, CSS links, and a JavaScript bundle to be included in an HTML5 file:  

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8"> <!-- charset for bootstrap-->
  <meta name="viewport" content="width=device-width, initial-scale=1"><!-- scaling for bootstrap-->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"> <!-- styling for bootstrap-->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script> <!-- bundle JS script for bootstrap-->
</head>

</html>
```
Basic structure of Bootstrap consists of contanier, row, column. 
Container can have one or multiple rows and specific row can have one or more columns. 

```html
<body>
  <div class="container">
    <div class="row">
      <div class="col-md-4">Column 1</div>
      <div class="col-md-4">Column 2</div>
      <div class="col-md-4">Column 3</div>
    </div>
  </div>
</body>
````
