#### (1) What are the advantages of Bootstrap? 
#### ans. 
**advantages:-**
* responsive design
* pre-built components
* easy customization
* cross-browser compatibility
* consistent design
* strong community support


#### (2)What is a Bootstrap Container, and how does it work? 
#### ans. 
A bootstrap container is a layout element that helps structures content.
* .container : responsive, with fixed width based on screen size.
* .container-fluid : stretches to full width of the screen.

**example:-**
```html
<html>
<head>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
<title>Bootstrap Container Example</title>
</head>
<body>

  <!-- Fixed-width container -->
  <div class="container">
    <h1>Fixed-width Container</h1>
    <p>This container adjusts its width based on the screen size.</p>
  </div>

  <!-- Full-width container -->
  <div class="container-fluid">
    <h1>Full-width Container</h1>
    <p>This container always takes up the full width of the screen.</p>
  </div>

</body>
</html>

```

#### (3) What are the default Bootstrap text settings?
#### ans.
* alignment 
* text weight
* text transform
* text color
* text decoration

**example:-**
```html
<html>
<head>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <title>Bootstrap Text Example</title>
</head>
<body>
  <div class="container">
    <!-- Text Alignment -->
    <p class="text-left">This text is left aligned.</p>
    <p class="text-center">This text is center aligned.</p>
    <p class="text-right">This text is right aligned.</p>

    <!-- Font Weight -->
    <p class="font-weight-bold">This text is bold.</p>
    <p class="font-weight-light">This text is light.</p>

    <!-- Text Transform -->
    <p class="text-uppercase">This text is uppercase.</p>
    <p class="text-lowercase">THIS TEXT IS LOWERCASE.</p>
    <p class="text-capitalize">this text is capitalized.</p>

    <!-- Text Color -->
    <p class="text-primary">This is primary text color.</p>
    <p class="text-muted">This is muted text color.</p>

    <!-- Text Decoration -->
    <p class="text-decoration-none">This text has no decoration.</p>
  </div>
</body>
</html>
```

#### (4) What do you know about the Bootstrap Grid System?
#### ans.
The Bootstrap Grid System divides the page into 12 columns.

* Rows: Use .row to start a new row.
* Columns: Use .col to create columns.
* Breakpoints: Adjusts layout for different screen sizes.
**example:-**
```html
<html>
<head>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <title>Bootstrap Grid Example</title>
</head>
<body>

  <div class="container">
    <div class="row">
      <div class="col-sm-12 col-md-6 col-lg-4">
        <div class="p-3 mb-2 bg-primary text-white">Column 1</div>
      </div>
      <div class="col-sm-12 col-md-6 col-lg-4">
        <div class="p-3 mb-2 bg-secondary text-white">Column 2</div>
      </div>
      <div class="col-sm-12 col-md-6 col-lg-4">
        <div class="p-3 mb-2 bg-success text-white">Column 3</div>
      </div>
    </div>
  </div>

</body>
</html>

```

#### (5) What is the difference between Bootstrap 4 and Bootstrap 5 
#### ans.
Here's a simple comparison between Bootstrap 4 and Bootstrap 5:

**(1) jQuery:-**
Bootstrap 4: Requires jQuery.
Bootstrap 5: No jQuery.

**(2) Grid System:-**
Bootstrap 4: 5 grid tiers.
Bootstrap 5: 6 grid tiers (adds xxl).

**(3) Forms:-**
Bootstrap 4: Basic form styles.
Bootstrap 5: Improved form styles.

**(4) Browser Support:-**
Bootstrap 4: Supports IE 10/11.
Bootstrap 5: No IE support.

**(5) Icons:-**
Bootstrap 4: No built-in icons.
Bootstrap 5: Includes Bootstrap Icons.





#### (6) What is a Button Group, and what is the class for a basic Button Group? 
#### ans.
A Button Group in Bootstrap groups buttons together in a row.
  * Use .btn-group for a basic button group.

  **example:-**
  ```html
<html>
<head>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <title>Button Group Example</title>
</head>
<body>
  <div class="container">
    <h3>Button Group Example</h3>
    <div class="btn-group">
      <button class="btn btn-primary">Left</button>
      <button class="btn btn-primary">Middle</button>
      <button class="btn btn-primary">Right</button>
    </div>
  </div>
</body>
</html>
  ```

  #### (7) How can you use Bootstrap to make thumbnails?
  #### ans.
  In Bootstrap, use .img-thumbnail to create thumbnails for images. It adds a border and rounded corners.
  **example:-**
  ```html
<html>
<head>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <title>Bootstrap Thumbnails Example</title>
</head>
<body>
  <div class="container">
    <h3>Bootstrap Thumbnail Example</h3>
    <img src="example.jpg" class="img-thumbnail" alt="Thumbnail Image" width="200">
  </div>
</body>
</html>
  ```

  #### (8) In Bootstrap 4, what is flexbox?
  #### ans.
  In Bootstrap 4, Flexbox helps create responsive layouts.
* .d-flex: Enables flexbox.
* .justify-content-center: Aligns items horizontally.
* .align-items-center: Aligns items vertically.

**example:-**
html
<html>
<head>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <title>Bootstrap Flexbox Example</title>
</head>
<body>
  <div class="container">
    <div class="d-flex justify-content-center align-items-center" style="height: 200px; background-color: lightgray;">
      <div>Centered Item</div>
    </div>
  </div>
</body>
</html>
```

#### (9) How can one create an alert in Bootstrap? 
#### ans.
```html
<html>
<head>
    <title>Document</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <div class="alert alert-success" role="alert">
        This is a success alert—check it out!
      </div>
      <div class="alert alert-secondary" role="alert">
  A simple secondary alert—check it out!
</div>
<div class="alert alert-info" role="alert">
  A simple info alert—check it out!
</div>
<div class="alert alert-warning" role="alert">
  A simple warning alert—check it out!
</div>
<div class="alert alert-danger" role="alert">
  A simple danger alert—check it out!
</div>
</body>
</html>
```


#### (10) What is a bootstrap card and how would you create one?
#### ans.
**example:-**
```html
<!DOCTYPE html>
<html>
<head>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <title>Bootstrap Card Example</title>
</head>
<body>
  <div class="container mt-3">
    <div class="card" style="width: 18rem;">
      <img src="https://cdn.pixabay.com/photo/2023/07/21/16/23/cat-8141916_640.jpg" class="card-img-top" alt="Image">
      <div class="card-body">
        <h5 class="card-title">Card Title</h5>
        <p class="card-text">This is some text within a card body.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
      </div>
    </div>
  </div>
</body>
</html>
```